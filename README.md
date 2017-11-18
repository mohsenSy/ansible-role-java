Role Name
=========

A simple ansible role to install java.

Requirements
------------

No special requriements

Role Variables
--------------

* JAVA_VERSION: the version of java you want to install (default is 8)

Dependencies
------------

No Dependencies

Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: moshenSy.java, JAVA_VERSION: 7 }

License
-------

BSD

Author Information
------------------

If you have any question please contact me on

[twitter](https://twitter.com/mouhsen_ibrahim)

[linkedin](https://linkedin.com/in/mohsen-ibrahim-670b13112/)

email mohsen47@hotmail.co.uk
