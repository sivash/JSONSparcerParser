JSONSparserParser
=================
README
This is the readme for Version .1 of The JSONSparserParser

Version Notes
----------
.01 -> Initial release of The JSONSparserParser Library

Purpose
----------
SparserParser is a JSON Parser/Unparser library. It's primary capabilities are too
turn a Java Object into a string of JSON, or take a string of JSON and
turn it into a Java Object.

Features
----------
Ignores incorrectly formatted whitespace
Accepts unicode
Can input JSON from file
Can take multiple lines of JSON at once, from file or strings.

Download
----------
The current version of JSONSparserParser can be accessed from
 https://github.com/sivash/JSONSparcerParser

Documentation
----------
JavaDoc documentation for each menthod can be found within the library's .java files

How to Use
----------
Import the JSONSparserParser library to gain access to its methods.
To parse a string of JSON into a java object, use parse(String str)
To parse a Java Object into a string of JSON, use toJsonString (Object obj)
To parse JSON from a file, use parseFile (String Filename)
To access the interactive object builder, run the iParserTest file.
For additional information check in-file documentation.

Developement
----------
The SparserParser was developed by Phineas Schlossberg and Ashwin
Sivaramakrishnan.
The JSONSparserParser is protected under the GPL v2 License

Contact
----------
The developers can be contacted for further information or bug reporting at 
schlossb@grinnell.edu or sivarama@grinnell.edu
