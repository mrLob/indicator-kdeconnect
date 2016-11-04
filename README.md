KDE Connect Indicator
=====================

This Indicator is written to make [KDE Connect](https://community.kde.org/KDEConnect) usable in Ubuntu and Pantheon DE, but it can work on another distros that supporting Gtk 3 and libindicator3.
It's started as an [AppIndicator](https://unity.ubuntu.com/projects/appindicators/) but later i add a binary file to send file and url easily through KDE Connect.

Features: 
-------
 1. Indicator in the panel which show your devices, with its name, status, and battery.
 2. Menu to request for pairing and unpairing.
 3. Menu to start sftp and open file browser.
 4. Menu to send files.
 5. A small program, `kdeconnect-send` to help sending file and choosing device.
 6. A .contractor file, so you can send file from any of elementary OS's applications.
 7. Menu to ring and find your phone.
 8. From the device status menu you can get encryption information.
 9. From the device name menu item you can open kdeconnect settings.

Limitation
-------
Currently this is have some limitation:
 1. After changes on KDE Connect this will work only in KDE Connect 1.0.0 and up

Usage Suggestions
-------
 To make life better you can try to apply this:

 1. add KDE Connect Indicator to your startup applications, on your System Setting.
 2. for Nautilus or Thunar user, create a Nautilus-actions or Thunar-actions entry with  `kdeconnect-send %f`as  command.
 3. or you can use the file manager scripts present on the scripts folder.

Please report issues and suggestion here:
https://github.com/Bajoja/indicator-kdeconnect
