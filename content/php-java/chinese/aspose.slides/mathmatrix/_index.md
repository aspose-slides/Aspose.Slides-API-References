---
title: MathMatrix
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/mathmatrix/
---
## MathMatrix 类

指定 Matrix 对象，由一个或多个行和列中的子元素布局组成。  
重要的是，矩阵没有内置定界符。  
要将矩阵放在括号中，应使用定界符对象 (IMathDelimiter)。  
可以使用 null 参数在矩阵中创建间隙。

### MathMatrix {#MathMatrix}

| 名称 | 描述 |
| --- | --- |
| MathMatrix(int, int) | 初始化 MathMatrix 类的新实例。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rowCount | int | 行数 |
| columnCount | int | 列数 |

**返回值：**
MathMatrix

---

### deleteColumn {#deleteColumn}

| 名称 | 描述 |
| --- | --- |
| deleteColumn (int) | 删除指定的列 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要删除的列的零基索引。 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 如果 columnIndex 小于零或大于等于 ColumnCount |

---

### deleteRow {#deleteRow}

| 名称 | 描述 |
| --- | --- |
| deleteRow (int) | 删除指定的行 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 要删除的行的零基索引。 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 如果 rowIndex 小于零或大于等于 RowCount |

---

### getBaseJustification {#getBaseJustification}

| 名称 | 描述 |
| --- | --- |
| getBaseJustification () | 指定相对于周围文本的垂直对齐方式。可能的值为 top、bottom 和 center。默认：Center |

**返回值：**
int

---

### getChildren {#getChildren}

| 名称 | 描述 |
| --- | --- |
| getChildren () | 获取子元素 |

**返回值：**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)

---

### getColumnAlignment {#getColumnAlignment}

| 名称 | 描述 |
| --- | --- |
| getColumnAlignment (int) | 获取指定列的水平对齐方式 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |

**返回值：**
int

---

### getColumnCount {#getColumnCount}

| 名称 | 描述 |
| --- | --- |
| getColumnCount () | 矩阵中的列数 |

**返回值：**
int

---

### getColumnGap {#getColumnGap}

| 名称 | 描述 |
| --- | --- |
| getColumnGap () | 矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3 (“Exactly”)，则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4 (“Multiple”)，则单位解释为 0.5 em 增量的数量。其他情况忽略。默认：0 |

**返回值：**
long

---

### getColumnGapRule {#getColumnGapRule}

| 名称 | 描述 |
| --- | --- |
| getColumnGapRule () | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twips 存储）。默认：SingleSpacingGap (0) |

**返回值：**
int

---

### getHidePlaceholders {#getHidePlaceholders}

| 名称 | 描述 |
| --- | --- |
| getHidePlaceholders () | 隐藏空矩阵元素的占位符。默认：false |

**返回值：**
boolean

---

### getMinColumnWidth {#getMinColumnWidth}

| 名称 | 描述 |
| --- | --- |
| getMinColumnWidth () | 最小列宽，单位为 twips（1/20 点）。间距（亦称 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定整体矩阵列间距（不同列相同边缘之间的距离）。默认：0。 |

**返回值：**
long

---

### getRowCount {#getRowCount}

| 名称 | 描述 |
| --- | --- |
| getRowCount () | 矩阵中的行数 |

**返回值：**
int

---

### getRowGap {#getRowGap}

| 名称 | 描述 |
| --- | --- |
| getRowGap () | 矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3 (“Exactly”)，则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4 (“Multiple”)，则单位解释为半行。默认：0 |

**返回值：**
long

---

### getRowGapRule {#getRowGapRule}

| 名称 | 描述 |
| --- | --- |
| getRowGapRule () | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0) |

**返回值：**
int

---

### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int, int) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要获取元素的行的零基索引 |
| column | int | 要获取元素的列的零基索引 |

**返回值：**
[MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement), [MathLimit](../mathlimit), [MathMatrix](../mathmatrix), [MathBlock](../mathblock), [MathRadical](../mathradical), [MathArray](../matharray), [MathPhantom](../mathphantom), [MathDelimiter](../mathdelimiter), [MathNaryOperator](../mathnaryoperator), [MathAccent](../mathaccent), [MathBorderBox](../mathborderbox), [MathGroupingCharacter](../mathgroupingcharacter), [MathBar](../mathbar), [MathSuperscriptElement](../mathsuperscriptelement), [MathFunction](../mathfunction), [MathSubscriptElement](../mathsubscriptelement), [MathFraction](../mathfraction), [MathematicalText](../mathematicaltext), [BaseScript](../basescript), [MathBox](../mathbox), [MathElementBase](../mathelementbase), [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)

---

### insertColumnAfter {#insertColumnAfter}

| 名称 | 描述 |
| --- | --- |
| insertColumnAfter (int) | 在指定列之后插入新列，初始时新列的所有元素均为 null。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要在其后插入新列的列索引 |

