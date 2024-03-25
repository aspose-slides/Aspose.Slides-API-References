---
title: Column
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/column/
---

## Column class

 Represents a column in a table.
 
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


### getColumnFormat {#getColumnFormat}

| Name | Description |
| --- | --- |
| getColumnFormat() | Returns the ColumnFormat object that contains formatting properties for this column. Read-only IColumnFormat. |

 **Result:**
[ColumnFormat](../columnformat)


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


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide() | Returns the parent slide of a CellCollection. Read-only IBaseSlide. |

 **Result:**
[MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [BaseSlide](../baseslide), [NotesSlide](../notesslide), [Slide](../slide), [MasterHandoutSlide](../masterhandoutslide), [MasterSlide](../masterslide)


---


### getSyncRoot {#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot() | Returns a synchronization root. Read-only Object. |

 **Result:**
Object


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth() | Returns or sets the width of a column. Read/write double. |

 **Result:**
double


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


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([PortionFormat](../portionformat)) | Sets defined portion format properties to all column cells' portions. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../portionformat) | IPortionFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([ParagraphFormat](../paragraphformat)) | Sets defined paragraph format properties to all column cells' paragraphs. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../paragraphformat) | IParagraphFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat([TextFrameFormat](../textframeformat)) | Sets defined text frame format properties to all column cells' text frames. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../textframeformat) | ITextFrameFormat object with necessary properties set. |


---


### setWidth {#setWidth}

| Name | Description |
| --- | --- |
| setWidth(double) | Returns or sets the width of a column. Read/write double. |


---


### size {#size}

| Name | Description |
| --- | --- |
| size() | Returns the number of cells in a collection. Read-only int. |

 **Result:**
int


---


