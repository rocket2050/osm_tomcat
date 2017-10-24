Ansible Role for Tomcat
=========

This an ansible role for RedHat and Debian Family

Requirements
------------
There is no any further requirment there is only need an Debian and RedHat machine

Role Variables
--------------
The role variables are in [vars](https://github.com/opstree-ansible/osm_tomcat/blob/release-1.1/vars/main.yml)

Dependencies
------------

The dependency for Tomcat is Apache and Java

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: "{{ hosts }}"
      roles:
         - { role: osm_tomcat }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
