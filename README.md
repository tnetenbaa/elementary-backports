# elementary backports
Like OS 8's new features? Can't wait for the full release? Or just don't want to upgrade right away?
I've got you covered!

This project aims to recreate features from the yet-to-release Elementary OS 8, as faithfully as possible, within OS 7. 

# Features Included:

-Dock redesign

-New cursor theme

# How to Install

## Dock

The dock themes can be installed one of two ways, single user or system-wide. 

**Single User**: Push the folders `plank` and `plank-dark` to `/home/(user)/.local/plank/themes`. Hold CTRL and Right Click on Plank, select *Preferences*, and select either theme. Single User install does not support automatic switching between light and dark mode.

**System-Wide**:Right Click Files and select *Open As Administrator*. Enter your password and navigate to `/usr/share/themes`. Copy `plank` and `plank-dark`from this repository into each Elementary stylesheet folder. 

**WARNING: Be sure to back up `plank` and `plank-dark` from at least one of the stylesheet folders in case you wish to revert changes**.

## Cursor

Right Click Files and select *Open As Administrator*. Enter your password and navigate to `/usr/share/icons/elementary`. Remove the directory `cursors`. 

**WARNING: Back up this directory before removing.**

Unzip `cursors.zip` from this repository in `/usr/share/icons/elementary`. Log out, or reboot, to see changes.



