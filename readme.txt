These diskettes contain a public domain Prolog interpreter
called Small Prolog version 2.
In the USA the C User's Journal will have the latest releases.

It has been compiled on an PC clone, on UNIX  and on an Atari ST.


The files concerned are:
Disk 1 (Sources)
pp.c - simple pretty printer (compile apart).
pralloc.c -allocate structures
prassert.c - asserta etc... builtins
pratari.c - Atari specific code
pratari.mak - Atari makefile for Mark Williams C.
prbltin.c - most builtins
prbltin.h -include file for prbltin.c
prcnsult.c - code for consult builtin
prdebug.c - functions you might use for debugging
prerror.c - error message functions
prhash.c - build sybol table
prlex.h - used bu prparse.c and prscan.c
prlush.c - lush resolution algorithm
prlush.h - include file for prlush.c
prmain.c - starting point
prolog.h - configuation switches
prparse.c - parser
prprint.c -printer
prscan.c - lexical analysis
prsun.c - unix specific code that worked on a Sun workstation.
prtypes.h -type definitions
prunify.c - recursive unification algorithm, dereferencing 
makefile.tbc - makefile for Turbo C
quickc.mak -makefile for Quick C
zortech.mak -makefile for Zortech C
old_prj.tbc - an old style Turbo C project file
makefile : one of the makefiles
makefile.unx : a makefile for Sun OS 
pratari.mak - a makefile for mark williams C on Atari.
*.lnk - various link response files
 
Disk 2 (Docs & executables)
---------------------------

prmanual.txt - sort of manual
frmanual.txt - out of date French translation of prmanual.txt
sprolog.exe - compiled for MS DOS
sprolog.32e - a 32bit version for a 386 machine (gcc-386 used)
sprolog.inf - configuration file to override default memory consumption
sprolog.ini - file of useful predicates loaded when starting up
go32.exe - a Dos extender needed to run sprolog.32e
pp.exe - a simple Small Prolog pretty-printer

verif.spr - helps you find bugs in sprolog programs
xread.spr - lets you read a list while retaining the variable names.
help.spr - load this and type (help)
exampl*.spr - example files that give you a taste of prolog.
changes.91 - summary of recent changes
