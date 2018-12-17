# Ansible Role: wsl

[![Build Status](https://img.shields.io/travis-ci/sbaerlocher/ansible.wsl.svg?branch=master&style=popout-square)](https://travis-ci.org/sbaerlocher/ansible.wsl) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-wsl-blue.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/wsl) [![Ansible Role](https://img.shields.io/ansible/role/d/id.svg?style=popout-square)](https://galaxy.ansible.com/sbaerlocher/wsl)

## Description

The role activates the windows wsl feature on a windows device.

## Installation

```bash
ansible-galaxy install sbaerlocher.wsl
```

## Requirements

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| wsl_enbale | false | in order for the function to be activated, it must be switched to true. |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - sbaerlocher.wsl
```

## Changelog

### 1.0.0

* inital commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2019, Simon Bärlocher