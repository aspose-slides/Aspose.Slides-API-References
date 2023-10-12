---
title: Table
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/table/
---

## Table class

 Represents a table on a slide.
 
| Name | Description |
| --- | --- |
| getColumns () | Returns the collectoin of columns. Read-only IColumnCollection. |

### Result
ColumnCollection(../../columncollection)


---


| Name | Description |
| --- | --- |
| getFillFormat () | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

### Result
FillFormat(../../fillformat)


---


| Name | Description |
| --- | --- |
| getFirstCol () | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getFirstRow () | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getHorizontalBanding () | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getLastCol () | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getLastRow () | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getRightToLeft () | Determines whether the table has right to left reading order. Read-write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| getRows () | Returns the collectoin of rows. Read-only IRowCollection. |

### Result
RowCollection(../../rowcollection)


---


| Name | Description |
| --- | --- |
| getStylePreset () | Gets or sets builtin table style. Read/write TableStylePreset. |

### Result
int


---


| Name | Description |
| --- | --- |
| getTableFormat () | Returns the TableFormat object that contains formatting properties for this table. Read-only ITableFormat. |

### Result
TableFormat(../../tableformat)


---


| Name | Description |
| --- | --- |
| getVerticalBanding () | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |

### Result
boolean


---


| Name | Description |
| --- | --- |
| get_Item (int, int) | Returns the cell at the specified column and row indexes. Read-only Cell. |

### Result
Cell(../../cell)


---


| Name | Description |
| --- | --- |
| mergeCells (Cell(../cell), Cell(../cell), boolean) | Merges neighbour cells. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cell1 | Cell(../cell) | Cell to merge. |
| cell2 | Cell(../cell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

### Result
Cell(../../cell)


---


| Name | Description |
| --- | --- |
| setFirstCol (boolean) | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setFirstRow (boolean) | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setHorizontalBanding (boolean) | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setLastCol (boolean) | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setLastRow (boolean) | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |


---


| Name | Description |
| --- | --- |
| setRightToLeft (boolean) | Determines whether the table has right to left reading order. Read-write boolean. |


---


| Name | Description |
| --- | --- |
| setStylePreset (int) | Gets or sets builtin table style. Read/write TableStylePreset. |


---


| Name | Description |
| --- | --- |
| setTextFormat (PortionFormat(../portionformat)) | Sets defined portion format properties to all table cells' portions. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | PortionFormat(../../portionformat) | IPortionFormat object with necessary properties set. |


---


| Name | Description |
| --- | --- |
| setTextFormat (ParagraphFormat(../paragraphformat)) | Sets defined paragraph format properties to all table cells' paragraphs. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | ParagraphFormat(../../paragraphformat) | IParagraphFormat object with necessary properties set. |


---


| Name | Description |
| --- | --- |
| setTextFormat (TextFrameFormat(../textframeformat)) | Sets defined text frame format properties to all table cells' text frames. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | TextFrameFormat(../../textframeformat) | ITextFrameFormat object with necessary properties set. |


---


| Name | Description |
| --- | --- |
| setVerticalBanding (boolean) | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |


---


