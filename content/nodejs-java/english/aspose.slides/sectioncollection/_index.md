---
title: SectionCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/sectioncollection/
---

## SectionCollection class

 Represents a collection of sections.
 

## Functions

| Name | Description |
| --- | --- |
| [addEmptySection](String, int) | Add empty section to specified position of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |
| index | int | Index of new section. |

### Result
[Section](../../section)


---


| [addSection](String, [Slide](../slide)) | Add slides section started form specific slide. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |
| startedFromSlide | [Slide](../../slide) | First slide of section |

### Result
[Section](../../section)


---


| [appendEmptySection](String) | Add empty section to the end of the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |

### Result
[Section](../../section)


---


| [clear]() | Removes all sections from the collection. |


---


| [getSyncRoot]() | Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item](int) | Gets the element at the specified index. Read-only ISection. |

### Result
[Section](../../section)


---


| [indexOf]([Section](../section)) | Returns an index of the specified section in the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | Section to find. |

### Result
int


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


| [removeSection]([Section](../section)) | Remove section. Slides contained in the section will be merged into previous section. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | The section to remove from the collection. |


---


| [removeSectionWithSlides]([Section](../section)) | Remove section and slides contained in the section. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../../section) | The section to remove from the collection. |


---


| [reorderSectionWithSlides]([Section](../section), int) | Moves section and its slides from the collection to the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [Section](../section) | Target index. |
| section | int | Section to move. |


---


| [size]() | Gets the number of elements actually contained in the collection. Read-only int. |

### Result
int


---


