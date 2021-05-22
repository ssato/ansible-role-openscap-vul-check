# ansible-role-openscap-vul-check

Ansible Role to check vulnerabilities of target nodes using openscap with SCAP
content such like security data provided from
https://www.redhat.com/security/data/metrics/.

![GitHub Actions Status](https://github.com/ssato/ansible-role-openscap-vul-check/workflows/Tests/badge.svg)

## requirements

- Linux Server running RHEL
- oscap command
  - openscap-scanner RPM package provides it
- Security Reference data available from https://www.redhat.com/security/data/metrics/

## role variables

see YAML files under defaults/.

## example playbook

TBD

## license

MIT

## Author

Satoru SATOH [ssato@Github](https://github.com/ssato)
