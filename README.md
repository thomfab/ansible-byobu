Byobu
=====

This role installs byobu (http://byobu.co/).

Role Variables
--------------

One variable can be set : byobu_launch_by_default
If set to True, byobu will be the default shell when a user logs in, which is very useful for remote administration via ssh.


Example Playbook
----------------

Example :

    ---
    - hosts: servers
      roles:
         - { role: thomfab.ansible-byobu, byobu_launch_by_default: True }

License
-------

BSD
