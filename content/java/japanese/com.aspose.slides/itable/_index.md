---
title: ITable
second_title: Aspose.Slides for Java API リファレンス
description: スライド上のテーブルを表します。
type: docs
url: /ja/com.aspose.slides/itable/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

スライド上のテーブルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | 指定された列と行のインデックスにあるセルを返します。 |
| [getRows()](#getRows--) | 行のコレクションを返します。 |
| [getColumns()](#getColumns--) | 列のコレクションを返します。 |
| [getTableFormat()](#getTableFormat--) | このテーブルの書式設定プロパティを含む TableFormat オブジェクトを返します。 |
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
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | 隣接するセルを結合します。 |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

指定された列と行のインデックスにあるセルを返します。読み取り専用 [ICell](../../com.aspose.slides/icell)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**戻り値:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

行のコレクションを返します。読み取り専用 [IRowCollection](../../com.aspose.slides/irowcollection)。

**戻り値:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

列のコレクションを返します。読み取り専用 [IColumnCollection](../../com.aspose.slides/icolumncollection)。

**戻り値:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

このテーブルの書式設定プロパティを含む TableFormat オブジェクトを返します。読み取り専用 [ITableFormat](../../com.aspose.slides/itableformat)。

**戻り値:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

組み込みテーブルスタイルを取得または設定します。読み書き可能 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**戻り値:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

組み込みテーブルスタイルを取得または設定します。読み書き可能 [TableStylePreset](../../com.aspose.slides/tablestylepreset)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

テーブルが右から左への読み順かどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

テーブルが右から左への読み順かどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

テーブルの最初の行が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

テーブルの最初の行が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

テーブルの最初の列が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

テーブルの最初の列が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

テーブルの最後の行が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

テーブルの最後の行が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

テーブルの最後の列が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

テーブルの最後の列が特別な書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

偶数行が異なる書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

偶数行が異なる書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

偶数列が異なる書式で描画されるかどうかを判断します。読み書き可能な boolean。

**戻り値:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

偶数列が異なる書式で描画されるかどうかを判断します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
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