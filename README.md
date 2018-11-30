shellbro.nux-dextop
===================

[![Build Status](https://travis-ci.org/shellbro/ansible-role-nux-dextop.svg?branch=master)](https://travis-ci.org/shellbro/ansible-role-nux-dextop)

Ansible role for adding nux-dextop repository (CentOS 7).

Requirements
------------

None

Role Variables
--------------

* rpm_url - URL to nux-dextop RPM (required)

Dependencies
------------

* shellbro.epel

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: shellbro.nux-dextop
          rpm_url: http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-5.el7.nux.noarch.rpm

License
-------

BSD

Author Information
------------------

Jakub Gorczyca
