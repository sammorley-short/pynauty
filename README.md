# Pynauty
*by Sam Morley-Short*

This is a fork of `pynauty`--a Python extension of the C module `nauty`--to add extra features needed for exploring LC classes of quantum graph states.

It was made entirely for use by my other Graph State Compass (gsc) module, which can be found [here](https://github.com/sammorley-short/gsc).

It is redistributed under the GPL v3 copyleft lisence WITHOUT ANY WARRANTY.

To install, follow the instructions provided [here](https://web.cs.dal.ca/~peter/software/pynauty/html/install.html).

Loosely, this requires:

1. Downloading nauty, (working as of version 27b11, found [here](http://users.cecs.anu.edu.au/~bdm/nauty/nauty27b11.tar.gz)),
2. Unzipping it and placing it in `/pynauty-hack`,
3. Symbolic link the nauty directory to `/nauty` (for the above case on Mac OS X this means running `ln -s nauty27b11 nauty` from the command line),
4. Installing pynauty (`make user-ins` can be used to install globally).

## Original warranty

pynauty  --  isomorphism testing and automorphism groups of graphs
version: 0.6

Copyright (c) 2015 Peter Dobsan

This is the source distribution of pynauty, a Python/C extension module.
It can be used to compare graphs for isomorphism and to determine their
automorphism group. It is based on the Nauty C procedures.

pynauty is compatible both Python-2 and Python-3.

pynauty is distributed under the terms GPL v3 WITHOUT ANY WARRANTY.
For exact details on licencing see the file COPYING.

For documentations, including instructions for  installation, API and
User's Guide see the docs/ directory.

