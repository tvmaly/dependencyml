# dependencyml
document non-code dependencies for impact analysis and data lineage 

# Introduction
In many programming languages, there is a facility
to track code dependencies. Python has various
ways such as requirements.txt. Go has the go.mod 
files.

But there is not a I could find to track that
software depends on a file, API, a service, a server,
or a database.

This information is useful if you need to 
change something, especially in a large 
organization. Documentation is always a 
struggle. You may not know all of the 
stakeholders or which programs depend on
services or servers.

Imagine someone upgrading a 
database of changing a critical table in
production. They may not have considered 
all the programs using the database. Some 
of the stakeholders may have been on vacation 
or might have left the organization all
together.

Solving this documentation gap with a human readable
markup language that can easily be queried is
the goal of this project.

# Terminology

* is a

* has a 

* depends on

* runs on

* interoperates with

* implemented in

* provides
