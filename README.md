# Review Red Hat OpenStack Environment Health

```
$ git clone https://github.com/openstack-healthcheck/environment-healthcheck.git 
$ cd environment-healthcheck/
$ source ~/stackrc
$ source ansible-test-env.rc
$ tripleo-ansible-inventory --static-yaml-inventory inventory.yaml
$ ansible-galaxy collection install community.general
$ ansible-playbook -i inventory.yaml ./playbooks/<playbook_name>.yaml
```
