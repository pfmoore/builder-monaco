This Project
============

This project automates the process of building the Monaco program. Monaco's
README file is included below.

Monaco ReadMe File
==================

This program, known as "Monaco", allows you to produce answers to some problems
that involve random effects, such as are produced by dice or cards. These will
typically be problems of forms such as "How likely is this?", "What is the
average value of that?", or "What is the distribution of that?".

The program should be supplied as either of both of:

- One or more executable files, each for a particular operating system. They
  might have names like monaco, monaco.exe and/or monaco.command. In some cases
  there might also be versions with names like monaco128 etc.

- C++ source code files, with .h and .cpp extensions, that you can compile to
  produce such an executable file, which it us assumed that you know how to do.
  The program was and is designed to run as C++98, for which you typically use
  a compiler flag such as -std=c++98. It should compile using some later
  versions of C++, but possibly with warnings, and from C++17 possibly with
  errors. There are also preprocessor symbols that can be defined to modify the
  integer size used, but on most systems the default should serve for most
  purposes. I usually compile with optimisation level -O3. See Appendix A of the
  main document described below for further details. There are currently 289
  source code files (103 with a .h extension, 186 with a .cpp extension).

In addition to this file the following documentation should have been provided:

- A PowerPoint presentation "Monaco Introduction.ppt", which as its name
  suggests is a basic introduction to what the program is. In case you do not
  use PowerPoint then there should also be a PDF version of this presentation.

- Three further PDF files that are documents rather than presentations. (Their
  original versions, which are not provided, are in Word.) These are:

  + "Monaco Tutorial.pdf". A tutorial that introduces some of the main features
    of the program to get you started.

  + "Monaco Documentation.pdf". The main documentation file. This provides a
    mixture of introductory, tutorial and reference material. It is a long
    document, but about three quarters of it is appendices, most of which you
    will not need except for occasional reference.

  + "Monaco Teaser.pdf". This presents some examples that the program can
    handle, all taken from the main documentation file. But in each case it
    provides only a statement of the problem and some output from which the
    solution can be determined. (The program parameters used are provided,
    unexplained, as a final note at the end of the file.) As the file name
    suggests, the aim is to indicate why this program might be useful and worth
    considering further.

Finally, there is also a text document changes.txt that summarises the main
changes in the program from version to version. Unless you are a regular user of
the program, you can ignore this file.


Final Note
----------

The program Monaco (current version 1.47) and all associated documentation,
including this file and the other documentation files listed above, are
copyright Christopher Dearlove, christopher.dearlove@gmail.com, 2008-2021, all
rights reserved.
