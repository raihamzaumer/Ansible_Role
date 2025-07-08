# Ansible Role: httpd

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-raihamzaumer.httpd-blue.svg)](https://galaxy.ansible.com/raihamzaumer/httpd)

## Description

This Ansible role installs and starts the Apache HTTP server (`httpd`) on RHEL/CentOS-based systems.

## Requirements

- Ansible >= 2.9
- Target OS: RHEL/CentOS 7/8

## Role Variables

No variables are required for this role.

## Dependencies

None

## Example Playbook

```yaml
- name: Install Apache using httpd role
  hosts: all
  become: true
  roles:
    - raihamzaumer.httpd
