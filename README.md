Role Name
=========

Ansible Monitoring Role for IOTA Node

Requirements
------------

This role is used by Ansible playbooks such as [IRI-Playbook](https://github.com/nuriel77/iri-playbook) and [Hornet-Playbook](https://github.com/nuriel77/hornet-playbook).

Role Variables
--------------

Variables can be found in [defaults](defaults/)

Dependencies
------------

[Ansible-Docker](https://github.com/nuriel77/ansible-docker)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-monitoring, x: 42 }

License
-------

MIT

Author Information
------------------

[Nuriel Shem-Tov](https://github.com/nuriel77)
