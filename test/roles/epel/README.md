Role Name
=========

Ensures that EPEL is installed on the system.

Requirements
------------

None.

Role Variables
--------------

| Name              | Default Value       | Description          |
|-------------------|---------------------|----------------------|
| `epel_disable` | false | Disables EPEL repository |

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

	- hosts: all
		remote_user: root
		vars:
			epel_disable: false
		roles:
			- ansible-epel


Testing
-------

1. Export a test inventory, otherwise it will run on localhost:

`export TEST_INVENTORY=/home/opiske/code/infra/test-inventory-ansible/hosts`

2. Run:
`make test`

License
-------

Apache 2.0


Author Information
------------------

Messaging QE team @ redhat.com
