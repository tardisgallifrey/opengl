<h2>My work on OpenGL in C</h2>

This is a repository of Linux based OpenGL written in C.  If OpenGL is properly set up, these applications will compile with gcc.

If you wish to install OpenGL on an Ubuntu equivalent distribution, visit this web site.  

https://www.wikihow.com/Install-Mesa-%28OpenGL%29-on-Linux-Mint

The file old_GLcompile is a bash file that I built to compile OpenGL apps.  It will allow four additional libraries to be added 
to the command line in addition to the ones needed for OpenGL compilation.  It has the prefix "old_" on my repo because I have GLcompile 
symlinked from my home /bin folder so that it works universally.  The bash file uses very simple notation, so it will move the a.out executive 
produced by the compiler to a correctly named executable app file.

You use it like this, assuming you've installed the real bash file to your home /bin and then symlinked it to /bin.

GLcompile myglfile

Where, myglfile is your C file with the name myglfile.c and it is in the current directory.  

As OpenGL and freeglut (the glut replacement) are very primitive, everything you want to use has to be written.  writetext.c is my current work to begin 
to write a character placing and input/output set of functions for my freeglut and OpenGL system.

I have and will attempt to give credit to locations and such where I've drawn examples from to learn OpenGL.  Most will be in line as C comments.

However, one that I used quite a bit and some of the examples are theirs came from:

https://www2.cs.arizona.edu/classes/cs433/spring02/opengl/

This is not a tutorial. None of this contains any kind of warranty for purpose or intent.  Use at your own risk.



