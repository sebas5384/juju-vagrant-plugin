juju-vagrant-plugin
===================

Juju Vagrant command plugin.


Objectives / User Stories
=========================
Pipe juju commands into the vagrant image

- Juju vagrant deploy X
- Juju vagrant deploy Local X
- juju vagrant destroy
- juju vagrant bootstrap 
Fetch the boxfile
Generate the template VagrantFile

Requirements:
=============
- Cross operating system code - eg: don’t hard code paths.

Risks:
======

- Wrapping SSHUTTLE can cause kernel panics on MacOSX 
- SShuttle only forwards web traffic, and does not respect ICMP/ some UDP packets.

Validating the hypothesis:
==========================
- Making some survey to receive some inputs form currently users.
something like survey monkey.

Milestone #1:
=============
- juju vagrant bootstrap
