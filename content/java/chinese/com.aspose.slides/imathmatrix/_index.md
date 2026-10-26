---
title: IMathMatrix
second_title: Aspose.Slides Java API 参考
description: 指定矩阵对象，由排列在一个或多个行和列中的子元素组成。
type: docs
url: /zh/com.aspose.slides/imathmatrix/
---
**已实现的接口:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

指定 Matrix 对象，由按一行或多行多列布局的子元素组成。需要注意的是，矩阵没有内置分隔符。若要将矩阵放入括号中，应使用分隔符对象 (IMathDelimiter)。可以使用空参数在矩阵中创建间隙。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩阵的元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩阵的元素 |
| [getRowCount()](#getRowCount--) | 矩阵中的行数 |
| [getColumnCount()](#getColumnCount--) | 矩阵中的列数 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 隐藏空矩阵元素的占位符，默认：false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 隐藏空矩阵元素的占位符，默认：false |
| [getBaseJustification()](#getBaseJustification--) | 指定相对于周围文本的垂直对齐方式。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定相对于周围文本的垂直对齐方式。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 最小列宽，单位为 twip（1/20 点）。间隙宽度（也称为 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定矩阵列间总间距（不同列相同边缘之间的距离）。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 最小列宽，单位为 twip（1/20 点）。间隙宽度（也称为 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定矩阵列间总间距（不同列相同边缘之间的距离）。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twip 存储）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twip 存储）。 |
| [getColumnGap()](#getColumnGap--) | 矩阵列之间水平间距的数值；如果 ColumnGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为 0.5 em 的增量次数。其他情况下忽略。默认：0 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩阵列之间水平间距的数值；如果 ColumnGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为 0.5 em 的增量次数。其他情况下忽略。默认：0 |
| [getRowGapRule()](#getRowGapRule--) | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twip 存储）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twip 存储）。 |
| [getRowGap()](#getRowGap--) | 矩阵行之间垂直间距的数值；如果 RowGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为半行。默认：0 |
| [setRowGap(long value)](#setRowGap-long-) | 矩阵行之间垂直间距的数值；如果 RowGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为半行。默认：0 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 获取指定列的水平对齐方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 设置指定列的水平对齐方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 设置指定列的水平对齐方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定行之前插入新行，初始时新行的所有元素均为 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定行之后插入新行，初始时新行的所有元素均为 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 删除指定的行 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定列之前插入新列，初始时新列的所有元素均为 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定列之后插入新列，初始时新列的所有元素均为 null。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 删除指定的列 |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

矩阵的元素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| row | int | 获取元素的行的零基索引 |
| column | int | 获取元素的列的零基索引 |

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

矩阵的元素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| row | int | 获取元素的行的零基索引 |
| column | int | 获取元素的列的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

矩阵的行数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**返回值：**
int
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

矩阵的列数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**返回值：**
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

隐藏空矩阵元素的占位符，默认：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**返回值：**
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

隐藏空矩阵元素的占位符，默认：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认：Center

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**返回值：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认：Center

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

最小列宽，单位为 twip（1/20 点）。间隙宽度（也称为 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定矩阵列间总间距（不同列相同边缘之间的距离）。默认：0。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**返回值：**
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

最小列宽，单位为 twip（1/20 点）。间隙宽度（也称为 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定矩阵列间总间距（不同列相同边缘之间的距离）。默认：0。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twip 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**返回值：**
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twip 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

矩阵列之间水平间距的数值；如果 ColumnGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为 0.5 em 的增量次数。其他情况下忽略。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**返回值：**
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

矩阵列之间水平间距的数值；如果 ColumnGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为 0.5 em 的增量次数。其他情况下忽略。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twip 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**返回值：**
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twip 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

矩阵行之间垂直间距的数值；如果 RowGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为半行。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**返回值：**
long
### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

矩阵行之间垂直间距的数值；如果 RowGapRule 设置为 3（“Exactly”），则单位解释为 twip（1/20 点）；如果设置为 4（“Multiple”），则单位解释为半行。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

获取指定列的水平对齐方式

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |

**返回值：**
int - Horizontal Alignment of specified column
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

设置指定列的水平对齐方式

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |
| val | int | 指定列水平对齐方式的新值 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

设置指定列的水平对齐方式

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 第一个要设置对齐方式的列的零基索引 |
| columnsCount | long | 要指定对齐方式的列数 |
| val | int | 指定列水平对齐方式的新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

在指定行之前插入新行，初始时新行的所有元素均为 null。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| rowIndex | int | 要在其前面插入新行的行索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

在指定行之后插入新行，初始时新行的所有元素均为 null。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| rowIndex | int | 要在其后面插入新行的行索引 |

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

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| rowIndex | int | 要删除的行的零基索引。 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

在指定列之前插入新列，初始时新列的所有元素均为 null。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 要在其前面插入新列的列索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

在指定列之后插入新列，初始时新列的所有元素均为 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 要在其后面插入新列的列索引 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

删除指定的列

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| columnIndex | int | 要删除的列的零基索引。 |