# Install Azure CLI

Ansible role to install baseline packages for Ubuntu images. Also updates all packages.

## Installation

Add to requirements.yml, e.g.:

```yaml
---
- src: https://github.com/richeney/ansible-role-common
  name: common
...
```

Then run the following command to install:

`sudo ansible-playbook install --role-file requirements.yml --roles-path=/etc/ansible/roles`

## Example Playbook

```yaml
- hosts: all
  roles:
    - common
```

## Requirements

None.

## Dependencies

None.
