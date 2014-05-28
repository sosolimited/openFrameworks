[openFrameworks](http://openframeworks.cc/)
================

openFrameworks is a C++ toolkit for creative coding.  If you are new to OF, welcome!


folder structure
--------

This release of OF comes with several folders: 

* addons
* apps
* docs
* examples
* export (on some systems)
* libs
* other
* scripts
* project generator


`docs` has some documentation around OF usage, per platform things to consider, etc. You should definitely take a look in there, for example, if you are on OSX, read the osx.md.   `apps` and `examples` are where projects go -- `examples` contains a variety of projects that show you how to use OF, and `apps` is where your own projects will go.  `libs` contains the libraries that OF uses, including the openframeworks core itself.  `addons` are for additional functionality that's not part of the core.  `export` is for DLLs and dylibs that need to be put in each compiled project.  The `scripts` folder has the templates and small scripts for automating OF per platform. `project generator` is a GUI based tool for making new projects - this folder is only there in packaged releases.  

One  idea that's important is that OF releases are designed to be self-contained.  You can put them anywhere on your hard drive, but it's not possible to mix different releases of OF together, so please keep each release (0.8.0, 0.8.1) separate.  Projects may generally work from release to release, but this is not guaranteed.   Because OF is self-contained, there's extensive use of local file paths (ie, ../../../) thoughout OF.  It's important to be aware of how directories are structured.  A common error is to take a project and move it so that it's a level below or above where it used to be compared to the root of OF.  This means that links such as ../../../libs will break.  


Get involved
--------

The openframeworks forum:

[http://forum.openframeworks.cc/]()

is a warm and friendly place  Please ask or answer a question.  The most important part of this project is that it's a community, more than just a tool, so please join us!  Also, this is free software, and we learn so much about what is hard, what doesn't make sense, what is useful, etc. The most basic questions are acceptable here!  Don't worry, just join the conversation.  Learning in OF is social, it's hard to do it alone, but together we can get far!

Our github site is active: 

[https://github.com/openframeworks/openFrameworks]()

if you have bugs or feature requests, consider opening an issue.  If you are a developer and want to help, pull requests are warmly welcome.  Please read the contributing guide for guidelines: 

https://github.com/openframeworks/openFrameworks/blob/master/CONTRIBUTING.md

We also have a developer's mailing list, which is useful for discussing issues around the development and future of OF. 


Developers
------

This repository stores versions of openFrameworks customized for Sosolimited projects. Development is primarily for OSX, so unlike the offical OFX releases, any enhancements are not guaraanteed to be cross-platform.

Versioning
----------
openFrameworks uses [Semantic Versioning](http://semver.org/), although strict adherence will only come into effect at version 1.0.0.

