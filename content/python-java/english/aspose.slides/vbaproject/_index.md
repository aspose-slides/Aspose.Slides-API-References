---
title: VbaProject
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/vbaproject/
---

## VbaProject class

 Represents VBA project with presentation macros.
 
### VbaProject {#VbaProject}

| Name | Description |
| --- | --- |
| VbaProject() | This constructor creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage |

 **Returns:**
VbaProject


---


### VbaProject {#VbaProject}

| Name | Description |
| --- | --- |
| VbaProject(byte[]) | This constructor loads VBA project from binary representation of OLE container. |

 **Returns:**
VbaProject


---


### getModules {#getModules}

| Name | Description |
| --- | --- |
| getModules() | Returns the list of all modules that are contained in the VBA project. Read-only IVbaModuleCollection. |

 **Returns:**
[VbaModuleCollection](../vbamodulecollection)


---


### getName {#getName}

| Name | Description |
| --- | --- |
| getName() | Returns the name of the VBA project. Read-only String. |

 **Returns:**
String


---


### getReferences {#getReferences}

| Name | Description |
| --- | --- |
| getReferences() | Returns the list of all references that are contained in the VBA project. Read-only IVbaReferenceCollection. |

 **Returns:**
[VbaReferenceCollection](../vbareferencecollection)


---


### isPasswordProtected {#isPasswordProtected}

| Name | Description |
| --- | --- |
| isPasswordProtected() | Indicates whether the VBAProject is protected by a password to view project properties. Read-only boolean. |

 **Returns:**
boolean


---


### toBinary {#toBinary}

| Name | Description |
| --- | --- |
| toBinary() | Returns the binary representation of the VBA project as OLE container |

 **Returns:**
byte


---