**返回值：**
void

---

### insertColumnBefore {#insertColumnBefore}

| 名称 | 描述 |
| --- | --- |
| insertColumnBefore (int) | 在指定列之前插入新列，初始时新列的所有元素均为 null。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 要在其前插入新列的列索引 |

**返回值：**
void

---

### insertRowAfter {#insertRowAfter}

| 名称 | 描述 |
| --- | --- |
| insertRowAfter (int) | 在指定行之后插入新行，初始时新行的所有元素均为 null。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 要在其后插入新行的行索引 |

**返回值：**
void

---

### insertRowBefore {#insertRowBefore}

| 名称 | 描述 |
| --- | --- |
| insertRowBefore (int) | 在指定行之前插入新行，初始时新行的所有元素均为 null。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | int | 要在其前插入新行的行索引 |

**返回值：**
void

---

### setBaseJustification {#setBaseJustification}

| 名称 | 描述 |
| --- | --- |
| setBaseJustification (int) | 指定相对于周围文本的垂直对齐方式。可能的值为 top、bottom 和 center。默认：Center |

**返回值：**
void

---

### setColumnAlignment {#setColumnAlignment}

| 名称 | 描述 |
| --- | --- |
| setColumnAlignment (int, int) | 设置指定列的水平对齐方式 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 零基列索引 |
| val | int | 指定列水平对齐方式的新值 |

**返回值：**
void

---

### setColumnGap {#setColumnGap}

| 名称 | 描述 |
| --- | --- |
| setColumnGap (long) | 矩阵列之间的水平间距值；如果 ColumnGapRule 设置为 3 (“Exactly”)，则单位解释为 twips（1/20 点）；如果 ColumnGapRule 设置为 4 (“Multiple”)，则单位解释为 0.5 em 增量的数量。其他情况忽略。默认：0 |

**返回值：**
void

---

### setColumnGapRule {#setColumnGapRule}

| 名称 | 描述 |
| --- | --- |
| setColumnGapRule (int) | 矩阵列之间水平间距的类型；水平间距单位可以是 em 或点（以 twips 存储）。默认：SingleSpacingGap (0) |

**返回值：**
void

---

### setColumnsAlignment {#setColumnsAlignment}

| 名称 | 描述 |
| --- | --- |
| setColumnsAlignment (int, long, int) | 设置指定列的水平对齐方式 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | int | 第一个要设置对齐方式的列的零基索引 |
| columnsCount | long | 要设置对齐方式的列数 |
| val | int | 指定列水平对齐方式的新值 |

**返回值：**
void

---

### setHidePlaceholders {#setHidePlaceholders}

| 名称 | 描述 |
| --- | --- |
| setHidePlaceholders (boolean) | 隐藏空矩阵元素的占位符。默认：false |

**返回值：**
void

---

### setMinColumnWidth {#setMinColumnWidth}

| 名称 | 描述 |
| --- | --- |
| setMinColumnWidth (long) | 最小列宽，单位为 twips（1/20 点）。间距（亦称 “Column Gap” 或 “Gap Width”）会加到 MinColumnWidth 上，以确定整体矩阵列间距（不同列相同边缘之间的距离）。默认：0。 |

**返回值：**
void

---

### setRowGap {#setRowGap}

| 名称 | 描述 |
| --- | --- |
| setRowGap (long) | 矩阵行之间的垂直间距值；如果 RowGapRule 设置为 3 (“Exactly”)，则单位解释为 twips（1/20 点）；如果 RowGapRule 设置为 4 (“Multiple”)，则单位解释为半行。默认：0 |

**返回值：**
void

---

### setRowGapRule {#setRowGapRule}

| 名称 | 描述 |
| --- | --- |
| setRowGapRule (int) | 矩阵行之间垂直间距的类型；垂直间距单位可以是行或点（以 twips 存储）。默认：SingleSpacingGap (0) |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathLimit](../mathlimit)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathMatrix](../mathmatrix)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathBlock](../mathblock)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathRadical](../mathradical)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathArray](../matharray)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathPhantom](../mathphantom)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathDelimiter](../mathdelimiter)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathNaryOperator](../mathnaryoperator)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathAccent](../mathaccent)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathBorderBox](../mathborderbox)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathGroupingCharacter](../mathgroupingcharacter)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathBar](../mathbar)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathSuperscriptElement](../mathsuperscriptelement)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathFunction](../mathfunction)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathSubscriptElement](../mathsubscriptelement)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathFraction](../mathfraction)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathematicalText](../mathematicaltext)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [BaseScript](../basescript)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathBox](../mathbox)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathElementBase](../mathelementbase)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void

---

### set_Item {#set_Item}

| 名称 | 描述 |
| --- | --- |
| set_Item (int, int, [MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | 矩阵元素 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| row | int | 要设置元素的行的零基索引 |
| column | int | 要设置元素的列的零基索引 |

**返回值：**
void