---
title: SmartArtNodeCollection
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/smartartnodecollection/
---
## SmartArtNodeCollection classe

 Représente une collection de nœuds SmartArt.
 
### addNode {#addNode}

| Name | Description |
| --- | --- |
| addNode () | Add new smart art node or sub node. |

 **Renvoie :**
[SmartArtNode](../smartartnode)


---


### addNodeByPosition {#addNodeByPosition}

| Name | Description |
| --- | --- |
| addNodeByPosition (int) | Add new node in the selected position of nodes collection |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| position | int | Position du nœud à base zéro |

 **Renvoie :**
[SmartArtNode](../smartartnode)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | position is less than 0 |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Renvoie :**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns node by index |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index à base zéro de l’élément |

 **Renvoie :**
[SmartArtNode](../smartartnode)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Renvoie :**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Renvoie :**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Renvoie :**



---


### removeNode {#removeNode}

| Name | Description |
| --- | --- |
| removeNode (int) | Remove node or sub node by index |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index à base zéro du nœud |

 **Renvoie :**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | index is less than 0. -or- index is equal to or greater than siblings count |


---


### removeNode {#removeNode}

| Name | Description |
| --- | --- |
| removeNode ([SmartArtNode](../smartartnode)) | Remove node or sub node |

 **Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| node | [SmartArtNode](../smartartnode) | Node to remove |

 **Renvoie :**
void


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns count of nodes in collection Read-only int Read-only int. |

 **Renvoie :**
int


---  