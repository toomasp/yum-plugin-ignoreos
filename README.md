yum-plugin-ignoreos
===================

Yum plugin for ignoring target OS with per-repository settings.
Useful when you want to install noarch packages on operating systems that trigger the target OS check.


Plugin Installation
-------------------

1. Copy yum_ignoreos.conf file into $pluginconfpath/ ( /usr/share/yum-plugins on RedHat/CentOS )
2. Copy yum_ignoreos.py file into $pluginpath/ ( /etc/yum/pluginconf.d on RedHat/CentOS )

Repository configuration
------------------------

Set ignore_os=1 inside the repository configuration file.

