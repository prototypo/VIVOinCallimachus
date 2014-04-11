VIVO in Callimachus
===================

## Overview

This repository contains a partial implementation of the VIVO ontology (see http://www.essepuntato.it/lode/owlapi/http://vivoweb.org/ontology/core) in Callimachus (see http://callimachusproject.org).

The Callimachus Project is a Web-based application development environment based on the principles of Linked Data.  Callimachus allows the rapid development of applications that serialize data to the RDF data model.  One aspect of Callimachus that suggests the implementation of the VIVO ontology is the ability to associate templates with OWL classes, enabling instances of those class to be created, edited or viewed via HTML pages.

We began by creating two OWL classes in Callimachus representing what are arguably the two key classes from the VIVO ontology, Person and Article, and creating Callimachus templates in HTML for the creation, editing and viewing of instances.  We ensured that these instances were simultaneously instances of the VIVO classes.

Callimachus provides a mechanism for the association of OWL class instances with SKOS Concepts, which allows a more simple association of roles with instances of the class Person, such as Faculty Member or Student.  There are some trade-offs in the simplification of the modeling in relation to the VIVO ontology but both approaches may be implemented simultaneously.

## Usage

* Access a running Callimachus instance
* Create a new folder
* Import the Callimachus ARchive (CAR) file into the folder

## Contributing

Developers should be familiar with Callimachus and developing Callimachus applications.  Please see http://callimachusproject.org for assistance and documentation.  New developers may wish to discuss their plans on irc.freenode.net in the channel #callimachus.

Development may occur within Callimachus or directly in the Git repository, but files must eventually be committed to a clone of this repository and a pull request issued.

Thank you for any contributions!

## License

Copyright © 2013 3 Round Stones, Inc.

Distributed under the Apache License, Version 2.0, the same as Callimachus.


