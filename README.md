[![Build Status](https://travis-ci.org/offtechnologies/ansible-role-afpd.svg?branch=master)](https://travis-ci.org/offtechnologies/ansible-role-afpd) [![Galaxy](http://img.shields.io/badge/galaxy-offtechnologies-brightgreen.svg)](https://galaxy.ansible.com/offtechnologies/afpd/)


An Ansible Role that: .configure and make and make install afpd on Ubuntu 16.10
<br>
More info on [Netatalk](http://netatalk.sourceforge.net/wiki/index.php/Install_Netatalk_3.1.10_on_Ubuntu_16.04_Xenial) wiki.



## Requirements
Ubuntu 16.10 (should also works with Debian 8)

## Role Variables

(see `defaults/main.yml`)

netatalk_version: "3.1.10"


Example Playbook
----------------

    - hosts: lab
      roles:
         - { role: offtechnologies.afpd }

License
-------
BSD
