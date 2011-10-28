Description
===========

This repository contains a bunch of stuff I use on my textmate installation.
Some of it is custom made by me, other parts are just adaptations of stuff I
found online and decided it would be a nice feature to add to textmate.

Go To Method Definition...
--------------------------

A small script to find a method definition inside a project. It's not specially
robust or fast, but it works well for most situations.

Some improvements can be made, such as:

* Context awareness to make sure it gets to the method on the right class
* Use Ack for faster search results
* Add support for multiple languages. Currently only the keyword function works
* Improve the regular expression
* Support for defining the extensions of files to look for

Remove Trailing Spaces in Document
----------------------------------

Removes trailling spaces from all lines on a document when saving it.
