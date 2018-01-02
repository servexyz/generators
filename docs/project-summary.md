# Project Summary

> Brainstormed all generators and their proper order of implementation

![](./images/project-summary/Screen%20Shot%202018-01-01%20at%2011.17.42%20AM.png)

## Summary

* Files
  * Libraries
  * UI Paradigm
  * Views
  * Features \* Applications

### Generator-Generators

> Generate any system files which make it possible for other generators to work

* Factory
  * **Directory**
  * **File**
  * **Symlink**
  * **Content**
  * Parsers
    * RegEx
    * JSON
    * AST

### Library-Generators

> Generate anything which helps apps work.

* Factory
  * **NPM Library**
    * eg. _Utility_
    * eg. \*UI Library\*
    * eg. \*Microservice\*

### Wrigley-Generators

* Factory
  * Asimov
    * **component-generator**
    * Wilhelm
      * **style-generator**
      * Galton
        * **style-bridge**

### View-Generators

> Generate part of a big app or whole of a small app

* Factory
  * CLI
  * GUI

![](./images/project-summary/Screen%20Shot%202018-01-01%20at%2011.36.23%20AM.png)
