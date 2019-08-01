# Ansible Role: Samba (SMB)

Installs Samba client and server for RHEL/CentOS.

This is a personal fork of https://github.com/geerlingguy/ansible-role-samba.

## Requirements

Samba requires ports 137, 138, 139, 445 to be open to function properly. For easy firewall configuration, you can use the `geerlingguy.firewall` role.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: servers
      roles:
        - geerlingguy.samba

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).
