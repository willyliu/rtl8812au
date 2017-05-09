rtl8812au
=========

Linux kernel driver for rtl8812au/rtl8821au/rtl8811au USB WiFi chipsets.

Experimental build of driver-5.1.5 branch from uminokoe/rtl8812AU, with some
patches from diederikdehaas/rtl8812AU to build it on RPi / ArchLinuxARM.

| For ArchLinuxARM PKGBUILD for Raspberry Pi (armv7h), see:
|   https://github.com/mk-fg/archlinux-pkgbuilds/tree/master/rtl8812au-5.1.5-rpi-git

Note that I'm not supporting or developing this driver here, just collected a
bunch of ad-hoc patches from different sources for my own purposes.


Links
-----

Repositories that seem to be most active (as of April 2017) wrt info on this
driver, i.e. places to watch for new issues, commits, pull requests and forks
(in no particular order):

- https://github.com/abperiasamy/rtl8812AU_8821AU_linux
- https://github.com/uminokoe/rtl8812AU/
- https://github.com/diederikdehaas/rtl8812AU/
- https://github.com/astsam/rtl8812au/ (esp. for 8814A and radiotap stuff)
- https://github.com/gnab/rtl8812au/
- https://github.com/Grawp/rtl8812au_rtl8821au/
- https://github.com/ulli-kroll/rtl8821au/

Not all (or any?) of these forks are linked under "Forks" tab on github.

Be sure to check different branches in these, as there are several different
upstream sources (dumps) for this driver, which these are usually based on.

More general links:

- Datasheet: https://wenku.baidu.com/view/733fb49602020740be1e9bb0.html
