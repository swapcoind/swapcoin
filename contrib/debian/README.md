
Debian
====================
This directory contains files used to package swapd/swap-qt
for Debian-based Linux systems. If you compile swapd/swap-qt yourself, there are some useful files here.

## swap: URI support ##


swap-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install swap-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your swap-qt binary to `/usr/bin`
and the `../../share/pixmaps/swap128.png` to `/usr/share/pixmaps`

swap-qt.protocol (KDE)

