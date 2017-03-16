ansible-role-intellij
=====================

Ansible role to install IntelliJ IDEA Ultimate Edition

These are the differences to the original authors version:

* Installs the Ultimate instead of the Community Edition
* Other IntelliJ versions previously installed by this role while automatically be removed if a newer/other version is installed.
* The archive is only downloaded and installed if the same version is not already installed.

# Usage
```
 - hosts: all
   roles:
     - intellij
```

# Notes
- Required Java installed
