# Ansible role: phpmyadmin
Installs phpMyAdmin via composer.

## Requirements
None.

## Role Variables
|Key|Type|Description|Default|
|:--|:---|:----------|:------|
|phpmyadmin_web_user|String||nginx|
|phpmyadmin_web_group|String||nginx|
|phpmyadmin_working_dir|String||/var/www|
|phpmyadmin_install_dir|String||/var/www/phpmyadmin|

## Dependencies
+ [composer](https://github.com/shomatan/ansible-composer.git)

## Example playbook

```yaml
- hosts: all
  roles:
    - { role: phpmyadmin }
  vars:

```
