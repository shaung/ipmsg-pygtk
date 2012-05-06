About
=====
pyipmsg is an IP Messenger(http://www.ipmsg.org) alternative for Gnome, written in python.


Requirements
============
 * Python 2.6
 * Gtk 2.18+


Dependencies
============
 * ipmsg
 * python-notify
 * python-keybinder

Notice: Only tested with Ubuntu 10.04 / Python 2.6 / gtk 2.20


Installation
============
To install::

    sudo python setup.py install

Then add "pyipmsg" to the panel.


Known issues
============
The M2Crypto package on Pypi seems not working properly.
If you encounterd errors while installing M2Crypto using easy_install,
try download the package and manually install it instead.
Besides, it requires SWIG and OpenSSL being installed.
Hopefully the dependency to M2Crypto will be removed in the next version of Pyipmsg.


Tips
====
You can use the <Meta>I shortcut to activate the main menu.

