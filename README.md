samr-utils
==========

Aka <https://github.com/rebelsky/samr-utils>

by Samuel A. Rebelsky

A variety of utilities and such that I've written over the years.
(Most are not here yet, but will show up eventually.)  Put into a
repository so that I can more easily move them from system to system
to system.

File Conversion
---------------

sw2md
  Convert Siteweaver files to Markdown.  (Siteweaver is my hybrid format
  for writing Web pages, with some features of Markdown and some features
  of XML.)

db2md
  Convert Docbook files to Markdown.

Tab Utilities
-------------

I like to put "tabs" (not in the \t sense, but in the sense of a label)
in between sections of code.  I therefore have a lot of silly utilities
for generating those tabs.

ctab some text
  Create one of the "comment tabs" which I use to organize C code.
  See also tab for the generic version.

jtab some text
  Create one of the "comment tabs" which I use to organize Java code.
  See also tab for the generic version.

ptab some text
  Create one of the "comment tabs" which I use to organize Perl code.
  See also tab for the generic version.

stab some text
  Create one of the "comment tabs" which I use to organize Scheme code.
  See also tab for the generic version.

tab comment-prefix some text
  Create one of the "comment tabs" which I use to organize code.  See
  also ctab, jtab, ptab, and stab.

Course Web Utilities
--------------------

ebi
  Make an index entry (in Docbook form) for links to an eboard.

ebr
  Make a related page entry (in markdown form) for links to an eboard.

Misc. Utilities
---------------

mem2svg
  A simple script for making SVG diagrams of simplified memory layouts, 
  helpful in making diagrams for my classes.  The input file format 
  is documented in the script.

ul
  Underline the first line of stdin, deleting the remaining text.
  (Used primarily within vi when I'm writing Markdown)

