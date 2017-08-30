# ansible-role-accelppp
This repository contains a ansible role for installing accel-ppp from source

Following variables need to be provided for role to run correctly -
* `accel_version` is the git branch or tag of accel-ppp that needs to be cloned. This role is tested with `1.11`
* `source_dir` is the full directory path where accel-ppp source code will be downloaded. E.g. `\opt`
* `build_option` is the cmake option flags if any.

This playbook will need connectivity to internet to clone the accel-ppp git repository.
