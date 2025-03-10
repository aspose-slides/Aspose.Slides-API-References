---
title: IMathMatrix
second_title: Aspose.Slides for Java API Reference
description: Specifies the Matrix object consisting of child elements laid out in one or more rows and columns.
type: docs
url: /com.aspose.slides/imathmatrix/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Specifies the Matrix object, consisting of child elements laid out in one or more rows and columns. It is important to note that matrices do not have built in delimiters. To place the matrix in the brackets you should use the delimiter object (IMathDelimiter). Null arguments can be used to create gaps in matrices.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | Elements of matrix |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | Elements of matrix |
| [getRowCount()](#getRowCount--) | Number of rows in the matrix |
| [getColumnCount()](#getColumnCount--) | Number of columns in the matrix |
| [getHidePlaceholders()](#getHidePlaceholders--) | Hide the placeholders for empty matrix elements Default: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | Hide the placeholders for empty matrix elements Default: false |
| [getBaseJustification()](#getBaseJustification--) | Specifies the vertical justification respect to surrounding text. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies the vertical justification respect to surrounding text. |
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [getColumnGapRule()](#getColumnGapRule--) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). |
| [getColumnGap()](#getColumnGap--) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [setColumnGap(long value)](#setColumnGap-long-) | The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. |
| [getRowGapRule()](#getRowGapRule--) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [setRowGapRule(int value)](#setRowGapRule-int-) | The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). |
| [getRowGap()](#getRowGap--) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [setRowGap(long value)](#setRowGap-long-) | The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | Get the horizontal alignment of the specified column |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | Set the horizontal alignment of the specified column |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | Set the horizontal alignment of the specified columns |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | Insert a new row before the specified one Initially all elements in the new row are null. |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | Insert a new row after the specified one Initially all elements in the new row are null. |
| [deleteRow(int rowIndex)](#deleteRow-int-) | Deletes the specified row |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | Insert a new column before the specified one Initially all elements in the new column are null. |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | Insert a new column after the specified one Initially all elements in the new column are null. |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | Deletes the specified column |
### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```


Elements of matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```


Elements of matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| row | int | The zero-based index of the row to get item |
| column | int | The zero-based index of the column to get item |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```


Number of rows in the matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**Returns:**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Number of columns in the matrix

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**Returns:**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```


Hide the placeholders for empty matrix elements Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Returns:**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```


Hide the placeholders for empty matrix elements Default: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


Specifies the vertical justification respect to surrounding text. Possible values are top, bottom, and center. Default: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```


Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Returns:**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```


Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \\u201cColumn Gap\\u201d or \\u201cGap Width\\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```


The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```


The type of horizontal spacing between columns of a matrix; Horizontal spacing units can be ems or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```


The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Returns:**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```


The value of horizontal spacing between columns of a matrix; If the ColumnGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the ColumnGapRule is set to 4 ("Multiple"), then the unit is interpreted as number of 0.5 em increments. In other cases ignored. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```


The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Returns:**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```


The type of vertical spacing between rows of a matrix; Vertical spacing units can be lines or points (stored as twips). Default: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```


The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Returns:**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```


The value of vertical spacing between rows of a matrix; If the RowGapRule is set to 3 ("Exactly"), then the unit is interpreted as twips (1/20th of a point) If the RowGapRule is set to 4 ("Multiple"), then the unit is interpreted as half-lines. Default: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```


Get the horizontal alignment of the specified column

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |

**Returns:**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```


Set the horizontal alignment of the specified column

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based column index |
| val | int | New value of horizontal alignment of specified column |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```


Set the horizontal alignment of the specified columns

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Zero-based index of the first column to set alignment |
| columnsCount | long | The number of columns to specify the alignment |
| val | int | New value of horizontal alignment of specified column |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```


Insert a new row before the specified one Initially all elements in the new row are null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row before which to insert a new one |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```


Insert a new row after the specified one Initially all elements in the new row are null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | Index of the row after which to insert a new one |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```


Deletes the specified row

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | int | The zero-based index of the row to delete. |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```


Insert a new column before the specified one Initially all elements in the new column are null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column before which to insert a new one |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```


Insert a new column after the specified one Initially all elements in the new column are null.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | Index of the column after which to insert a new one |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```


Deletes the specified column

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | int | The zero-based index of the column to delete. |

