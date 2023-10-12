---
title: LayoutSlideCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/layoutslidecollection/
---

## LayoutSlideCollection class

 Represents a base class for collection of a layout slides.
 
### getByType {#getByType}

| Name | Description |
| --- | --- |
| getByType (byte) | Returns the first layout slide of specified type. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| type | byte | A type of layout slide to find. |

 **Result**
[LayoutSlide](../layoutslide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns the layout slide by index. Read-only LayoutSlide. |

 **Result**
[LayoutSlide](../layoutslide)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([LayoutSlide](../layoutslide)) | Removes a layout from the collection. |

 **Parameters**

| Name | Type | Description |
| --- | --- | --- |
| value | [LayoutSlide](../layoutslide) | The layout slide to remove from the collection. 1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also ILayoutSlide#remove function to simplify code. |

 **Error**

| Error | Condition |
| --- | --- |
 | PptxEditException | Thrown if layout is used in presentation (its HasDependingSlides property is true). |


---


### removeUnused {#removeUnused}

| Name | Description |
| --- | --- |
| removeUnused () | Removes unused layout slides (layout slides whose HasDependingSlides is false). |


---


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns the number of layout slides in a collection. Read-only int. |

 **Result**
int


---


