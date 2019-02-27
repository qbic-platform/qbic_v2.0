
Debian
====================
This directory contains files used to package qbiccoind/qbiccoin-qt
for Debian-based Linux systems. If you compile qbiccoind/qbiccoin-qt yourself, there are some useful files here.

## qbiccoin: URI support ##


qbiccoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qbiccoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qbiccoinqt binary to `/usr/bin`
and the `../../share/pixmaps/qbiccoin128.png` to `/usr/share/pixmaps`

qbiccoin-qt.protocol (KDE)

