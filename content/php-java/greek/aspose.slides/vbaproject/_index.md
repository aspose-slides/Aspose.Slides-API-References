---
title: VbaProject
second_title: Aspose.Sildes για PHP μέσω Java API Αναφορά
description: 
type: docs

url: /el/aspose.slides/vbaproject/
---
## VbaProject κλάση

 Represents VBA project with presentation macros.
 
### VbaProject {#VbaProject}

| Όνομα | Περιγραφή |
| --- | --- |
| VbaProject() | This function creates new VBA project from scratch. Project will be created in 1252 Windows Latin 1 (ANSI) codepage |

 **Επιστρέφει:**
VbaProject


---


### VbaProject {#VbaProject}

| Όνομα | Περιγραφή |
| --- | --- |
| VbaProject(byte[]) | This function loads VBA project from binary representation of OLE container. |

 **Επιστρέφει:**
VbaProject


---


### getModules {#getModules}

| Όνομα | Περιγραφή |
| --- | --- |
| getModules () | Returns the list of all modules that are contained in the VBA project. Read-only IVbaModuleCollection. |

 **Επιστρέφει:**
[VbaModuleCollection](../vbamodulecollection)


---


### getName {#getName}

| Όνομα | Περιγραφή |
| --- | --- |
| getName () | Returns the name of the VBA project. Read-only String. |

 **Επιστρέφει:**
String


---


### getReferences {#getReferences}

| Όνομα | Περιγραφή |
| --- | --- |
| getReferences () | Returns the list of all references that are contained in the VBA project. Read-only IVbaReferenceCollection. |

 **Επιστρέφει:**
[VbaReferenceCollection](../vbareferencecollection)


---


### isPasswordProtected {#isPasswordProtected}

| Όνομα | Περιγραφή |
| --- | --- |
| isPasswordProtected () | Indicates whether the VBAProject is protected by a password to view project properties. Read-only boolean. |

 **Επιστρέφει:**
boolean


---


### toBinary {#toBinary}

| Όνομα | Περιγραφή |
| --- | --- |
| toBinary () | Returns the binary representation of the VBA project as OLE container |

 **Επιστρέφει:**
byte


---