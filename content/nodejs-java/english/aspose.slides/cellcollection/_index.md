---
title: CellCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/cellcollection/
---

## CellCollection class

 Represents a collection of cells.
 
### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a CellCollection. Read-only IPresentation. |

 **Returns:**
[Presentation](../presentation)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a CellCollection. Read-only IBaseSlide. |

 **Returns:**
[BaseSlide](../baseslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [MasterNotesSlide](../masternotesslide), [MasterSlide](../masterslide), [NotesSlide](../notesslide), [Slide](../slide)


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
| get_Item (int) | Returns a cell by it's position. Read-only Cell. One Cell object can be returned for several indexes in case cell is merged. |

 **Returns:**
[Cell](../cell)


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


### size {#size}

| Name | Description |
| --- | --- |
| size () | Returns the number of cells in a collection. Read-only int. |

 **Returns:**
int


---


