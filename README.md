# Ansible role 'ansible-role-nvidia'

An Ansible role for setting up Nvidia proprietary drivers (non-bumblebee).

## Requirements
- Arch Linux, or
- Fedora

## Role Variables
| Variable		| Default		| Comments (type) |
| :---			| :---			| :---		  |

## Dependencies
Fedora requires the [RPM Fustion (nonfree) repository](https://rpmfusion.org).
```Shell
$ sudo ansible-galaxy install -r requirements
```

## Example Playbook
```Yaml
- hosts: foo
  roles:
    - role: ansible-role-nvidia
```

## Testing


## License

BSD

## Contributors

Issues, feature requests, ideas, suggestions, etc. are appreciated and can be posted in the Issues section. Pull requests are also very welcome. Please create a topic branch for your proposed changes, it's the easiest way to merge back into the project.

- [Oscar Petersson](https://github.com/oscpe262/) (Maintainer)
