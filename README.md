Role Name
=========

Install Extra Packages for Enterprise Linux Edit

Requirements
------------

This role is applicable on CentOS and RHEL machines.

Role Variables
--------------

None known.

Dependencies
------------

robertdebock/bootstrap is an optional dependency to allow Ansible to run on clients.

Example Playbook
----------------

```
---
- hosts: servers
  become: yes
  roles:
    - epel
```

License
-------

Apache License, Version 2.0

Author Information
------------------

Robert de Bock <robert@meinit.nl>