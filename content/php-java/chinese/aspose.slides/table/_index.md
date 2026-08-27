---
title: Table
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/table/
---
## Table 类

 表示幻灯片上的表格。
 
### getColumns {#getColumns}

| Name | Description |
| --- | --- |
| getColumns () | Returns the collectoin of columns. 只读 IColumnCollection. |

 **返回：**
[ColumnCollection](../columncollection)


---


### getFillFormat {#getFillFormat}

| Name | Description |
| --- | --- |
| getFillFormat () | Returns a TableFormat.FillFormat object containing the fill formatting for the Table. 只读 IFillFormat. |

 **返回：**
[FillFormat](../fillformat)


---


### getFirstCol {#getFirstCol}

| Name | Description |
| --- | --- |
| getFirstCol () | Determines whether the first column of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
boolean


---


### getFirstRow {#getFirstRow}

| Name | Description |
| --- | --- |
| getFirstRow () | Determines whether the first row of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
boolean


---


### getHorizontalBanding {#getHorizontalBanding}

| Name | Description |
| --- | --- |
| getHorizontalBanding () | Determines whether the even rows has to be drawn with a different formatting. 读写 boolean. |

 **返回：**
boolean


---


### getLastCol {#getLastCol}

| Name | Description |
| --- | --- |
| getLastCol () | Determines whether the last column of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
boolean


---


### getLastRow {#getLastRow}

| Name | Description |
| --- | --- |
| getLastRow () | Determines whether the last row of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
boolean


---


### getRightToLeft {#getRightToLeft}

| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the table has right to left reading order. 读写 boolean. |

 **返回：**
boolean


---


### getRows {#getRows}

| Name | Description |
| --- | --- |
| getRows () | Returns the collectoin of rows. 只读 IRowCollection. |

 **返回：**
[RowCollection](../rowcollection)


---


### getStylePreset {#getStylePreset}

| Name | Description |
| --- | --- |
| getStylePreset () | Gets or sets builtin table style. 读写 TableStylePreset. |

 **返回：**
int


---


### getTableFormat {#getTableFormat}

| Name | Description |
| --- | --- |
| getTableFormat () | Returns the TableFormat object that contains formatting properties for this table. 只读 ITableFormat. |

 **返回：**
[TableFormat](../tableformat)


---


### getVerticalBanding {#getVerticalBanding}

| Name | Description |
| --- | --- |
| getVerticalBanding () | Determines whether the even columns has to be drawn with a different formatting. 读写 boolean. |

 **返回：**
boolean


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int, int) | Returns the cell at the specified column and row indexes. 只读 Cell. |

 **返回：**
[Cell](../cell)


---


### mergeCells {#mergeCells}

| Name | Description |
| --- | --- |
| mergeCells ([Cell](../cell), [Cell](../cell), boolean) | Merges neighbour cells. |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| cell1 | [Cell](../cell) | Cell to merge. |
| cell2 | [Cell](../cell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

 **返回：**
[Cell](../cell)


---


### setFirstCol {#setFirstCol}

| Name | Description |
| --- | --- |
| setFirstCol (boolean) | Determines whether the first column of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
void


---


### setFirstRow {#setFirstRow}

| Name | Description |
| --- | --- |
| setFirstRow (boolean) | Determines whether the first row of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
void


---


### setHorizontalBanding {#setHorizontalBanding}

| Name | Description |
| --- | --- |
| setHorizontalBanding (boolean) | Determines whether the even rows has to be drawn with a different formatting. 读写 boolean. |

 **返回：**
void


---


### setLastCol {#setLastCol}

| Name | Description |
| --- | --- |
| setLastCol (boolean) | Determines whether the last column of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
void


---


### setLastRow {#setLastRow}

| Name | Description |
| --- | --- |
| setLastRow (boolean) | Determines whether the last row of a table has to be drawn with a special formatting. 读写 boolean. |

 **返回：**
void


---


### setRightToLeft {#setRightToLeft}

| Name | Description |
| --- | --- |
| setRightToLeft (boolean) | Determines whether the table has right to left reading order. 读写 boolean. |

 **返回：**
void


---


### setStylePreset {#setStylePreset}

| Name | Description |
| --- | --- |
| setStylePreset (int) | Gets or sets builtin table style. 读写 TableStylePreset. |

 **返回：**
void


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([PortionFormat](../portionformat)) | Sets defined portion format properties to all table cells' portions. |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../portionformat) | IPortionFormat object with necessary properties set. |

 **返回：**
void


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([ParagraphFormat](../paragraphformat)) | Sets defined paragraph format properties to all table cells' paragraphs. |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../paragraphformat) | IParagraphFormat object with necessary properties set. |

 **返回：**
void


---


### setTextFormat {#setTextFormat}

| Name | Description |
| --- | --- |
| setTextFormat ([TextFrameFormat](../textframeformat)) | Sets defined text frame format properties to all table cells' text frames. |

 **参数：**

| Name | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../textframeformat) | ITextFrameFormat object with necessary properties set. |

 **返回：**
void


---


### setVerticalBanding {#setVerticalBanding}

| Name | Description |
| --- | --- |
| setVerticalBanding (boolean) | Determines whether the even columns has to be drawn with a different formatting. 读写 boolean. |

 **返回：**
void


---  