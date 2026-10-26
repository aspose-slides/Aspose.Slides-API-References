---
title: MathMatrix
second_title: Java 用 Aspose.Slides API リファレンス
description: 子要素が1つ以上の行と列に配置されたマトリックスオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathmatrix/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathMatrix](../../com.aspose.slides/imathmatrix), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathMatrix extends MathElementBase implements IMathMatrix, IHasControlCharacterProperties
```

マトリックスオブジェクトを指定します。子要素は 1 つ以上の行と列に配置されます。マトリックスには組み込みのデリミタがないことに注意してください。マトリックスを括弧で囲むにはデリミタオブジェクト (IMathDelimiter) を使用する必要があります。NULL 引数を使用して、マトリックス内に空白を作成できます。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathMatrix(int rowCount, int columnCount)](#MathMatrix-int-int-) | MathMatrix クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRowCount()](#getRowCount--) | マトリックスの行数 |
| [getColumnCount()](#getColumnCount--) | マトリックスの列数 |
| [getHidePlaceholders()](#getHidePlaceholders--) | 空のマトリックス要素のプレースホルダーを非表示にします デフォルト: false |
| [setHidePlaceholders(boolean value)](#setHidePlaceholders-boolean-) | 空のマトリックス要素のプレースホルダーを非表示にします デフォルト: false |
| [getBaseJustification()](#getBaseJustification--) | 周囲のテキストに対する垂直揃えを指定します。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 周囲のテキストに対する垂直揃えを指定します。 |
| [getMinColumnWidth()](#getMinColumnWidth--) | 列幅の最小値（twips (ポイントの 1/20)） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、マトリックス列間隔の総計（異なる列の同じエッジ間の距離）を決定します。 |
| [setMinColumnWidth(long value)](#setMinColumnWidth-long-) | 列幅の最小値（twips (ポイントの 1/20)） ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、マトリックス列間隔の総計（異なる列の同じエッジ間の距離）を決定します。 |
| [getColumnGapRule()](#getColumnGapRule--) | マトリックスの列間の水平間隔のタイプ; 水平間隔の単位は em またはポイント (twips として保存) です。 |
| [setColumnGapRule(int value)](#setColumnGapRule-int-) | マトリックスの列間の水平間隔のタイプ; 水平間隔の単位は em またはポイント (twips として保存) です。 |
| [getColumnGap()](#getColumnGap--) | マトリックスの列間の水平間隔の値; ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。 |
| [setColumnGap(long value)](#setColumnGap-long-) | マトリックスの列間の水平間隔の値; ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。 |
| [getRowGapRule()](#getRowGapRule--) | マトリックスの行間の垂直間隔のタイプ; 垂直間隔の単位は行またはポイント (twips として保存) です。 |
| [setRowGapRule(int value)](#setRowGapRule-int-) | マトリックスの行間の垂直間隔のタイプ; 垂直間隔の単位は行またはポイント (twips として保存) です。 |
| [getRowGap()](#getRowGap--) | マトリックスの行間の垂直間隔の値; RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。 |
| [setRowGap(long value)](#setRowGap-long-) | マトリックスの行間の垂直間隔の値; RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。 |
| [get_Item(int row, int column)](#get-Item-int-int-) | マトリックスの要素 |
| [set_Item(int row, int column, IMathElement value)](#set-Item-int-int-com.aspose.slides.IMathElement-) | マトリックスの要素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
| [getColumnAlignment(int columnIndex)](#getColumnAlignment-int-) | 指定された列の水平揃えを取得します |
| [setColumnAlignment(int columnIndex, int val)](#setColumnAlignment-int-int-) | 指定された列の水平揃えを設定します |
| [setColumnsAlignment(int columnIndex, long columnsCount, int val)](#setColumnsAlignment-int-long-int-) | 指定された列の水平揃えを設定します |
| [insertRowBefore(int rowIndex)](#insertRowBefore-int-) | 指定された位置の前に新しい行を挿入します。新しい行のすべての要素は null です。 |
| [insertRowAfter(int rowIndex)](#insertRowAfter-int-) | 指定された位置の後に新しい行を挿入します。新しい行のすべての要素は null です。 |
| [deleteRow(int rowIndex)](#deleteRow-int-) | 指定された行を削除します |
| [insertColumnBefore(int columnIndex)](#insertColumnBefore-int-) | 指定された位置の前に新しい列を挿入します。新しい列のすべての要素は null です。 |
| [insertColumnAfter(int columnIndex)](#insertColumnAfter-int-) | 指定された位置の後に新しい列を挿入します。新しい列のすべての要素は null です。 |
| [deleteColumn(int columnIndex)](#deleteColumn-int-) | 指定された列を削除します |
| [getChildren()](#getChildren--) | 子要素を取得します |
### MathMatrix(int rowCount, int columnCount) {#MathMatrix-int-int-}
```
public MathMatrix(int rowCount, int columnCount)
```

MathMatrix クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowCount | int | 行数 |
| columnCount | int | 列数 |

### getRowCount() {#getRowCount--}
```
public final int getRowCount()
```

マトリックスの行数

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
public final int getColumnCount()
```

マトリックスの列数

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
public final boolean getHidePlaceholders()
```

空のマトリックス要素のプレースホルダーを非表示にします デフォルト: false

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
public final void setHidePlaceholders(boolean value)
```

空のマトリックス要素のプレースホルダーを非表示にします デフォルト: false

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
public final int getBaseJustification()
```

周囲のテキストに対する垂直揃えを指定します。可能な値は top、bottom、center です。デフォルト: Center

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
public final void setBaseJustification(int value)
```

