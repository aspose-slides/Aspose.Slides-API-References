---
title: Cell
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/cell/
---

## Cell class

 Represents a cell of a table.
 

## Functions

| Name | Description |
| --- | --- |
| [getAnchorCenter]() | Determines whether or not text box centered inside a cell. Read/write boolean. |

### Result
boolean


---


| [getCellFormat]() | Returns the CellFormat object that contains formatting properties for this cell. Read-only ICellFormat. |

### Result
[CellFormat](../../cellformat)


---


| [getColSpan]() | Returns the number of grid columns in the parent table's table grid which shall be spanned by the current cell. This property allows cells to have the appearance of being merged, as they span vertical boundaries of other cells in the table. Read-only int. |

### Result
int


---


| [getFirstColumn]() | Gets first column of cell. Read-only IColumn. |

### Result
[Column](../../column)


---


| [getFirstColumnIndex]() | Returns an index of first column, covered by the cell. Read-only int. |

### Result
int


---


| [getFirstRow]() | Gets first row of cell. Read-only IRow. |

### Result
[Row](../../row)


---


| [getFirstRowIndex]() | Returns an index of first row, covered by the cell. Read-only int. |

### Result
int


---


| [getHeight]() | Returns the height of the cell. Read-only double. |

### Result
double


---


| [getMarginBottom]() | Returns or sets the bottom margin in a TextFrame. Read/write double. |

### Result
double


---


| [getMarginLeft]() | Returns or sets the left margin in a TextFrame. Read/write double. |

### Result
double


---


| [getMarginRight]() | Returns or sets the right margin in a TextFrame. Read/write double. |

### Result
double


---


| [getMarginTop]() | Returns or sets the top margin in a TextFrame. Read/write double. |

### Result
double


---


| [getMinimalHeight]() | Returns the minimum height of a cell. This is a sum of minimal heights of all rows cowered by the cell. Read-only double. |

### Result
double


---


| [getOffsetX]() | Returns a distance from left side of a table to left side of a cell. Read-only double. |

### Result
double


---


| [getOffsetY]() | Returns a distance from top side of a table to top side of a cell. Read-only double. |

### Result
double


---


| [getPresentation]() | Returns the parent presentation of a cell. Read-only IPresentation. |

### Result
[Presentation](../../presentation)


---


| [getRowSpan]() | Returns the number of rows that a merged cell spans. This is used in combination with the vMerge attribute on other cells in order to specify the beginning cell of a horizontal merge. Read-only int. |

### Result
int


---


| [getSlide]() | Returns the parent slide of a cell. Read-only IBaseSlide. |

### Result
[MasterNotesSlide](../../masternotesslide), [MasterHandoutSlide](../../masterhandoutslide), [BaseSlide](../../baseslide), [NotesSlide](../../notesslide), [LayoutSlide](../../layoutslide), [Slide](../../slide), [MasterSlide](../../masterslide)


---


| [getTable]() | Returns the parent Table object for a cell. Read-only ITable. |

### Result
[Table](../../table)


---


| [getTextAnchorType]() | Returns or sets the text anchor type. Read/write TextAnchorType. |

### Result
byte


---


| [getTextFrame]() | Returns the text frame of a cell. Read-only ITextFrame. |

### Result
[TextFrame](../../textframe)


---


| [getTextVerticalType]() | Returns or sets the type of vertical text. Read/write TextVerticalType. |

### Result
byte


---


| [getWidth]() | Returns the width of the cell. Read-only double. |

### Result
double


---


| [isMergedCell]() | Returns true if the cell is merged with any adjusted cell, false otherwise. Read-only boolean. |

### Result
boolean


---


| [setAnchorCenter](boolean) | Determines whether or not text box centered inside a cell. Read/write boolean. |


---


| [setMarginBottom](double) | Returns or sets the bottom margin in a TextFrame. Read/write double. |


---


| [setMarginLeft](double) | Returns or sets the left margin in a TextFrame. Read/write double. |


---


| [setMarginRight](double) | Returns or sets the right margin in a TextFrame. Read/write double. |


---


| [setMarginTop](double) | Returns or sets the top margin in a TextFrame. Read/write double. |


---


| [setTextAnchorType](byte) | Returns or sets the text anchor type. Read/write TextAnchorType. |


---


| [setTextVerticalType](byte) | Returns or sets the type of vertical text. Read/write TextVerticalType. |


---


| [splitByColSpan](int) | Splits the cell to two cells by index of column. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of column. |


---


| [splitByHeight](double) | Splits the cell by height. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| height | double | Height of a row. |


---


| [splitByRowSpan](int) | Splits the cell to two cells by index of row. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of row. |


---


| [splitByWidth](double) | Splits the cell by width. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| width | double | Width of a column. |


---


