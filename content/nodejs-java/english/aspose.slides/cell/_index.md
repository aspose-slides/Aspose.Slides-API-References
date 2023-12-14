---
title: Cell
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/cell/
---

## Cell class

 Represents a cell of a table.
 
### getAnchorCenter {#getAnchorCenter}

| Name | Description |
| --- | --- |
| getAnchorCenter () | Determines whether or not text box centered inside a cell. Read/write boolean. |

 **Result:**
boolean


---


### getCellFormat {#getCellFormat}

| Name | Description |
| --- | --- |
| getCellFormat () | Returns the CellFormat object that contains formatting properties for this cell. Read-only ICellFormat. |

 **Result:**
[CellFormat](../cellformat)


---


### getColSpan {#getColSpan}

| Name | Description |
| --- | --- |
| getColSpan () | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only int. |

 **Result:**
int


---


### getFirstColumn {#getFirstColumn}

| Name | Description |
| --- | --- |
| getFirstColumn () | Gets first column of cell. Read-only IColumn. |

 **Result:**
[Column](../column)


---


### getFirstColumnIndex {#getFirstColumnIndex}

| Name | Description |
| --- | --- |
| getFirstColumnIndex () | Returns an index of first column, covered by the cell. Read-only int. |

 **Result:**
int


---


### getFirstRow {#getFirstRow}

| Name | Description |
| --- | --- |
| getFirstRow () | Gets first row of cell. Read-only IRow. |

 **Result:**
[Row](../row)


---


### getFirstRowIndex {#getFirstRowIndex}

| Name | Description |
| --- | --- |
| getFirstRowIndex () | Returns an index of first row, covered by the cell. Read-only int. |

 **Result:**
int


---


### getHeight {#getHeight}

| Name | Description |
| --- | --- |
| getHeight () | Returns the height of the cell. Read-only double. |

 **Result:**
double


---


### getMarginBottom {#getMarginBottom}

| Name | Description |
| --- | --- |
| getMarginBottom () | Returns or sets the bottom margin in a TextFrame. Read/write double. |

 **Result:**
double


---


### getMarginLeft {#getMarginLeft}

| Name | Description |
| --- | --- |
| getMarginLeft () | Returns or sets the left margin in a TextFrame. Read/write double. |

 **Result:**
double


---


### getMarginRight {#getMarginRight}

| Name | Description |
| --- | --- |
| getMarginRight () | Returns or sets the right margin in a TextFrame. Read/write double. |

 **Result:**
double


---


### getMarginTop {#getMarginTop}

| Name | Description |
| --- | --- |
| getMarginTop () | Returns or sets the top margin in a TextFrame. Read/write double. |

 **Result:**
double


---


### getMinimalHeight {#getMinimalHeight}

| Name | Description |
| --- | --- |
| getMinimalHeight () | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only double. |

 **Result:**
double


---


### getOffsetX {#getOffsetX}

| Name | Description |
| --- | --- |
| getOffsetX () | Returns a distance from left side of a table to left side of a cell. Read-only double. |

 **Result:**
double


---


### getOffsetY {#getOffsetY}

| Name | Description |
| --- | --- |
| getOffsetY () | Returns a distance from top side of a table to top side of a cell. Read-only double. |

 **Result:**
double


---


### getPresentation {#getPresentation}

| Name | Description |
| --- | --- |
| getPresentation () | Returns the parent presentation of a cell. Read-only IPresentation. |

 **Result:**
[Presentation](../presentation)


---


### getRowSpan {#getRowSpan}

| Name | Description |
| --- | --- |
| getRowSpan () | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only int. |

 **Result:**
int


---


### getSlide {#getSlide}

| Name | Description |
| --- | --- |
| getSlide () | Returns the parent slide of a cell. Read-only IBaseSlide. |

 **Result:**
[NotesSlide](../notesslide), [MasterSlide](../masterslide), [MasterNotesSlide](../masternotesslide), [LayoutSlide](../layoutslide), [BaseSlide](../baseslide), [MasterHandoutSlide](../masterhandoutslide), [Slide](../slide)


---


### getTable {#getTable}

| Name | Description |
| --- | --- |
| getTable () | Returns the parent Table object for a cell. Read-only ITable. |

 **Result:**
[Table](../table)


---


### getTextAnchorType {#getTextAnchorType}

| Name | Description |
| --- | --- |
| getTextAnchorType () | Returns or sets the text anchor type. Read/write TextAnchorType. |

 **Result:**
byte


---


### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame () | Returns the text frame of a cell. Read-only ITextFrame. |

 **Result:**
[TextFrame](../textframe)


---


### getTextVerticalType {#getTextVerticalType}

| Name | Description |
| --- | --- |
| getTextVerticalType () | Returns or sets the type of vertical text. Read/write TextVerticalType. |

 **Result:**
byte


---


### getWidth {#getWidth}

| Name | Description |
| --- | --- |
| getWidth () | Returns the width of the cell. Read-only double. |

 **Result:**
double


---


### isMergedCell {#isMergedCell}

| Name | Description |
| --- | --- |
| isMergedCell () | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only boolean. |

 **Result:**
boolean


---


### setAnchorCenter {#setAnchorCenter}

| Name | Description |
| --- | --- |
| setAnchorCenter (boolean) | Determines whether or not text box centered inside a cell. Read/write boolean. |


---


### setMarginBottom {#setMarginBottom}

| Name | Description |
| --- | --- |
| setMarginBottom (double) | Returns or sets the bottom margin in a TextFrame. Read/write double. |


---


### setMarginLeft {#setMarginLeft}

| Name | Description |
| --- | --- |
| setMarginLeft (double) | Returns or sets the left margin in a TextFrame. Read/write double. |


---


### setMarginRight {#setMarginRight}

| Name | Description |
| --- | --- |
| setMarginRight (double) | Returns or sets the right margin in a TextFrame. Read/write double. |


---


### setMarginTop {#setMarginTop}

| Name | Description |
| --- | --- |
| setMarginTop (double) | Returns or sets the top margin in a TextFrame. Read/write double. |


---


### setTextAnchorType {#setTextAnchorType}

| Name | Description |
| --- | --- |
| setTextAnchorType (byte) | Returns or sets the text anchor type. Read/write TextAnchorType. |


---


### setTextVerticalType {#setTextVerticalType}

| Name | Description |
| --- | --- |
| setTextVerticalType (byte) | Returns or sets the type of vertical text. Read/write TextVerticalType. |


---


### splitByColSpan {#splitByColSpan}

| Name | Description |
| --- | --- |
| splitByColSpan (int) | Splits the cell to two cells by index of column. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of column. |


---


### splitByHeight {#splitByHeight}

| Name | Description |
| --- | --- |
| splitByHeight (double) | Splits the cell by height. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| height | double | Height of a row. |


---


### splitByRowSpan {#splitByRowSpan}

| Name | Description |
| --- | --- |
| splitByRowSpan (int) | Splits the cell to two cells by index of row. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of row. |


---


### splitByWidth {#splitByWidth}

| Name | Description |
| --- | --- |
| splitByWidth (double) | Splits the cell by width. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| width | double | Width of a column. |


---


