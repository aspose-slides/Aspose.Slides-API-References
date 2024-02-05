---
title: Row
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/row/
---

## Row class

 Represents a row in a table.
 
### copyTo {#copyTo}

| Name | Description |
| --- | --- |
| copyTo(Array, int) | Copies all elements from the collection to the specified array. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| array | Array | Target array. |
| index | int | Starting index in the target array. |


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight() | Returns the height of a row. Read-only double. |

 **Result:**
double


---


### getMinimalHeight {#getMinimalHeight}

| Name | Description |
| --- | --- |
| getMinimalHeight() | Returns or sets the minimal possible height of a row. Read/write double. |

 **Result:**
double


---


### getParent_Immediate {#getParent_Immediate}

| Name | Description |
| --- | --- |
| getParent_Immediate() |  |


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation() | Returns the parent presentation of a CellCollection. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRowFormat {#getRowFormat}

| Name | Description |
| --- | --- |
| getRowFormat() | Returns the RowFormat object that contains formatting properties for this row. Read-only IRowFormat. |

 **Result:**
[RowFormat](../rowformat)


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() | Returns the parent slide of a CellCollection. Read-only IBaseSlide. |

 **Result:**
[Slide](../slide), [MasterNotesSlide](../masternotesslide), [BaseSlide](../baseslide), [MasterSlide](../masterslide), [LayoutSlide](../layoutslide), [MasterHandoutSlide](../masterhandoutslide), [NotesSlide](../notesslide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot() | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item(int) | Returns a cell by it's position. Read-only Cell. One Cell object can be returned for several indexes in case cell is merged. |

 **Result:**
[Cell](../cell)


---


### isSynchronized {#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized() | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result:**
boolean


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator() | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava() | Returns a java iterator for the entire collection. |

 **Result:**



---


### setMinimalHeight {#setMinimalHeight}

| Name | Description |
| --- | --- |
| setMinimalHeight(double) | Returns or sets the minimal possible height of a row. Read/write double. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([PortionFormat](../portionformat)) | Sets defined portion format properties to all row cells' portions. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../portionformat) | IPortionFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([ParagraphFormat](../paragraphformat)) | Sets defined paragraph format properties to all row cells' paragraphs. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../paragraphformat) | IParagraphFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([TextFrameFormat](../textframeformat)) | Sets defined text frame format properties to all row cells' text frames. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../textframeformat) | ITextFrameFormat object with necessary properties set. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size() | Returns the number of cells in a collection. Read-only int. |

 **Result:**
int


---


