SBT
=========

[![Build Status](https://travis-ci.com/triviadata/sbt.svg?branch=master)](https://travis-ci.com/triviadata/sbt)

Install SBT on Linux host.

Requirements
--------------
None.

Role Variables
--------------
Variables are listed in `defaults/main.yml` and desribed below:

* **sbt_yum_repository**: URL address for YUM repository
* **sbt_apt_repository**: URL address for APT repository
* **sbt_apt_keyserver**: keyserver for APT repository
* **sbt_apt_key_id**: identifier of the key for APT repository

Dependencies
----------------
None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: triviadata.sbt

License
-------

BSD

Author Information
-------
This role was created in July 2019 by Matus Cuper
