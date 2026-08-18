---
title: IMathMatrix
second_title: Aspose.Slides の Java API リファレンス
description: 子要素が 1 行または複数行、列に配置された Matrix オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathmatrix/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathMatrix extends IMathElement
```

行列オブジェクトを指定します。子要素は 1 行または複数行、列に配置されます。行列には組み込みの区切り文字がないことに注意してください。行列を括弧で囲むにはデリミタ オブジェクト (IMathDelimiter) を使用します。null 引数を使用して行列内に空白を作成できます。

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
| [getHidePlaceholders()](#getHidePlaceholders--) | 空の行列要素のプレースホルダーを非表示にする デフォルト: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 空の行列要素のプレースホルダーを非表示にする デフォルト: false |
| [getBaseJustification()](#getBaseJustification--) | 周囲のテキストに対する垂直方向の配置を指定します。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 周囲のテキストに対する垂直方向の配置を指定します。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | twips（ポイントの1/20）単位の最小列幅。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、行列全体の列間隔（異なる列の同じエッジ間の距離）を決定します。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | twips（ポイントの1/20）単位の最小列幅。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、行列全体の列間隔（異なる列の同じエッジ間の距離）を決定します。 |
| [getColumnGapRule()](#getColumnGapRule--) | 行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twips で保存）です。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | 行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twips で保存）です。 |
| [getColumnGap()](#getColumnGap--) | 行列の列間の水平間隔の値。ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。 |
| [setColumnGap(long value)](#setColumnGap-long-) | 行列の列間の水平間隔の値。ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。 |
| [getRowGapRule()](#getRowGapRule--) | 行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twips で保存）です。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | 行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twips で保存）です。 |
| [getRowGap()](#getRowGap--) | 行列の行間の垂直間隔の値。RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。 |
| [setRowGap(long value)](#setRowGap-long-) | 行列の行間の垂直間隔の値。RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。 |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 指定された列の水平配置を取得する |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 指定された列の水平配置を設定する |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 指定された列の水平配置を設定する |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 指定された行の前に新しい行を挿入します。新しい行のすべての要素は null です。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 指定された行の後に新しい行を挿入します。新しい行のすべての要素は null です。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 指定された行を削除する |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 指定された列の前に新しい列を挿入します。新しい列のすべての要素は null です。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 指定された列の後に新しい列を挿入します。新しい列のすべての要素は null です。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 指定された列を削除する |

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得するアイテムの行のゼロベースインデックス |
| column | int | 取得するアイテムの列のゼロベースインデックス |

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得するアイテムの行のゼロベースインデックス |
| column | int | 取得するアイテムの列のゼロベースインデックス |
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

空の行列要素のプレースホルダーを非表示にする デフォルト: false

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

空の行列要素のプレースホルダーを非表示にする デフォルト: false

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setHidePlaceholders(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

周囲のテキストに対する垂直方向の配置を指定します。可能な値は top、bottom、center です。デフォルト: Center

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

周囲のテキストに対する垂直方向の配置を指定します。可能な値は top、bottom、center です。デフォルト: Center

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setBaseJustification(MathVerticalAlignment.Center);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinColumnWidth() {#getMinColumnWidth--}
```
public abstract long getMinColumnWidth()
```

twips（ポイントの1/20）単位の最小列幅。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、行列全体の列間隔（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0.

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

twips（ポイントの1/20）単位の最小列幅。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、行列全体の列間隔（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0.

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setMinColumnWidth(20);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getColumnGapRule() {#getColumnGapRule--}
```
public abstract int getColumnGapRule()
```

行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)

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

行列の列間の水平間隔のタイプ。水平間隔の単位は em またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getColumnGap() {#getColumnGap--}
```
public abstract long getColumnGap()
```

行列の列間の水平間隔の値。ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。他の場合は無視されます。デフォルト: 0

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

行列の列間の水平間隔の値。ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。他の場合は無視されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnGapRule(MathSpacingRules.Exactly);
>  matrix.setColumnGap(20);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getRowGapRule() {#getRowGapRule--}
```
public abstract int getRowGapRule()
```

行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)

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

行列の行間の垂直間隔のタイプ。垂直間隔の単位は行またはポイント（twips で保存）です。デフォルト: SingleSpacingGap (0)

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.OneAndHalfSpacingGap);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRowGap() {#getRowGap--}
```
public abstract long getRowGap()
```

行列の行間の垂直間隔の値。RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

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

行列の行間の垂直間隔の値。RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips（ポイントの1/20）として解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setRowGapRule(MathSpacingRules.Exactly);
>  matrix.setRowGap(20);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public abstract int getColumnAlignment(int columnIndex)
```

指定された列の水平配置を取得する

--------------------

> ```
public abstract int getColumnAlignment(int columnIndex)
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | ゼロベースの列インデックス |

**戻り値:**
int - 指定された列の水平配置

### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public abstract void setColumnAlignment(int columnIndex, int val)
```

指定された列の水平配置を設定する

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | ゼロベースの列インデックス |
| val | int | 指定された列の新しい水平配置の値 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public abstract void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

指定された列の水平配置を設定する

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, 3, MathHorizontalAlignment.Left);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 設定する最初の列のゼロベースインデックス |
| columnsCount | long | 配置を指定する列数 |
| val | int | 指定された列の新しい水平配置の値 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public abstract void insertRowBefore(int rowIndex)
```

指定された行の前に新しい行を挿入します。新しい行のすべての要素は null です。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 新しい行を挿入する対象行のインデックス |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public abstract void insertRowAfter(int rowIndex)
```

指定された行の後に新しい行を挿入します。新しい行のすべての要素は null です。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowAfter(1);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 新しい行を挿入する対象行のインデックス |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public abstract void deleteRow(int rowIndex)
```

指定された行を削除する

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteRow(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 削除する行のゼロベースインデックス |

### insertColumnBefore(int columnIndex) {#insertColumnBefore-int-}
```
public abstract void insertColumnBefore(int columnIndex)
```

指定された列の前に新しい列を挿入します。新しい列のすべての要素は null です。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnBefore(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 新しい列を挿入する対象列のインデックス |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public abstract void insertColumnAfter(int columnIndex)
```

指定された列の後に新しい列を挿入します。新しい列のすべての要素は null です。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertColumnAfter(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 新しい列を挿入する対象列のインデックス |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public abstract void deleteColumn(int columnIndex)
```

指定された列を削除する

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.deleteColumn(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 削除する列のゼロベースインデックス |