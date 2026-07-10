---
title: IMathMatrix
second_title: Aspose.Slides for Android via Java API 参考
description: 指定矩阵对象，由布局在一个或多个行和列中的子元素组成。
type: docs
url: /zh/com.aspose.slides/imathmatrix/
---
**所有已实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

指定 Matrix 对象，由布局在一个或多个行和列中的子元素组成。需要注意的是，矩阵没有内置的定界符。要在括号中放置矩阵，应使用定界符对象 (IMathDelimiter)。可以使用 null 参数在矩阵中创建空白。

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
| [getMinColumnWidth()](#getMinColumnWidth--) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). |
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

指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认：Center

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

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

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

Minimum column width in twips (1/20th of a point) The gap spacing (also referred to as \u201cColumn Gap\u201d or \u201cGap Width\u201d) is added to the MinColumnWidth to determine the total Matrix Column Spacing (distance between the same edges of different columns). Default: 0.

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

矩阵列之间的水平间距类型；水平间距单位可以是 ems 或 points（以 twips 存储）。默认：SingleSpacingGap (0)

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

矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3（"Exactly"），则该单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4（"Multiple"），则该单位解释为 0.5 em 增量的数量。其他情况下忽略。默认值：0

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

矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0)

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

矩阵行之间的垂直间距类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0)

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

矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3（"Exactly"），则该单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（"Multiple"），则该单位解释为半行。默认值：0

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

矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3（"Exactly"），则该单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（"Multiple"），则该单位解释为半行。默认值：0

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
设置指定列的水平对齐

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

插入一个新行到指定行之前，新的行中的所有元素初始为 null。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 在其之前插入新行的行索引 |

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
删除指定的行

--------------------

> ```
> 示例：
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
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 在其之前插入新列的列索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```
在指定列之后插入一个新列，新的列中的所有元素初始为 null。

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
Deletes the specified column

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要删除的列的零基索引。 |