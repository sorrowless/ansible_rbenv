# sbog/rbenv

[![Build Status](https://travis-ci.com/sorrowless/ansible_rbenv.svg?branch=master)](https://travis-ci.com/sorrowless/ansible_rbenv)
[![Ansible Role](https://img.shields.io/ansible/role/00000)](https://galaxy.ansible.com/sorrowless/rbenv)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/00000)](https://galaxy.ansible.com/sorrowless/rbenv)
[![Ansible Role](https://img.shields.io/ansible/role/d/00000)](https://galaxy.ansible.com/sorrowless/rbenv)
[![GitHub](https://img.shields.io/github/license/sorrowless/ansible_rbenv)](https://github.com/sorrowless/ansible_rbenv/blob/master/LICENSE)

An Ansible role which installs and configures [rbenv](https://github.com/rbenv/rbenv) on Linux

## Requirements

Ansible 2.7+

## Role Variables

You can see all vars in `defaults/main.yml` vars file.

## Dependencies

None

## Example Playbook

```yaml
- name: Ensure rbenv DB
  hosts: rbenvs
  remote_user: root

  roles:
    - rbenv
```

## License

Apache 2.0

## Author Information

This role was created by [Stan Bogatkin](https://sbog.ru).
