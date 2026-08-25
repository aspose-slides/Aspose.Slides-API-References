---
title: VbaProject
second_title: Aspose.Sildes pour PHP via la référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/vbaproject/
---
## classe VbaProject

 Représente le projet VBA avec des macros de présentation.
 
### VbaProject {#VbaProject}

| Nom | Description |
| --- | --- |
| VbaProject() | Cette fonction crée un nouveau projet VBA à partir de zéro. Le projet sera créé dans la page de code 1252 Windows Latin 1 (ANSI) |

 **Renvoie:**  
VbaProject


---


### VbaProject {#VbaProject}

| Nom | Description |
| --- | --- |
| VbaProject(byte[]) | Cette fonction charge un projet VBA à partir de la représentation binaire d'un conteneur OLE. |

 **Renvoie:**  
VbaProject


---


### getModules {#getModules}

| Nom | Description |
| --- | --- |
| getModules () | Renvoie la liste de tous les modules contenus dans le projet VBA. Lecture seule IVbaModuleCollection. |

 **Renvoie:**  
[VbaModuleCollection](../vbamodulecollection)


---


### getName {#getName}

| Nom | Description |
| --- | --- |
| getName () | Renvoie le nom du projet VBA. Lecture seule String. |

 **Renvoie:**  
String


---


### getReferences {#getReferences}

| Nom | Description |
| --- | --- |
| getReferences () | Renvoie la liste de toutes les références contenues dans le projet VBA. Lecture seule IVbaReferenceCollection. |

 **Renvoie:**  
[VbaReferenceCollection](../vbareferencecollection)


---


### isPasswordProtected {#isPasswordProtected}

| Nom | Description |
| --- | --- |
| isPasswordProtected () | Indique si le VBAProject est protégé par un mot de passe pour afficher les propriétés du projet. Lecture seule boolean. |

 **Renvoie:**  
boolean


---


### toBinary {#toBinary}

| Nom | Description |
| --- | --- |
| toBinary () | Renvoie la représentation binaire du projet VBA sous forme de conteneur OLE |

 **Renvoie:**  
byte


---