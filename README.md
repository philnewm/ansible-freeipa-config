# Freeipa-config-Role

[![Alma9-CI](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/alma9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/alma9-ci-caller.yml)  [![Rocky9-CI](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/rocky9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/rocky9-ci-caller.yml)  [![CentOSStream9-CI](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/centosstream9-ci-caller.yml/badge.svg)](https://github.com/philnewm/ansible-freeipa-config/actions/workflows/centosstream9-ci-caller.yml)

Role description

This role includes a vagrant based molecule testing setup as a submodule at `molecule/`

## Structure

```code
📦 ansible-freeipa-config
 ┣ 📂 defaults
 ┃ ┗ 📜 main.yml
 ┣ 📂 meta
 ┃ ┗ 📜 main.yml
 ┣ 📂 molecule
 ┃ ┗ 📂 default
 ┃   ┗ 📜, 📜, 📜, scenario_files
 ┣ 📂 tasks
 ┃ ┣ 📜 main.yml
 ┃ ┣ 📜 absent.yml
 ┃ ┣ 📜 present.yml
 ┃ ┗ 📜 tests.yml
 ┣ 📂 vars
 ┃ ┗ 📜 main.yml
 ┗ 🗒️ README.md
 ┗ 📓 requirements.yml

```

Describe and explain role structure.

## Requirements

Elaborate external dependencies and how to use them.

## Role Variables

* defaults/main.yml
  * first_var
  * sec_var
  * third_var
* vars/main.yml
  * first_var
  * sec_var
  * third_var

## Dependencies

List role ansible-galaxy dependencies - if any.

## Example Playbook

Add an example playbook

```yaml
---

tasks:
  - name: Include ansible-freeipa-config present
    ansible.builtin.include_role:
      name: ansible-freeipa-config
    vars:
      state: present

...
```

## License

Add license - if any.
