git-info
=======

A bash script that traverses the sub-directories
from the directory where it is invoked. It any of those
sub-directories are git repos and have modified files,
it will return the directory name, git branch name, 
and the list modified files.

Passing the -b or --branch option will cause the script
to print the current branch of any repos it finds, regardless
of if modified files are found. If modified files are found,
it will also print the list of modified files.

Installation
=======

Place in your path and make executable.
Run by simply typing git-info or git info

Usage
=======

Usage: git-info [OPTION]
Show branches and modified files in git repos with modified files
  
-b, --branch  Show branches even of repos without modified files
-h, --help    Show this help dialogue
 
License
=======

Licensed under the MIT license (see LICENSE.txt)
