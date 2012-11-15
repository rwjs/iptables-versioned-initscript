NAME:
========
iptables-versioned-initscript

SYNOPSIS:
========
/etc/init.d/iptables [start|stop|restart|status|save|revert {n}|rollback {n}]

DESCRIPTION:
========
As Debian seems to have depreciated the init script for iptables, this is a basic drop-in replacement. The only notable feature is that it does handle basic firewall rule versioning.

AUTHOR:
========
Robert W.J. Stewart

TODO:
========
 - Add a timed restart (requiring a user prompt to commit the rules)

