
Debian
====================
This directory contains files used to package putind/putin-qt
for Debian-based Linux systems. If you compile putind/putin-qt yourself, there are some useful files here.

## putin: URI support ##


putin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install putin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your putinqt binary to `/usr/bin`
and the `../../share/pixmaps/putin128.png` to `/usr/share/pixmaps`

putin-qt.protocol (KDE)

