---
title: IMathMatrix
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 子要素が1つ以上の行と列に配置された Matrix オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathmatrix/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

Matrix オブジェクトを指定します。このオブジェクトは、1 つ以上の行と列に配置された子要素で構成されます。行列には組み込みの区切り記号がないことに注意してください。行列を括弧で囲むには、区切りオブジェクト (IMathDelimiter) を使用する必要があります。null 引数を使用して、行列内に空白を作成できます。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int row, int column)](#get-Item-int-int-) | 行列の要素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | 行列の要素 |
| [getRowCount()](#getRowCount--) | 行列の行数 |
| [getColumnCount()](#getColumnCount--) | 行列の列数 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 空の行列要素のプレースホルダーを非表示にします (デフォルト: false) |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 空の行列要素のプレースホルダーを非表示にします (デフォルト: false) |
| [getBaseJustification()](#getBaseJustification--) | 周囲のテキストに対する垂直方向の揃えを指定します。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 周囲のテキストに対する垂直方向の揃えを指定します。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 最小列幅（twips（ポイントの 1/20）） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、総行列列間隔（異なる列の同じ端点間の距離）を決定します。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 最小列幅（twips（ポイントの 1/20）） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、総行列列間隔（異なる列の同じ端点間の距離）を決定します。 |
| [getColumnGapRule()](#getColumnGapRule--) | 行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twip 単位で保存）です。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twip 単位で保存）です。 |
| [getColumnGap()](#getColumnGap--) | 行列の列間の水平間隔の値。ColumnGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。ColumnGapRule が 4（「Multiple」）に設定されている場合、単位は 0.5 em 増分の数として解釈されます。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 行列の列間の水平間隔の値。ColumnGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。ColumnGapRule が 4（「Multiple」）に設定されている場合、単位は 0.5 em 増分の数として解釈されます。 |
| [getRowGapRule()](#getRowGapRule--) | 行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twip 単位で保存）です。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twip 単位で保存）です。 |
| [getRowGap()](#getRowGap--) | 行列の行間の垂直間隔の値。RowGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。RowGapRule が 4（「Multiple」）に設定されている場合、単位は半行として解釈されます。 |
| [setRowGap(long value)](#setRowGap-long-) | 行列の行間の垂直間隔の値。RowGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。RowGapRule が 4（「Multiple」）に設定されている場合、単位は半行として解釈されます。 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 指定された列の水平配置を取得します |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 指定された列の水平配置を設定します |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 指定された列の水平配置を設定します |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 指定された位置の前に新しい行を挿入します。新しい行のすべての要素は最初 null になります。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 指定された位置の後に新しい行を挿入します。新しい行のすべての要素は最初 null になる。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 指定された行を削除します |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 指定された位置の前に新しい列を挿入します。新しい列のすべての要素は最初 null になります。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 指定された位置の後に新しい列を挿入します。新しい列のすべての要素は最初 null になります。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 指定された列を削除します |

### get_Item(int row, int column) {#get-Item-int-int-}
```
public abstract IMathElement get_Item(int row, int column)
```

行列の要素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得する項目の行のゼロベースインデックス |
| column | int | 取得する項目の列のゼロベースインデックス |

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement

### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public abstract void set_Item(int row, int column, IMathElement value)
```

行列の要素

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得する項目の行のゼロベースインデックス |
| column | int | 取得する項目の列のゼロベースインデックス |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getRowCount() {#getRowCount--}
```
public abstract int getRowCount()
```

行列の行数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int rowCount = matrix.getRowCount();
> ```

**戻り値:**
int

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

行列の列数

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  int columnCount = matrix.getColumnCount();
> ```

**戻り値:**
int

### getHidePlaceholders() {#getHidePlaceholders--}
```
public abstract boolean getHidePlaceholders()
```

空の行列要素のプレースホルダーを非表示にします (デフォルト: false)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**戻り値:**
boolean

### setHidePlaceholders(boolean value) {#setHidePlaceholders-boolean-}
```
public abstract void setHidePlaceholders(boolean value)
```

空の行列要素のプレースホルダーを非表示にします (デフォルト: false)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

周囲のテキストに対する垂直方向の揃えを指定します。可能な値は top、bottom、center です。デフォルト: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**戻り値:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

周囲のテキストに対する垂直方向の揃えを指定します。可能な値は top、bottom、center です。デフォルト: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

最小列幅（twips（ポイントの 1/20）） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、総行列列間隔（異なる列の同じ端点間の距離）を決定します。デフォルト: 0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**戻り値:**
long

### setMinColumnWidth(long value) {#setMinColumnWidth-long-}
```
public abstract void setMinColumnWidth(long value)
```

最小列幅（twips（ポイントの 1/20）） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、総行列列間隔（異なる列の同じ端点間の距離）を決定します。デフォルト: 0。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twip 単位で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**戻り値:**
int

### setColumnGapRule(int value) {#setColumnGapRule-int-}
```
public abstract void setColumnGapRule(int value)
```

行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twip 単位で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

行列の列間の水平間隔の値。ColumnGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。ColumnGapRule が 4（「Multiple」）に設定されている場合、単位は 0.5 em 増分の数として解釈されます。それ以外の場合は無視されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**戻り値:**
long

### setColumnGap(long value) {#setColumnGap-long-}
```
public abstract void setColumnGap(long value)
```

行列の列間の水平間隔の値。ColumnGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。ColumnGapRule が 4（「Multiple」）に設定されている場合、単位は 0.5 em 増分の数として解釈されます。それ以外の場合は無視されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twip 単位で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**戻り値:**
int

### setRowGapRule(int value) {#setRowGapRule-int-}
```
public abstract void setRowGapRule(int value)
```

行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twip 単位で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

行列の行間の垂直間隔の値。RowGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。RowGapRule が 4（「Multiple」）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**戻り値:**
long

### setRowGap(long value) {#setRowGap-long-}
```
public abstract void setRowGap(long value)
```

行列の行間の垂直間隔の値。RowGapRule が 3（「Exactly」）に設定されている場合、単位は twip（ポイントの 1/20）として解釈されます。RowGapRule が 4（「Multiple」）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

指定された列の水平配置を取得します

--------------------

> ```
public abstract int getColumnAlignment(int columnIndex)
```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | ゼロベースの列インデックス |
**戻り値:**
int - 指定された列の水平配置

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

指定された列の水平配置を設定します

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | ゼロベースの列インデックス |
| val | int | 指定された列の水平配置の新しい値 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

指定された列の水平配置を設定します

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 水平配置を設定する最初の列のゼロベースインデックス |
| columnsCount | long | 配置を指定する列数 |
| val | int | 指定された列の水平配置の新しい値 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

指定された位置の前に新しい行を挿入します。新しい行のすべての要素は最初 null になります。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 新しい行を挿入する前の行のインデックス |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

指定された位置の後に新しい行を挿入します。新しい行のすべての要素は最初 null になる。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 新しい行を挿入する後の行のインデックス |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

指定された行を削除します

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 削除する行のゼロベースインデックス |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

指定された位置の前に新しい列を挿入します。新しい列のすべての要素は最初 null になります。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 新しい列を挿入する前の列のインデックス |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

指定された位置の後に新しい列を挿入します。新しい列のすべての要素は最初 null になる。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 新しい列を挿入する後の列のインデックス |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

指定された列を削除します

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 削除する列のゼロベースインデックス |