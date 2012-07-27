***
#Sublime Text 2 Package for Stata
***

Author: Ryan Powers [rpowers@wisc.edu](mailto:rpowers@wisc.edu)
Date: 27 July 2012
Keywords: Subime Text 2, Stata, Textmate Bundle, Port

##Summary
This is a port of the Textmate Bundle for Stata. It relies mostly on the old code, but adds a build system for use in Sublime Text. The original Textmate Bundle is available from [Dan Byler](http://bylr.net/3/2010/10/stata-bundle-for-textmate/). 

The package is currently for the OS X versions of Sublime Text 2 and Stata only. 

This package is very young. There may be errors and/or bugs. Please let me know if/when you find them. 

##Installation
Copy the "Stata" directory to your Sublime Text 2 packages directly. Normally located at ~/Library/Application Support/Sublime Text 2/Packages/.

Currently, the Package expects your installation of Stata to be named "Stata" -- not "StataSE", "StataMC", etc.

##Use
All stata .do files will get more or less correct code highlighting. Command+B will run your whole file in Stata. If you'd like to run only a section, select the code you'd like to run and the choose "Run" from the "Tools" menu. I'm working on a keyboard shortcut for this. At the moment, the Run command does not have a default keyboard shortcut on OS X.  