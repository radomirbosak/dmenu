# dmenu

My fork of **dmenu** adds
* keyboard shortcut Super_L for exiting
* option `-o` to choose an option based on the first keypress (without needing to press Enter)


## Dependencies on Ubuntu

* `libxft-dev`
* `libxinerama-dev`


# Original readme

dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X.


Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
