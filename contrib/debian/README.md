
Debian
====================
This directory contains files used to package speedd/speed-qt
for Debian-based Linux systems. If you compile speedd/speed-qt yourself, there are some useful files here.

## speed: URI support ##


speed-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install speed-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your speed-qt binary to `/usr/bin`
and the `../../share/pixmaps/speed128.png` to `/usr/share/pixmaps`

speed-qt.protocol (KDE)

