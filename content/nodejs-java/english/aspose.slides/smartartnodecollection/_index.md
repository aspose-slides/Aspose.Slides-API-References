---
title: SmartArtNodeCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/smartartnodecollection/
---

## SmartArtNodeCollection class

 Represents a collection of SmartArt nodes.
 

## Functions

| Name | Description |
| --- | --- |
| [addNode]() | Add new smart art node or sub node. |

### Result
[SmartArtNode](../../smartartnode)


---


| [addNodeByPosition](int) | Add new node in the selected position of nodes collection |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| position | int | Zero-base node position |

### Result
[SmartArtNode](../../smartartnode)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | position is less than 0 |


---


| [getSyncRoot]() | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item](int) | Returns node by index |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index of the element |

### Result
[SmartArtNode](../../smartartnode)


---


| [isSynchronized]() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator]() | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava]() | Returns a java iterator for the entire collection. |

### Result



---


| [removeNode](int) | Remove node or sub node by index |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Zero-based index of node |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | index is less than 0. -or- index is equal to or greater than siblings count |


---


| [removeNode]([SmartArtNode](../smartartnode)) | Remove node or sub node |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| node | [SmartArtNode](../../smartartnode) | Node to remove |


---


| [size]() | Returns count of nodes in collection Read-only int Read-only int. |

### Result
int


---


