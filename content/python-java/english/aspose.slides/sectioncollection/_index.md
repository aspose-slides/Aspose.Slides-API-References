---
title: SectionCollection
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/sectioncollection/
---

## SectionCollection class

 Represents a collection of sections.
 
### addEmptySection {#addEmptySection}

| Name | Description |
| --- | --- |
| addEmptySection(String, int) | Add empty section to specified position of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |
| index | int | Index of new section. |

 **Returns:**
[Section](../section)


---


### addSection {#addSection}

| Name | Description |
| --- | --- |
| addSection(String, [Slide](../slide)) | Add slides section started form specific slide. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |
| startedFromSlide | [Slide](../slide) | First slide of section |

 **Returns:**
[Section](../section)


---


### appendEmptySection {#appendEmptySection}

| Name | Description |
| --- | --- |
| appendEmptySection(String) | Add empty section to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| name | String | Name of the section |

 **Returns:**
[Section](../section)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear() | Removes all sections from the collection. |


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot() | Returns a synchronization root. Read-only Object. |

 **Returns:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item(int) | Gets the element at the specified index. Read-only ISection. |

 **Returns:**
[Section](../section)


---


### indexOf {#indexOf}

| Name | Description |
| --- | --- |
| indexOf([Section](../section)) | Returns an index of the specified section in the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | Section to find. |

 **Returns:**
int


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Returns:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator() | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava() | Returns a java iterator for the entire collection. |

 **Returns:**



---


### removeSection {#removeSection}

| Name | Description |
| --- | --- |
| removeSection([Section](../section)) | Remove section. Slides contained in the section will be merged into previous section. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | The section to remove from the collection. |


---


### removeSectionWithSlides {#removeSectionWithSlides}

| Name | Description |
| --- | --- |
| removeSectionWithSlides([Section](../section)) | Remove section and slides contained in the section. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| section | [Section](../section) | The section to remove from the collection. |


---


### reorderSectionWithSlides {#reorderSectionWithSlides}

| Name | Description |
| --- | --- |
| reorderSectionWithSlides([Section](../section), int) | Moves section and its slides from the collection to the specified position. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | [Section](../section) | Target index. |
| section | int | Section to move. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size() | Gets the number of elements actually contained in the collection. Read-only int. |

 **Returns:**
int


---


