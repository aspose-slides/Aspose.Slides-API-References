---
title: ITable
second_title: Aspose.Slides for Java API Reference
description: Represents a table on a slide.
type: docs
url: /com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Represents a table on a slide.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Returns the cell at the specified column and row indexes. |
| [getRows()](#getRows--) | Returns the collectoin of rows. |
| [getColumns()](#getColumns--) | Returns the collectoin of columns. |
| [getTableFormat()](#getTableFormat--) | Returns the TableFormat object that contains formatting properties for this table. |
| [getStylePreset()](#getStylePreset--) | Get's or sets builtin table style. |
| [setStylePreset(int value)](#setStylePreset-int-) | Get's or sets builtin table style. |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Merges neighbour cells. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```


Returns the cell at the specified column and row indexes. Read-only [ICell](../../com.aspose.slides/icell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```


Returns the collectoin of rows. Read-only [IRowCollection](../../com.aspose.slides/irowcollection).

**Returns:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```


Returns the collectoin of columns. Read-only [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Returns:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```


Returns the TableFormat object that contains formatting properties for this table. Read-only [ITableFormat](../../com.aspose.slides/itableformat).

**Returns:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```


Get's or sets builtin table style. Read/write [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Returns:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```


Get's or sets builtin table style. Read/write [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Determines whether the table has right to left reading order. Read-write boolean.

**Returns:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```


Determines whether the table has right to left reading order. Read-write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```


Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```


Determines whether the first row of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```


Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```


Determines whether the first column of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```


Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```


Determines whether the last row of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```


Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean.

**Returns:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```


Determines whether the last column of a table has to be drawn with a special formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```


Determines whether the even rows has to be drawn with a different formatting. Read/write boolean.

**Returns:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```


Determines whether the even rows has to be drawn with a different formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```


Determines whether the even columns has to be drawn with a different formatting. Read/write boolean.

**Returns:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```


Determines whether the even columns has to be drawn with a different formatting. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
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
