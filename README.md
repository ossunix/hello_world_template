Simple C program template
===============================

This is a little template for compiling C programs, that I use
to save me some pain on being beginner C developer. So if you are a beginner and if no one else can help, and if you can download it, maybe you can use it.

##### Whats inside ?

- Simple directory structure that you can use organize your stuff.
- MIT licence, which you can remove or replace.
- Sample files for README, INSTALL, VERSION.
- Sample program.
- A Makefile made to work on this directory structure.

By default Makefile includes some libraries like glib, libcurl etc. 
These were necessary for me and if you need you can uncomment them or 
add your own. These are just to get you started.


##### What are the directories for ?

Directory   |   What for ?
-------     |   --------
doc  	      |   Here be the docs.
include     |   Here be the header(.h) files.
src 	      |   Here be the source(.c) files.
src/obj     |   Here the compiler puts object files.
lib         |   Here be the local libraries.
data        |   Here be some data for your program. 	 


##### References:
A lot of good stuff was learned from these websites:

* A Simple Makefile Tutorial
http://www.cs.colby.edu/maxwell/courses/tutorials/maketutor/
* Makefile tutorial
http://makefiletutorial.com/
