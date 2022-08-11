---
title: Table
second_title: Aspose.Slides for Java API Reference
description:  Represents a table on a slide.
type: docs
weight: 545
url: /java/com.aspose.slides/table/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITable](../../com.aspose.slides/itable)
```
public final class Table extends GraphicalObject implements ITable
```

Represents a table on a slide.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Returns the cell at the specified column and row indexes. |
| [getRows()](#getRows--) | Returns the collectoin of rows. |
| [getColumns()](#getColumns--) | Returns the collectoin of columns. |
| [getTableFormat()](#getTableFormat--) | Returns the TableFormat object that contains formatting properties for this table. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Merges neighbour cells. |
| [getStylePreset()](#getStylePreset--) | Gets or sets builtin table style. |
| [setStylePreset(int value)](#setStylePreset-int-) | Gets or sets builtin table style. |
| [getRightToLeft()](#getRightToLeft--) | Determines whether the table has right to left reading order. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Determines whether the table has right to left reading order. |
| [getFirstRow()](#getFirstRow--) | Determines whether the first row of a table has to be drawn with a special formatting. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Determines whether the first row of a table has to be drawn with a special formatting. |
| [getFirstCol()](#getFirstCol--) | Determines whether the first column of a table has to be drawn with a special formatting. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Determines whether the first column of a table has to be drawn with a special formatting. |
| [getLastRow()](#getLastRow--) | Determines whether the last row of a table has to be drawn with a special formatting. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Determines whether the last row of a table has to be drawn with a special formatting. |
| [getLastCol()](#getLastCol--) | Determines whether the last column of a table has to be drawn with a special formatting. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Determines whether the last column of a table has to be drawn with a special formatting. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Determines whether the even rows has to be drawn with a different formatting. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Determines whether the even rows has to be drawn with a different formatting. |
| [getVerticalBanding()](#getVerticalBanding--) | Determines whether the even columns has to be drawn with a different formatting. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Determines whether the even columns has to be drawn with a different formatting. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Sets defined portion format properties to all table cells' portions. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Sets defined paragraph format properties to all table cells' paragraphs. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Sets defined text frame format properties to all table cells' text frames. |
| [getFillFormat()](#getFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a shape. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```


Returns the cell at the specified column and row indexes. Read-only [Cell](../../com.aspose.slides/cell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public final IRowCollection getRows()
```


Returns the collectoin of rows. Read-only [IRowCollection](../../com.aspose.slides/irowcollection).

**Returns:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```


Returns the collectoin of columns. Read-only [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returns:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```


Returns the TableFormat object that contains formatting properties for this table. Read-only [ITableFormat](../../com.aspose.slides/itableformat).

**Returns:**
[ITableFormat](../../com.aspose.slides/itableformat)
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```


Merges neighbour cells.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Returns:**
[ICell](../../com.aspose.slides/icell) - Merged cell.
### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```


Gets or sets builtin table style. Read/write [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returns:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```


Gets or sets builtin table style. Read/write [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```


Determines whether the table has right to left reading order. Read-write boolean.

**Returns:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```


Determines whether the table has right to left reading order. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```


Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```


Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```


Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```


Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```


Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```


Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```


Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```


Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```


Determines whether the even rows has to be drawn with a different formatting. Read/write boolean.

**Returns:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```


Determines whether the even rows has to be drawn with a different formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```


Determines whether the even columns has to be drawn with a different formatting. Read/write boolean.

**Returns:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```


Determines whether the even columns has to be drawn with a different formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Sets defined portion format properties to all table cells' portions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat object with necessary properties set. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Sets defined paragraph format properties to all table cells' paragraphs.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat object with necessary properties set. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Sets defined text frame format properties to all table cells' text frames.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat object with necessary properties set. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```


Returns the FillFormat object that contains fill formatting properties for a shape. Note: can return null for certain types of shapes which don't have fill properties. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
