---
title: Table
second_title: Aspose.Slides for Android の Java API リファレンス
description: スライド上のテーブルを表します。
type: docs
url: /ja/com.aspose.slides/table/
---
**継承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**すべての実装インターフェイス:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

スライド上のテーブルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 指定された列および行のインデックスにあるセルを返します。 |
| [getRows()](#getRows--) | 行のコレクションを返します。 |
| [getColumns()](#getColumns--) | 列のコレクションを返します。 |
| [getTableFormat()](#getTableFormat--) | このテーブルの書式設定プロパティを含む TableFormat オブジェクトを返します。 |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 隣接するセルを結合します。 |
| [getStylePreset()](#getStylePreset--) | 組み込みテーブルスタイルを取得または設定します。 |
| [setStylePreset(int value)](#setStylePreset-int-) | 組み込みテーブルスタイルを取得または設定します。 |
| [getRightToLeft()](#getRightToLeft--) | テーブルが右から左への読み順かどうかを判断します。 |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | テーブルが右から左への読み順かどうかを判断します。 |
| [getFirstRow()](#getFirstRow--) | テーブルの最初の行が特別な書式で描画されるかどうかを判断します。 |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | テーブルの最初の行が特別な書式で描画されるかどうかを判断します。 |
| [getFirstCol()](#getFirstCol--) | テーブルの最初の列が特別な書式で描画されるかどうかを判断します。 |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | テーブルの最初の列が特別な書式で描画されるかどうかを判断します。 |
| [getLastRow()](#getLastRow--) | テーブルの最後の行が特別な書式で描画されるかどうかを判断します。 |
| [setLastRow(boolean value)](#setLastRow-boolean-) | テーブルの最後の行が特別な書式で描画されるかどうかを判断します。 |
| [getLastCol()](#getLastCol--) | テーブルの最後の列が特別な書式で描画されるかどうかを判断します。 |
| [setLastCol(boolean value)](#setLastCol-boolean-) | テーブルの最後の列が特別な書式で描画されるかどうかを判断します。 |
| [getHorizontalBanding()](#getHorizontalBanding--) | 偶数行が異なる書式で描画されるかどうかを判断します。 |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | 偶数行が異なる書式で描画されるかどうかを判断します。 |
| [getVerticalBanding()](#getVerticalBanding--) | 偶数列が異なる書式で描画されるかどうかを判断します。 |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | 偶数列が異なる書式で描画されるかどうかを判断します。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 定義された部分書式プロパティをすべてのテーブルセルの部分に設定します。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 定義された段落書式プロパティをすべてのテーブルセルの段落に設定します。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 定義されたテキストフレーム書式プロパティをすべてのテーブルセルのテキストフレームに設定します。 |
| [getFillFormat()](#getFillFormat--) | テーブルの塗りつぶし書式を含む TableFormat.FillFormat オブジェクトを返します。 |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

指定された列および行のインデックスにあるセルを返します。読み取り専用 [Cell](../../com.aspose.slides/cell)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**戻り値:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

行のコレクションを返します。読み取り専用 [IRowCollection](../../com.aspose.slides/irowcollection)。

**戻り値:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

列のコレクションを返します。読み取り専用 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**戻り値:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

このテーブルの書式設定プロパティを含む TableFormat オブジェクトを返します。読み取り専用 [ITableFormat](../../com.aspose.slides/itableformat)。

**戻り値:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

隣接するセルを結合します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | 結合するセル。 |
| cell2 | [ICell](../../com.aspose.slides/icell) | 結合するセル。 |
| allowSplitting | boolean | セルの分割を許可する場合は true。 |

**戻り値:**
[ICell](../../com.aspose.slides/icell) - 結合されたセル。

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

組み込みテーブルスタイルを取得または設定します。読み書き [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**戻り値:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

組み込みテーブルスタイルを取得または設定します。読み書き [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

テーブルが右から左への読み順かどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

テーブルが右から左への読み順かどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

テーブルの最初の行が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

テーブルの最初の行が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

テーブルの最初の列が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

テーブルの最初の列が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

テーブルの最後の行が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

テーブルの最後の行が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

テーブルの最後の列が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

テーブルの最後の列が特別な書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

偶数行が異なる書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

偶数行が異なる書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

偶数列が異なる書式で描画されるかどうかを判断します。読み書き boolean 。

**戻り値:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

偶数列が異なる書式で描画されるかどうかを判断します。読み書き boolean 。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

定義された部分書式プロパティをすべてのテーブルセルの部分に設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 必要なプロパティが設定された IPortionFormat オブジェクト。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

定義された段落書式プロパティをすべてのテーブルセルの段落に設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 必要なプロパティが設定された IParagraphFormat オブジェクト。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

定義されたテキストフレーム書式プロパティをすべてのテーブルセルのテキストフレームに設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 必要なプロパティが設定された ITextFrameFormat オブジェクト。 |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

テーブルの塗りつぶし書式を含む TableFormat.FillFormat オブジェクトを返します。読み取り専用 [IFillFormat](../../com.aspose.slides/ifillformat)。

**戻り値:**
[IFillFormat](../../com.aspose.slides/ifillformat)