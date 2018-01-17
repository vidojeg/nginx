Nginx and Certbot
=========

Automatization for Nginx and Certbot. Istalling web server with(out) SSL certificate for statical sites.

Requirements
------------

  - Ansible 2.4
  - CentOS 7 minimal (clear istallation)
  - Ubuntu 16.04 minimal (clear istallation)

Dependencies
------------
If you have install only Nginx use tags: *nginx*

Example Playbook
----------------


    - hosts: all
      become: yes
      roles:
         - ../nginx

License
-------

BSD

Author Information
------------------

@vidojeg
