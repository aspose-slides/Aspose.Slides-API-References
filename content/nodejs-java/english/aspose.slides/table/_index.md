---
title: Table
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/table/
---

## Table class

 Represents a table on a slide.
 

## Functions

| Name | Description |
| --- | --- |
| [getColumns]() | Returns the collectoin of columns. Read-only IColumnCollection. |

### Result
[ColumnCollection](../../columncollection)


---


| [getFillFormat]() | Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only IFillFormat. |

### Result
[FillFormat](../../fillformat)


---


| [getFirstCol]() | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| [getFirstRow]() | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| [getHorizontalBanding]() | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |

### Result
boolean


---


| [getLastCol]() | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| [getLastRow]() | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |

### Result
boolean


---


| [getRightToLeft]() | Determines whether the table has right to left reading order. Read-write boolean. |

### Result
boolean


---


| [getRows]() | Returns the collectoin of rows. Read-only IRowCollection. |

### Result
[RowCollection](../../rowcollection)


---


| [getStylePreset]() | Gets or sets builtin table style. Read/write TableStylePreset. |

### Result
int


---


| [getTableFormat]() | Returns the TableFormat object that contains formatting properties for this table. Read-only ITableFormat. |

### Result
[TableFormat](../../tableformat)


---


| [getVerticalBanding]() | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |

### Result
boolean


---


| [get_Item](int, int) | Returns the cell at the specified column and row indexes. Read-only Cell. |

### Result
[Cell](../../cell)


---


| [mergeCells]([Cell](../cell), [Cell](../cell), boolean) | Merges neighbour cells. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| cell1 | [Cell](../cell) | Cell to merge. |
| cell2 | [Cell](../cell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

### Result
[Cell](../../cell)


---


| [setFirstCol](boolean) | Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean. |


---


| [setFirstRow](boolean) | Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean. |


---


| [setHorizontalBanding](boolean) | Determines whether the even rows has to be drawn with a different formatting. Read/write boolean. |


---


| [setLastCol](boolean) | Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean. |


---


| [setLastRow](boolean) | Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean. |


---


| [setRightToLeft](boolean) | Determines whether the table has right to left reading order. Read-write boolean. |


---


| [setStylePreset](int) | Gets or sets builtin table style. Read/write TableStylePreset. |


---


| [setTextFormat]([PortionFormat](../portionformat)) | Sets defined portion format properties to all table cells' portions. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | [PortionFormat](../../portionformat) | IPortionFormat object with necessary properties set. |


---


| [setTextFormat]([ParagraphFormat](../paragraphformat)) | Sets defined paragraph format properties to all table cells' paragraphs. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | [ParagraphFormat](../../paragraphformat) | IParagraphFormat object with necessary properties set. |


---


| [setTextFormat]([TextFrameFormat](../textframeformat)) | Sets defined text frame format properties to all table cells' text frames. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| source | [TextFrameFormat](../../textframeformat) | ITextFrameFormat object with necessary properties set. |


---


| [setVerticalBanding](boolean) | Determines whether the even columns has to be drawn with a different formatting. Read/write boolean. |


---


