# Ansible Collection - nfaction.bootstrap

Documentation for the collection.

## Using this Collections

```shell
ansible-galaxy collection install nfaction.bootstrap
```

## Git Subtree

**First time only**

Adding Ansible roles from outside

```shell
# internal
git subtree add --prefix=roles/ssh_config git@github.com:nfaction/ansible-ssh-config.git master --squash
git subtree add --prefix=roles/bootstrap git@github.com:nfaction/ansible-bootstrap.git master --squash
git subtree add --prefix=roles/ssh_port_probe git@github.com:nfaction/ansible-ssh-port-probe.git master --squash
git subtree add --prefix=roles/x0_vnc git@github.com:nfaction/ansible-x0-vnc.git master --squash
git subtree add --prefix=roles/ntp git@github.com:nfaction/ansible-ntp.git master --squash
git subtree add --prefix=roles/proxmox-config git@github.com:nfaction/proxmox-config.git master --squash
# external
git subtree add --prefix=roles/docker https://github.com/lean-delivery/ansible-role-docker.git master --squash
```

Updating subtrees

```shell
# internal
git subtree pull --prefix=roles/ssh_config git@github.com:nfaction/ansible-ssh-config.git master --squash
git subtree pull --prefix=roles/bootstrap git@github.com:nfaction/ansible-bootstrap.git master --squash
git subtree pull --prefix=roles/ssh_port_probe git@github.com:nfaction/ansible-ssh-port-probe.git master --squash
git subtree pull --prefix=roles/x0_vnc git@github.com:nfaction/ansible-x0-vnc.git master --squash
git subtree pull --prefix=roles/ntp git@github.com:nfaction/ansible-ntp.git master --squash
git subtree pull --prefix=roles/proxmox-config git@github.com:nfaction/proxmox-config.git master --squash
# external
git subtree pull --prefix=roles/docker https://github.com/lean-delivery/ansible-role-docker.git master --squash
```
