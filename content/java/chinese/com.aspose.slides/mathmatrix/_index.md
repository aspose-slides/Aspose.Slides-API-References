---
title: MathMatrix
second_title: Aspose.Slides for Java API 参考
description: 指定由一个或多个行列排列的子元素组成的 Matrix 对象。
type: docs
url: /zh/com.aspose.slides/mathmatrix/
---
**继承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口:**  
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

指定 Matrix 对象，由一个或多个行列排列的子元素组成。需要注意的是矩阵没有内置的定界符。要在括号中放置矩阵，应使用定界符对象 (IMathDelimiter)。可以使用 null 参数在矩阵中创建空隙。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | 初始化 MathMatrix 类的一个新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRowCount()](#getRowCount--) | 矩阵的行数 |
| [getColumnCount()](#getColumnCount--) | 矩阵的列数 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 隐藏空矩阵元素的占位符 默认：false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 隐藏空矩阵元素的占位符 默认：false |
| [getBaseJustification()](#getBaseJustification--) | 指定相对于周围文本的垂直对齐方式。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定相对于周围文本的垂直对齐方式。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 最小列宽，单位为 twips（1/20 点）。间隙间距（也称为 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d）会加到 MinColumnWidth 上，以确定总的矩阵列间距（不同列相同边缘之间的距离）。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 最小列宽，单位为 twips（1/20 点）。间隙间距（也称为 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d）会加到 MinColumnWidth 上，以确定总的矩阵列间距（不同列相同边缘之间的距离）。 |
| [getColumnGapRule()](#getColumnGapRule--) | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或 points（以 twips 存储）。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或 points（以 twips 存储）。 |
| [getColumnGap()](#getColumnGap--) | 矩阵列之间水平间距的值；如果 ColumnGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果设置为 4（\"Multiple\"），则单位解释为 0.5 em 的增量数。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 矩阵列之间水平间距的值；如果 ColumnGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果设置为 4（\"Multiple\"），则单位解释为 0.5 em 的增量数。 |
| [getRowGapRule()](#getRowGapRule--) | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或 points（以 twips 存储）。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或 points（以 twips 存储）。 |
| [getRowGap()](#getRowGap--) | 矩阵行之间垂直间距的值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果设置为 4（\"Multiple\"），则单位解释为半行。 |
| [setRowGap(long value)](#setRowGap-long-) | 矩阵行之间垂直间距的值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果设置为 4（\"Multiple\"），则单位解释为半行。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | 矩阵元素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 矩阵元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 获取指定列的水平对齐方式 |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 设置指定列的水平对齐方式 |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 设置指定列的水平对齐方式 |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 在指定行之前插入新行，新的行中的所有元素最初为 null。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 在指定行之后插入新行，新的行中的所有元素最初为 null。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 删除指定的行 |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 在指定列之前插入新列，新的列中的所有元素最初为 null。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 在指定列之后插入新列，新的列中的所有元素最初为 null。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 删除指定的列 |
| [getChildren()](#getChildren--) | 获取子元素 |

### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

初始化 MathMatrix 类的一个新实例。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowCount | int | 行数 |
| columnCount | int | 列数 |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

矩阵的行数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**返回:**  
int
### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

矩阵的列数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**返回:**  
int
### getHidePlaceholders() {#getHidePlaceholders--}
```
public final boolean getHidePlaceholders()
```

隐藏空矩阵元素的占位符 默认：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**返回:**  
boolean
### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public final void setHidePlaceholders(boolean value)
```

隐藏空矩阵元素的占位符 默认：false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

指定相对于周围文本的垂直对齐方式。可能的值有 top、bottom 和 center。默认：Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**返回:**  
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

指定相对于周围文本的垂直对齐方式。可能的值有 top、bottom 和 center。默认：Center

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public final long getMinColumnWidth()
```

最小列宽，单位为 twips（1/20 点）。间隙间距（也称为 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d）会加到 MinColumnWidth 上，以确定总的矩阵列间距（不同列相同边缘之间的距离）。默认：0。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**返回:**  
long
### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public final void setMinColumnWidth(long value)
```

最小列宽，单位为 twips（1/20 点）。间隙间距（也称为 \\u201cColumn Gap\\u201d 或 \\u201cGap Width\\u201d）会加到 MinColumnWidth 上，以确定总的矩阵列间距（不同列相同边缘之间的距离）。默认：0。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public final int getColumnGapRule()
```

矩阵列之间水平间距的类型；水平间距单位可以是 em 或 points（以 twips 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**返回:**  
int
### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public final void setColumnGapRule(int value)
```

矩阵列之间水平间距的类型；水平间距单位可以是 em 或 points（以 twips 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public final long getColumnGap()
```

矩阵列之间水平间距的值；如果 ColumnGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4（\"Multiple\"），则单位解释为 0.5 em 的增量数。其他情况下忽略。默认：0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**返回:**  
long
### setColumnGap(long value) {#setColumnGap-long-}
```
public final void setColumnGap(long value)
```

矩阵列之间水平间距的值；如果 ColumnGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4（\"Multiple\"），则单位解释为 0.5 em 的增量数。其他情况下忽略。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public final int getRowGapRule()
```

矩阵行之间垂直间距的类型；垂直间距单位可以是行或 points（以 twips 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**返回:**  
int
### setRowGapRule(int value) {#setRowGapRule-int-}
```
public final void setRowGapRule(int value)
```

矩阵行之间垂直间距的类型；垂直间距单位可以是行或 points（以 twips 存储）。默认：SingleSpacingGap (0)

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public final long getRowGap()
```

矩阵行之间垂直间距的值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为半行。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**返回:**  
long
### setRowGap(long value) {#setRowGap-long-}
```
public final void setRowGap(long value)
```

矩阵行之间垂直间距的值；如果 RowGapRule 设置为 3（\"Exactly\"），则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4（\"Multiple\"），则单位解释为半行。默认：0

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

矩阵元素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要获取项目的行的零基索引 |
| column | int | 要获取项目的列的零基索引 |

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

矩阵元素

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要获取项目的行的零基索引 |
| column | int | 要获取项目的列的零基索引 |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

获取指定列的水平对齐方式

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |

**返回:**  
int - 指定列的水平对齐方式
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

设置指定列的水平对齐方式

--------------------

> ```
> 示例



```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |
| val | int | 指定列的水平对齐方式的新值 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

设置指定列的水平对齐方式

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要设置对齐方式的第一列的零基索引 |
| columnsCount | long | 要指定对齐方式的列数 |
| val | int | 指定列的水平对齐方式的新值 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

在指定行之前插入新行，新的行中的所有元素最初为 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 在其前面插入新行的行索引 |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

在指定行之后插入新行，新的行中的所有元素最初为 null。

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 在其后面插入新行的行索引 |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

删除指定的行

--------------------

> ```
> 示例：
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 要删除的行的零基索引。 |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public final void insertColumnBefore(int columnIndex)
```

在指定列之前插入新列，新的列中的所有元素最初为 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 在其前面插入新列的列索引 |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

在指定列之后插入新列，新的列中的所有元素最初为 null。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 在其后面插入新列的列索引 |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

删除指定的列

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要删除的列的零基索引。 |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回:**  
com.aspose.slides.IMathElement[]