Ratpoison - Say good-bye to the rodent
--------------------------------------

*This is Ratpoison patched to fix problems with border transparency when
used with Picom. Patch is similar in implementation to
[fix-border](https://dwm.suckless.org/patches/alpha/dwm-fixborders-6.2.diff)
from DWM.*

Copyright (C) 2000, 2001, 2002, 2003, 2004 Shawn Betts

Copying and distribution of this file, with or without modification,
are permitted in any medium without royalty provided the copyright
notice and this notice are preserved.

About
-----

ratpoison is a simple Window Manager with no fat library dependencies,
no fancy graphics, no window decorations, and no flashy wank. It is
largely modelled after GNU Screen which has done wonders in virtual
terminal market.

All interaction with the window manager is done through
keystrokes. ratpoison has a prefix map to minimize the key clobbering
that cripples Emacs and other quality pieces of software.

Building
--------

ratpoison uses autoconf and automake. To build it:

```
$ ./configure && make
```

if you want to install it system-wide, simply type 'make install' as
a privileged user:

```
# make install
```

If you retrieved ratpoison from the source repository, you will have to
install somewhat recent versions of autoconf and automake before
running:

```
$ ./autogen.sh
```

Customization
-------------

Use the configure option '--enable-debug' to enable debugging symbols
and verbose logging.

Use the configure option '--with-xterm=PROG' to set the x terminal
emulator to use. The default is `xterm`.

Consult the INSTALL file for more information about the configure script.

Using
-----

See the info manual for more information.
