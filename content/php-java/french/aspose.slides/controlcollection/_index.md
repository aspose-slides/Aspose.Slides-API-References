---
title: ControlCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/controlcollection/
---
## ControlCollection classe

 Une collection de contrôles ActiveX.
 
### addControl {#addControl}

| Name | Description |
| --- | --- |
| addControl (int, float, float, float, float) | Crée et ajoute un nouveau contrôle à la collection. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| controlType | int | Type d'un contrôle à ajouter. |
| x | float | La coordonnée X du côté gauche du cadre du forme. |
| y | float | La coordonnée Y du côté supérieur du cadre du forme. |
| width | float | La largeur du cadre du forme. |
| height | float | La hauteur du cadre du forme. |

 **Retour:**
[Control](../control)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Supprime tous les contrôles de la collection. |

 **Retour:**
void


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Renvoie une racine de synchronisation. Objet en lecture seule. |

 **Retour:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Renvoie un contrôle à la position spécifiée. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index d'un contrôle. |

 **Retour:**
[Control](../control)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Renvoie une valeur indiquant si l'accès à la collection est synchronisé (thread-safe). boolean en lecture seule. |

 **Retour:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Renvoie un énumérateur qui parcourt la collection. |

 **Retour:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Renvoie un itérateur java pour l'ensemble de la collection. |

 **Retour:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([Control](../control)) | Supprime un contrôle ActiveX de la collection. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| item | [Control](../control) | Un contrôle à supprimer. |

 **Retour:**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Supprime un contrôle ActiveX stocké à la position spécifiée de la collection. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index d'un contrôle à supprimer. |

 **Retour:**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Renvoie le nombre d'objets dans la collection. int en lecture seule. |

 **Retour:**
int


---