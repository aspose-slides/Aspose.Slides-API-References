---
title: VbaProject
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/vbaproject/
---

## VbaProject class

 Represents VBA project with presentation macros.
 
| Name | Description |
| --- | --- |
| VbaProject() | This function creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage |

### Result
VbaProject


---


| Name | Description |
| --- | --- |
| VbaProject(byte[]) | This function loads VBA project from binary representation of OLE container. |

### Result
VbaProject


---


| Name | Description |
| --- | --- |
| getModules () | Returns the list of all modules that are contained in the VBA project. Read-only IVbaModuleCollection. |

### Result
VbaModuleCollection(../../vbamodulecollection)


---


| Name | Description |
| --- | --- |
| getName () | Returns the name of the VBA project. Read-only String. |

### Result
String


---


| Name | Description |
| --- | --- |
| getReferences () | Returns the list of all references that are contained in the VBA project. Read-only IVbaReferenceCollection. |

### Result
VbaReferenceCollection(../../vbareferencecollection)


---


| Name | Description |
| --- | --- |
| toBinary () | Returns the binary representation of the VBA project as OLE container |

### Result
byte


---


