# izFirewall
izFirewall is the InitZero Linux firewall subsystem

## Installation
copy the izfirewall script into /etc/init.d/ directory and run (if using a RedHat based Linux distro):

```
chkconfig izfirewall --add
chkconfig izfirewall on
```

## Usage

edit the main script configuring the base network adapters variables and edit the various sections containing the Firewall Zones
