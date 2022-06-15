---
title: VbaProject
type: docs
weight: 0
url: /php-java/vbaproject/
---

# VbaProject class

 Represents VBA project with presentation macros.
 

## Constructors

| name | description |
| --- | --- |
| [VbaProject](/slides/php-java/vbaproject/vbaproject/)() | This constructor creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage |
| [VbaProject](/slides/php-java/vbaproject/vbaproject/)(byte[]) | This constructor loads VBA project from binary representation of OLE container. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getModules](/slides/php-java/vbaproject/getmodules/)() | IVbaModuleCollection | Returns the list of all modules that are contained in the VBA project. Read-only IVbaModuleCollection. |
| [getName](/slides/php-java/vbaproject/getname/)() | String | Returns the name of the VBA project. Read-only String. |
| [getReferences](/slides/php-java/vbaproject/getreferences/)() | IVbaReferenceCollection | Returns the list of all references that are contained in the VBA project. Read-only IVbaReferenceCollection. |
| [toBinary](/slides/php-java/vbaproject/tobinary/)() | byte | Returns the binary representation of the VBA project as OLE container |
