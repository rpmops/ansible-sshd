## [![DebOps project](http://debops.org/images/debops-small.png)](http://debops.org) sshd

[![Travis CI](http://img.shields.io/travis/debops/ansible-sshd.svg?style=flat)](http://travis-ci.org/debops/ansible-sshd) [![test-suite](http://img.shields.io/badge/test--suite-ansible--sshd-blue.svg?style=flat)](https://github.com/debops/test-suite/tree/master/ansible-sshd/)  [![Ansible Galaxy](http://img.shields.io/badge/galaxy-debops.sshd-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/1602)

[OpenSSH](http://www.openssh.com/) is a secure replacement for `telnet`
and other remote control programs. It allows you to connect to remote hosts
over encrypted communication channel and perform variety of tasks. It's
also primary communication channel used by Ansible.

### Installation

This role requires at least Ansible `v1.7.0`. To install it, run:

    ansible-galaxy install debops.sshd

### Documentation

More information about `debops.sshd` can be found in the
[official debops.sshd documentation](http://docs.debops.org/en/latest/ansible/roles/ansible-sshd/docs/).


### Role dependencies

- `debops.ferm`
- `debops.sshkeys`
- `debops.secret`
- `debops.apt_preferences`
- `debops.tcpwrappers`

### Are you using this as a standalone role without DebOps?

You may need to include missing roles from the [DebOps common
playbook](https://github.com/debops/debops-playbooks/blob/master/playbooks/common.yml)
into your playbook.

[Try DebOps now](https://github.com/debops/debops) for a complete solution to run your Debian-based infrastructure.





### Authors and license

`sshd` role was written by:
- Maciej Delmanowski | [e-mail](mailto:drybjed@gmail.com) | [Twitter](https://twitter.com/drybjed) | [GitHub](https://github.com/drybjed)

License: [GPLv3](https://tldrlegal.com/license/gnu-general-public-license-v3-%28gpl-3%29)

***

This role is part of the [DebOps](http://debops.org/) project. README generated by [ansigenome](https://github.com/nickjj/ansigenome/).
