
# Prerequisites

* Vagrant : version >= 2.0
* VirtualBox : version >= 5.1.30

# How to test locally

## Create tests VMs

```
vagrant up
vagrant ssh-config > generated_ssh_config
```

## Launch portchecker with ansible playbook

```
ansible-playbook -i inventories/LOCAL.ini main.yml
```
