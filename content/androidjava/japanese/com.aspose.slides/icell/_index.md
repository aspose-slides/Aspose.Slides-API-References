---
title: ICell
second_title: Aspose.Slides for Android の Java API リファレンス
description: テーブル内のセルを表します。
type: docs
url: /ja/com.aspose.slides/icell/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

テーブル内のセルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | テーブルの左端からセルの左端までの距離を返します。 |
| [getOffsetY()](#getOffsetY--) | テーブルの上端からセルの上端までの距離を返します。 |
| [getFirstRowIndex()](#getFirstRowIndex--) | セルがカバーする最初の行のインデックスを返します。 |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | セルがカバーする最初の列のインデックスを返します。 |
| [getWidth()](#getWidth--) | セルの幅を返します。 |
| [getHeight()](#getHeight--) | セルの高さを返します。 |
| [getMinimalHeight()](#getMinimalHeight--) | セルの最小高さを返します。 |
| [getMarginLeft()](#getMarginLeft--) | TextFrame の左余白を取得または設定します。 |
| [setMarginLeft(double value)](#setMarginLeft-double-) | TextFrame の左余白を取得または設定します。 |
| [getMarginRight()](#getMarginRight--) | TextFrame の右余白を取得または設定します。 |
| [setMarginRight(double value)](#setMarginRight-double-) | TextFrame の右余白を取得または設定します。 |
| [getMarginTop()](#getMarginTop--) | TextFrame の上余白を取得または設定します。 |
| [setMarginTop(double value)](#setMarginTop-double-) | TextFrame の上余白を取得または設定します。 |
| [getMarginBottom()](#getMarginBottom--) | TextFrame の下余白を取得または設定します。 |
| [setMarginBottom(double value)](#setMarginBottom-double-) | TextFrame の下余白を取得または設定します。 |
| [getTextVerticalType()](#getTextVerticalType--) | 縦書きテキストのタイプを取得または設定します。 |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | 縦書きテキストのタイプを取得または設定します。 |
| [getTextAnchorType()](#getTextAnchorType--) | テキストアンカーのタイプを取得または設定します。 |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | テキストアンカーのタイプを取得または設定します。 |
| [getAnchorCenter()](#getAnchorCenter--) | テキストボックスがセル内で中央揃えかどうかを判定します。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | テキストボックスがセル内で中央揃えかどうかを判定します。 |
| [getFirstColumn()](#getFirstColumn--) | セルの最初の列を取得します。 |
| [getFirstRow()](#getFirstRow--) | セルの最初の行を取得します。 |
| [getColSpan()](#getColSpan--) | 現在のセルが跨ぐ、親テーブルのテーブルグリッド内の列数を返します。 |
| [getRowSpan()](#getRowSpan--) | 結合されたセルが跨ぐ行数を返します。 |
| [getTextFrame()](#getTextFrame--) | セルのテキストフレームを返します。 |
| [getTable()](#getTable--) | セルの親 Table オブジェクトを返します。 |
| [isMergedCell()](#isMergedCell--) | セルが調整されたセルと結合されている場合は true、そうでなければ false を返します。 |
| [getCellFormat()](#getCellFormat--) | このセルの書式設定プロパティを含む CellFormat オブジェクトを返します。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 列インデックスでセルを 2 つに分割します。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 行インデックスでセルを 2 つに分割します。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 高さでセルを分割します。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 幅でセルを分割します。 |

### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```


テーブルの左端からセルの左端までの距離を返します。読み取り専用 double.

**戻り値:**
double

### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```


テーブルの上端からセルの上端までの距離を返します。読み取り専用 double.

**戻り値:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```


セルがカバーする最初の行のインデックスを返します。読み取り専用 int.

**戻り値:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```


セルがカバーする最初の列のインデックスを返します。読み取り専用 int.

**戻り値:**
int

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


セルの幅を返します。読み取り専用 double.

**戻り値:**
double

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


セルの高さを返します。読み取り専用 double.

**戻り値:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


セルの最小高さを返します。これはセルがカバーするすべての行の最小高さの合計です。読み取り専用 double.

**戻り値:**
double

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


TextFrame の左余白を取得または設定します。読み書き可能 double.

**戻り値:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


TextFrame の左余白を取得または設定します。読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


TextFrame の右余白を取得または設定します。読み書き可能 double.

**戻り値:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


TextFrame の右余白を取得または設定します。読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


TextFrame の上余白を取得または設定します。読み書き可能 double.

**戻り値:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


TextFrame の上余白を取得または設定します。読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


TextFrame の下余白を取得または設定します。読み書き可能 double.

**戻り値:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


TextFrame の下余白を取得または設定します。読み書き可能 double.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


縦書きテキストのタイプを取得または設定します。読み書き可能 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**戻り値:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


縦書きテキストのタイプを取得または設定します。読み書き可能 [TextVerticalType](../../com.aspose.slides/textverticaltype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```


テキストアンカーのタイプを取得または設定します。読み書き可能 [TextAnchorType](../../com.aspose.slides/textanchortype).

**戻り値:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```


テキストアンカーのタイプを取得または設定します。読み書き可能 [TextAnchorType](../../com.aspose.slides/textanchortype).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```


テキストボックスがセル内で中央揃えかどうかを判定します。読み書き可能 boolean.

**戻り値:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```


テキストボックスがセル内で中央揃えかどうかを判定します。読み書き可能 boolean.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```


セルの最初の列を取得します。読み取り専用 [IColumn](../../com.aspose.slides/icolumn).

**戻り値:**
[IColumn](../../com.aspose.slides/icolumn)

### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```


セルの最初の行を取得します。読み取り専用 [IRow](../../com.aspose.slides/irow).

**戻り値:**
[IRow](../../com.aspose.slides/irow)

### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```


現在のセルが跨ぐ、親テーブルのテーブルグリッド内の列数を返します。このプロパティにより、セルはテーブル内の他のセルの垂直境界を跨ぐことで結合されたように見えるようになります。読み取り専用 int.

**戻り値:**
int

### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```


結合されたセルが跨ぐ行数を返します。この属性は他のセルの vMerge と組み合わせて水平結合の開始セルを指定するために使用されます。読み取り専用 int.

**戻り値:**
int

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


セルのテキストフレームを返します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe).

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public abstract ITable getTable()
```


セルの親 Table オブジェクトを返します。読み取り専用 [ITable](../../com.aspose.slides/itable).

**戻り値:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```


セルが調整されたセルと結合されている場合は true、そうでなければ false を返します。読み取り専用 boolean.

**戻り値:**
boolean

### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```


このセルの書式設定プロパティを含む CellFormat オブジェクトを返します。読み取り専用 [ICellFormat](../../com.aspose.slides/icellformat).

**戻り値:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```


列インデックスでセルを 2 つに分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 列のインデックス。 |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```


行インデックスでセルを 2 つに分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 行のインデックス。 |

### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```


高さでセルを分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| height | double | 行の高さ。 |

### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```


幅でセルを分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | double | 列の幅。 |