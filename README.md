Role Name
=========

Installs Tomcat 8

Requirements
------------

Java8 (tested with Oracle java 8) for example ragingbal.java8

Role Variables
--------------

None

Dependencies
------------

ragingbal.java8 , which installs Java8 and sets JAVA_HOME variable to /usr/lib/jvm/java-8-oracle

Example Playbook
----------------
    - hosts: all
      roles:
         - ragingbal.java8
         - ragingbal.tomcat8

License
-------

Apache

Author Information
------------------

Raging Bal
