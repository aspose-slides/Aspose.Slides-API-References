---
title: Table
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/table/
---

## Table class

 Represents a table on a slide.
 
### getColumns {#getColumns}

| Name | Description |
| --- | --- |
| getColumns () | Returns the collectoin of columns. Read-only IColumnCollection. |

 **Returns:**
[ColumnCollection](../columncollection)


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat () | Returns a TableFormat.FillFormat object containing the fill formatting for the Table. Read-only IFillFormat. |

 **Returns:**
[FillFormat](../fillformat)


---


### getFirstCol {#getFirstCol}

| Name | Description |
| --- | --- |
| getFirstCol () | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |

 **Returns:**
boolean


---


### getFirstRow {#getFirstRow}

| Name | Description |
| --- | --- |
| getFirstRow () | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |

 **Returns:**
boolean


---


### getHorizontalBanding {#getHorizontalBanding}

| Name | Description |
| --- | --- |
| getHorizontalBanding () | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |

 **Returns:**
boolean


---


### getLastCol {#getLastCol}

| Name | Description |
| --- | --- |
| getLastCol () | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |

 **Returns:**
boolean


---


### getLastRow {#getLastRow}

| Name | Description |
| --- | --- |
| getLastRow () | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |

 **Returns:**
boolean


---


### getRightToLeft {#getRightToLeft}

| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the table has right to left reading order. Read-write boolean. |

 **Returns:**
boolean


---


### getRows {#getRows}

| Name | Description |
| --- | --- |
| getRows () | Returns the collectoin of rows. Read-only IRowCollection. |

 **Returns:**
[RowCollection](../rowcollection)


---


### getStylePreset {#getStylePreset}

| Name | Description |
| --- | --- |
| getStylePreset () | Gets or sets builtin table style. Read/write TableStylePreset. |

 **Returns:**
int


---


### getTableFormat {#getTableFormat}

| Name | Description |
| --- | --- |
| getTableFormat () | Returns the TableFormat object that contains formatting properties for this table. Read-only ITableFormat. |

 **Returns:**
[TableFormat](../tableformat)


---


### getVerticalBanding {#getVerticalBanding}

| Name | Description |
| --- | --- |
| getVerticalBanding () | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |

 **Returns:**
boolean


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int, int) | Returns the cell at the specified column and row indexes. Read-only Cell. |

 **Returns:**
[Cell](../cell)


---


### mergeCells {#mergeCells}

| Name | Description |
| --- | --- |
| mergeCells ([Cell](../cell), [Cell](../cell), boolean) | Merges neighbour cells. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| cell1 | [Cell](../cell) | Cell to merge. |
| cell2 | [Cell](../cell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

 **Returns:**
[Cell](../cell)


---


### setFirstCol {#setFirstCol}

| Name | Description |
| --- | --- |
| setFirstCol (boolean) | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |


---


### setFirstRow {#setFirstRow}

| Name | Description |
| --- | --- |
| setFirstRow (boolean) | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |


---


### setHorizontalBanding {#setHorizontalBanding}

| Name | Description |
| --- | --- |
| setHorizontalBanding (boolean) | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |


---


### setLastCol {#setLastCol}

| Name | Description |
| --- | --- |
| setLastCol (boolean) | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |


---


### setLastRow {#setLastRow}

| Name | Description |
| --- | --- |
| setLastRow (boolean) | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |


---


### setRightToLeft {#setRightToLeft}

| Name | Description |
| --- | --- |
| setRightToLeft (boolean) | Determines whether the table has right to left reading order. Read-write boolean. |


---


### setStylePreset {#setStylePreset}

| Name | Description |
| --- | --- |
| setStylePreset (int) | Gets or sets builtin table style. Read/write TableStylePreset. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([PortionFormat](../portionformat)) | Sets defined portion format properties to all table cells' portions. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../portionformat) | IPortionFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([ParagraphFormat](../paragraphformat)) | Sets defined paragraph format properties to all table cells' paragraphs. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../paragraphformat) | IParagraphFormat object with necessary properties set. |


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([TextFrameFormat](../textframeformat)) | Sets defined text frame format properties to all table cells' text frames. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../textframeformat) | ITextFrameFormat object with necessary properties set. |


---


### setVerticalBanding {#setVerticalBanding}

| Name | Description |
| --- | --- |
| setVerticalBanding (boolean) | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |


---


