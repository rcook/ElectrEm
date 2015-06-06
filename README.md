# ElectrEm v0.7

ElectrEm is an open source emulator of the Acorn Electron microcomputer with three areas of focus:

* ease of use
* accuracy
* portability

## Ease of Use

ElectrEm should be usable by anybody who can use the OS ElectrEm is running on and the piece of Electron software they want to run. To that extent ElectrEm is able to automatically issue the correct commands to load most tape and disc software, and can automatically configure the emulated hardware to match inserted media.

## Accuracy

ElectrEm should be able to run Electron software in exactly the same way as a real Electron. To that end, ElectrEm employs an event based emulation that is a cycle perfect impersonation of the currently known operating parameters of the Electron.

## Portability

ElectrEm is written in C++ and makes use of the SDL library for most tasks. All code is cleanly laid out and mostly well commented. OS specific front ends have been written for Windows and Mac OS X. A GNOME or KDE port is part of the long term plan, but so far no effort has been extended in that direction.

## Announcements

ElectrEm announcements are usually made to the ElectrEm Yahoo! group — see http://games.groups.yahoo.com/group/electrem/ for more details. The main website for this emulator is http://electrem.acornelectron.co.uk/.

## Feedback

I invite feedback on this emulator, and can be contacted at thomas.harte@gmail.com.

## Changes

* Ver 0.7
  * brand new FX-80 emulation code; RTF and TXT output options are retained, a PNG output mode is added to provide the option of outputting graphics and a more accurate rendition of dot matrix fonts.
 

## Credits

All emulation code is by Thomas Harte. Platform specific GUI code is by Ewen Roberts and Thomas Harte.

CSW.dll (distributed with Windows version only) is by Fraser Ross.

FDI reading code is by Toni Wilen. All are provided 'as-is', without any express or implied warranty.

The Acorn ROMs are copyright PACE, and are distributed with their knowledge.

SDL is distributed under the terms of the GNU LGPL license:
	http://www.gnu.org/copyleft/lesser.html

Source for those libraries is available from the libraries page at the SDL website:
	http://www.libsdl.org/

zLib is (C) 1995-2002 Jean-loup Gailly and Mark Adler and is provided 'as-is', without any express or implied warranty.

'Transparent Electron' image and emulator name by Ian Marshall.

The following, listed in alphabetical order, have also aided the project in one way or another:

* gARetH baBB
* John Belson
* David Boddie
* Paul Boddie
* Ricky Grant
* R. Henderson
* Wouter Hobers
* Simon Irwin
* Marcel de Kogel
* Dave M
* David Raven
* Mark Shackman
* Partrick Shoenmakers
* Paul Walker
* John Wike
