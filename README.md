u8glib: Universal Graphics Library for 8 Bit Embedded Systems
=============================================================

This repository hosted on [github](https://github.com/pabigot/u8glib) is a
mirror of [u8glib](http://code.google.com/p/u8glib/).

*Universal Graphics Library for 8 Bit Embedded Systems* is a graphics
library specifically useful for text and graphical output to LCDs commonly
used in microcontroller platforms.

The git clone exists primarily to simplify inclusion of u8glib as a
sub-repository in git-based projects.

- Branch `upstream` is intended to track the default branch of the original
  Mercurial repository.  Updates are done manually.

- Branch `master` provides this file and merges from `upstream`.

- Other branches may be present.

Details of Import
-----------------

Initial creation was done with the following commands:

    git clone git://repo.or.cz/fast-export.git
    
    hg clone https://code.google.com/p/u8glib/ u8glib.hg
    
    git init u8glib
    cd u8glib
    ../fast-export/hg-fast-export.sh \
      -r /opt/u8glib.hg \
      -M upstream

As upstream changes are made this file will be updated with instructions for
synchronizing them into the upstream branch.
