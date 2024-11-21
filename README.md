Ansible role roon-on-wine
=========================

Install Roon GUI

Requirements
------------

Wine

Role Variables
--------------
To force a re-install set roon_on_wine_reinstall to true

    roon_on_wine_reinstall: false

Dependencies
------------

None

Example Playbook
----------------

    - hosts: desktop
      roles:
        - roon-on-wine

License
-------

This software is available under the MIT license. See the LICENSE file for more info.

Author Information
------------------

oosten246
