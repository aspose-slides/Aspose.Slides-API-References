---
title: MasterSlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/masterslidecollection/
---

## MasterSlideCollection class

 Represents a collection of master slides.
 
| [addClone] ([MasterSlide]) Adds a copy of a specified master slide to the end of the collection. Linked layout slides will be copied too. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| sourceMaster | [MasterSlide] | Slide to clone. |

### Result
[MasterSlide]


---


| [getSyncRoot] () Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) Gets the element at the specified index. Read-only MasterSlide. |

### Result
[MasterSlide]


---


| [insertClone] ([int], [MasterSlide]) Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of new slide. |
| sourceMaster | [MasterSlide] | Slide to clone. |

### Result
[MasterSlide]


---


| [isSynchronized] () Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([MasterSlide]) Removes the first occurrence of a specific object from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| value | [MasterSlide] | The master slide to remove from the collection. |


---


| [removeAt] ([int]) Removes the element at the specified index of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index of the element to remove. To avoid throwing of the PptxEditException check master's HasDependingSlides property before. |

### Error

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if the master to remove is used in presentation (its HasDependingSlides property is true). |


---


| [removeUnused] ([boolean]) Removes unused master slides. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| ignorePreserveField | [boolean] | Determines, whether this function should remove unused master even if its ( MasterSlide#getPreserve/ MasterSlide#setPreserve(boolean)) property is set to true. |


---


| [size] () Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


