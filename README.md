Ansible Role: Setup docker-compose for Raspberry Pi
=========

Ansible role to install docker-compose on Raspberry Pi.

Requirements
------------

- Docker

Role Variables
--------------

- docker_compose_version: 1.29.2
- docker_compose_checkout_dir: /tmp/compose
- docker_compose_bin_path: /usr/local/bin
- docker_compose_arch: armv7l

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: localhost
      roles:
         - { role: wagawo.docker_compose_pi }
```

License
-------

MIT

Author Information
------------------

[Twitter](https://twitter.com/wagawo)
