# ClassDefinition
project to define class structure, a centralized place to record all class definition, and become a tool to quick start a project
draggable control to define properties of an object, define it's initial sequence.
allow one defined class reused in multiple projects.
# Tech structure
tool: visual studio code/ mysql
project type: dotnet web api/ vue init new
# table structurs
this section to have a draft design view of this project. model based view of the project
## Project
### projectName
name and field descirption
### projectClassList
mapping of the project and different classes
## class
this is type of main table to defin what the class will be 
### classtype
define different class types, to define as dummy class/ real class/ class list
when deifine classdef, use this class to identify the type
### classdef
this class main information
define parent class, inherit option: yes or no.
use tree view to navigate all the classes. and see the inheried class relationship.
### classProperties
list of the class properties, include the intial sequence for properties.
the properties include inherited property and own property, need to find a good way to define all the property 
