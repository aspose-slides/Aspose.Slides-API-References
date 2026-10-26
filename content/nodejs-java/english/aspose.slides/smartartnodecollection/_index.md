---
title: SmartArtNodeCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/smartartnodecollection/
---

## SmartArtNodeCollection class

 Represents a collection of SmartArt nodes.
 
### addNode {#addNode}

| Name | Description |
| --- | --- |
| addNode () | Add new smart art node or sub node. |

 **Returns:**
[SmartArtNode](../smartartnode)


---


### addNodeByPosition {#addNodeByPosition}

| Name | Description |
| --- | --- |
| addNodeByPosition (int) | Add new node in the selected position of nodes collection |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| position | int | Zero-base node position |

 **Returns:**
[SmartArtNode](../smartartnode)

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | position is less than 0 |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns node by index |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element |

 **Returns:**
[SmartArtNode](../smartartnode)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### removeNode {#removeNode}

| Name | Description |
| --- | --- |
| removeNode (int) | Remove node or sub node by index |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of node |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | index is less than 0. -or- index is equal to or greater than siblings count |


---


### removeNode {#removeNode}

| Name | Description |
| --- | --- |
| removeNode ([SmartArtNode](../smartartnode)) | Remove node or sub node |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| node | [SmartArtNode](../smartartnode) | Node to remove |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns count of nodes in collection Read-only int Read-only int. |

 **Returns:**
int


---