周囲のテキストに対する垂直揃えを指定します。可能な値は top、bottom、center です。デフォルト: Center

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
public final long getMinColumnWidth()
```

列幅の最小値（twips (ポイントの 1/20)）。ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、マトリックス列間隔の総計（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0.

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
public final void setMinColumnWidth(long value)
```

列幅の最小値（twips (ポイントの 1/20)）。ギャップ間隔（\\u201cColumn Gap\\u201d または \\u201cGap Width\\u201d とも呼ばれる）は MinColumnWidth に加算され、マトリックス列間隔の総計（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0.

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
public final int getColumnGapRule()
```

マトリックスの列間の水平間隔のタイプ; 水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)

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
public final void setColumnGapRule(int value)
```

マトリックスの列間の水平間隔のタイプ; 水平間隔の単位は em またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)

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
public final long getColumnGap()
```

マトリックスの列間の水平間隔の値; ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。他の場合は無視されます。デフォルト: 0

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
public final void setColumnGap(long value)
```

マトリックスの列間の水平間隔の値; ColumnGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。ColumnGapRule が 4（"Multiple"）に設定されている場合、単位は 0.5 em の増分数として解釈されます。他の場合は無視されます。デフォルト: 0

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
public final int getRowGapRule()
```

マトリックスの行間の垂直間隔のタイプ; 垂直間隔の単位は行またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)

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
public final void setRowGapRule(int value)
```

マトリックスの行間の垂直間隔のタイプ; 垂直間隔の単位は行またはポイント (twips として保存) です。デフォルト: SingleSpacingGap (0)

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
public final long getRowGap()
```

マトリックスの行間の垂直間隔の値; RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

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
public final void setRowGap(long value)
```

マトリックスの行間の垂直間隔の値; RowGapRule が 3（"Exactly"）に設定されている場合、単位は twips (ポイントの 1/20) と解釈されます。RowGapRule が 4（"Multiple"）に設定されている場合、単位は半行として解釈されます。デフォルト: 0

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

### get_Item(int row, int column) {#get-Item-int-int-}
```
public final IMathElement get_Item(int row, int column)
```

マトリックスの要素

--------------------

> ```
> 例:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得する行のゼロベースインデックス |
| column | int | 取得する列のゼロベースインデックス |

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement) - IMathElement
### set_Item(int row, int column, IMathElement value) {#set-Item-int-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int row, int column, IMathElement value)
```

マトリックスの要素

--------------------

> ```
> 例:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.set_Item(0, 0, new MathematicalText("item.1.1"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| row | int | 取得する行のゼロベースインデックス |
| column | int | 取得する列のゼロベースインデックス |
| value | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getColumnAlignment(int columnIndex) {#getColumnAlignment-int-}
```
public final int getColumnAlignment(int columnIndex)
```

指定された列の水平揃えを取得します

--------------------

> ```
> Example:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  MathHorizontalAlignment alignment = matrix.getColumnAlignment(0);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | ゼロベースの列インデックス |

**戻り値:**
int - 指定された列の水平揃え
### setColumnAlignment(int columnIndex, int val) {#setColumnAlignment-int-int-}
```
public final void setColumnAlignment(int columnIndex, int val)
```

指定された列の水平揃えを設定します

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
| val | int | 指定された列の水平揃えの新しい値 |

### setColumnsAlignment(int columnIndex, long columnsCount, int val) {#setColumnsAlignment-int-long-int-}
```
public final void setColumnsAlignment(int columnIndex, long columnsCount, int val)
```

指定された列群の水平揃えを設定します

--------------------

> ```
> 例:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.setColumnAlignment(0, MathHorizontalAlignment.Left);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int | 最初に揃えを設定する列のゼロベースインデックス |
| columnsCount | long | 揃えを指定する列数 |
| val | int | 指定された列の水平揃えの新しい値 |

### insertRowBefore(int rowIndex) {#insertRowBefore-int-}
```
public final void insertRowBefore(int rowIndex)
```

指定された位置の前に新しい行を挿入します。新しい行のすべての要素は null です。

--------------------

> ```
> 例:
>  
>  IMathMatrix matrix = new MathMatrix(2, 3);
>  matrix.insertRowBefore(1);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | int | 新しい行を挿入する前の行のインデックス |

### insertRowAfter(int rowIndex) {#insertRowAfter-int-}
```
public final void insertRowAfter(int rowIndex)
```

指定された位置の後に新しい行を挿入します。新しい行のすべての要素は null です。

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
| rowIndex | int | 新しい行を挿入する後の行のインデックス |

### deleteRow(int rowIndex) {#deleteRow-int-}
```
public final void deleteRow(int rowIndex)
```

指定された行を削除します

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
public final void insertColumnBefore(int columnIndex)
```

指定された位置の前に新しい列を挿入します。新しい列のすべての要素は null です。

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
| columnIndex | int | 新しい列を挿入する前の列のインデックス |

### insertColumnAfter(int columnIndex) {#insertColumnAfter-int-}
```
public final void insertColumnAfter(int columnIndex)
```

指定された位置の後に新しい列を挿入します。新しい列のすべての要素は null です。

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
| columnIndex | int | 新しい列を挿入する後の列のインデックス |

### deleteColumn(int columnIndex) {#deleteColumn-int-}
```
public final void deleteColumn(int columnIndex)
```

指定された列を削除します

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]