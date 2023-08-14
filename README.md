SYSTEM CONTROLS APPLET
======================
Minimal system controls applet for Cinnamon Desktop Environment

> Fork of https://github.com/linuxmint/cinnamon-spices-applets/tree/master/system-controls%40rcalixte  
> Uses loginctl instead systemctl  
> Original author: rcalixte

DESCRIPTION
-----------
This is an applet that adds an icon in the panel that provides access to the
following system controls functions:
 * Restart Cinnamon
 * Lock Screen
 * Switch User (if enabled in system settings)
 * Log Out
 * Suspend
 * Hibernate
 * Restart
 * Power Off

As of now, the action executes immediately without prompt or verification.

Portions of this code were adapted from the user@cinnamon.org applet created by
the Cinnamon Team.

COMPATIBILITY
-------------
This applet has been tested to be compatible with Cinnamon 5.4+.

DEPENDENCIES
------------
This applet depends on the following packages being installed:
  * cinnamon-screensaver
  * cinnamon-session
  * loginctl

INSTALLATION
------------

1. `git clone https://github.com/xHyroM/cinnamon-system-controls.git`
2. `mv cinnamon-system-controls/files/system-controls@xhyrom ~/.local/share/cinnamon/applets`
3. Done :D
