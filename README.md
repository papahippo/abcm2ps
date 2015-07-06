abcm2ps version 8.x.x
=====================

Overview
--------
abcm2ps is a program which converts music tunes from ABC format to
PostScript or SVG. Based on abc2ps version 1.2.5 (see [Contacts](/contacts/) below),
it was developped mainly to print barock organ scores which have
independant voices played on one or many keyboards and a pedal-board
(the '`m`' of abcm2ps stands for many or multi staves/voices).

Features
--------
The main features of abcm2ps are quite the same as the abc2ps ones,
but they are closer to the ABC standard 2.0 (draft IV - 14/8/2003):

<http://abc.sourceforge.net/standard/abc2-draft.html>

Installation and usage
----------------------
The installation procedure is described in the file `INSTALL`.

Basically, the program usage is:
    abcm2ps [options] file1 [file1_options] file2 [file2_options] ...
where file1, file2, .. are the ABC input files. This will generate
a Postscript file (default name: '`Out.ps`' - run '`abcm2ps -h`' to
know the list of the command line options).

Documentation
-------------
- `options.txt` contains the list of the command line options.
- the format parameters are described in:
	<http://moinejf.free.fr/abcm2ps-doc/index.html>
- the differences from the current ABC standard are described in:
	<http://moinejf.free.fr/abcm2ps-doc/index.html>

Limits
------

Many limits may be changed at compilation time (number of voices,
staves, ..).

Contacts
--------
The primary abcm2ps site is:
<http://moinejf.free.fr/>

Guido Gonzatto maintains Win32 and RedHat binaries and some more
documentation at:
<http://abcplus.sourceforge.net/>

abc2ps was developped by Michael Methfessel:
    <http://www.ihp-ffo.de/~msm/>
    msm (at) ihp-ffo (dot) de

To know more about the ABC notation, have a look at:
    <http://abcnotation.com/>

For any comment: moinejf (at) free (dot) fr
