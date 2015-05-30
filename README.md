## vnstat

[![Travis CI](http://img.shields.io/travis/ypid/ansible-vnstat.svg?style=flat)](http://travis-ci.org/ypid/ansible-vnstat)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-ypid.vnstat-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/3315)
[![Platforms](http://img.shields.io/badge/platforms-debian%20/%20ubuntu-lightgrey.svg?style=flat)](#)



### Installation

This role requires at least Ansible `v1.3`. To install it, run:

    ansible-galaxy install ypid.vnstat

To install via git, run either:

    git clone https://github.com/ypid/ansible-vnstat ypid.vnstat
    git submodule add https://github.com/ypid/ansible-vnstat roles/ypid.vnstat




### Role variables

List of default variables available in the inventory:

    ---
    
    vnstat_config_options_integer:
      MaxBandwidth: 0
    
    vnstat_group_config_options_integer: {}
    vnstat_host_config_options_integer: {}




### Authors and license

`vnstat` role was written by:

- [Robin Schneider](https://github.com/ypid) | [e-mail](mailto:ypid@riseup.net)

License: [AGPLv3](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-%28agpl-3.0%29)

***

README generated by [Ansigenome](https://github.com/nickjj/ansigenome/).
