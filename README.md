repo-remi
=========

[![Build Status](https://travis-ci.org/wate/ansible-role-repo-remi.svg?branch=master)](https://travis-ci.org/wate/ansible-role-repo-remi)

remiリポジトリのインストールとセットアップを行います


Role Variables
--------------

### repo_remi_enabled

インストール後にリポジトリを有効化するか否かを指定します。

```yaml
repo_remi_enabled: yes
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: repo-remi }
```


License
-------

MIT
