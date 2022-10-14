---
title: "Desktops in Raspberry Pi OS"
date: 2022-10-11T20:41:44-05:00
draft: false 
category: elinux
translationKey: "pi desktops"
---

The graphical environment for a Linux system is typically called the _desktop_, and it is not a requirement for a Linux system to have one. Most Linux servers do not use the desktop, in fact; the standard interaction with the server is through the _command line interface_, either through the console shell or a terminal emulator. In eLinux systems, the desktop is often an afterthought, or oriented towards a mobile system, which uses a touchscreen as the primary peripheral input device.

Raspberry Pi OS is a special case for eLinux, because it has almost enough resource power and OS support to enable a full traditional Linux desktop environment. I say 'almost' because there are only a few desktop environments lightweight enough to be handled smoothy and speedily by the RPi hardware resources. Gnome and KDE, for example, are both too heavy to be run on a RPi4b (the latest generation of hardware as of this writing)