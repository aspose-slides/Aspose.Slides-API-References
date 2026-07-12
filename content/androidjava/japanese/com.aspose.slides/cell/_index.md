---
title: Cell
second_title: Aspose.Slides for Android の Java API リファレンス
description: テーブルのセルを表します。
type: docs
url: /ja/com.aspose.slides/cell/
---
**継承:**
java.lang.Object

**すべての実装インターフェイス:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

テーブルのセルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | テーブルの左側からセルの左側までの距離を返します。 |
| [getOffsetY()](#getOffsetY--) | テーブルの上側からセルの上側までの距離を返します。 |
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
| [getAnchorCenter()](#getAnchorCenter--) | テキスト ボックスがセル内で中央揃えかどうかを判定します。 |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | テキスト ボックスがセル内で中央揃えかどうかを判定します。 |
| [getFirstRow()](#getFirstRow--) | セルの最初の行を取得します。 |
| [getFirstColumn()](#getFirstColumn--) | セルの最初の列を取得します。 |
| [getColSpan()](#getColSpan--) | 現在のセルが跨ぐ、親テーブルのテーブルグリッド内の列数を返します。 |
| [getRowSpan()](#getRowSpan--) | 結合されたセルが跨ぐ行数を返します。 |
| [getTextFrame()](#getTextFrame--) | セルのテキストフレームを返します。 |
| [getTable()](#getTable--) | セルの親 Table オブジェクトを返します。 |
| [isMergedCell()](#isMergedCell--) | セルが調整されたセルと結合されている場合は true、そうでない場合は false を返します。 |
| [getCellFormat()](#getCellFormat--) | このセルの書式設定プロパティを含む CellFormat オブジェクトを返します。 |
| [splitByColSpan(int index)](#splitByColSpan-int-) | 列のインデックスでセルを 2 つに分割します。 |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | 行のインデックスでセルを 2 つに分割します。 |
| [splitByHeight(double height)](#splitByHeight-double-) | 高さでセルを分割します。 |
| [splitByWidth(double width)](#splitByWidth-double-) | 幅でセルを分割します。 |
| [getSlide()](#getSlide--) | セルの親スライドを返します。 |
| [getPresentation()](#getPresentation--) | セルの親プレゼンテーションを返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

テーブルの左側からセルの左側までの距離を返します。読み取り専用 double。

**戻り値:**
double

### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

テーブルの上側からセルの上側までの距離を返します。読み取り専用 double。

**戻り値:**
double

### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

セルがカバーする最初の行のインデックスを返します。読み取り専用 int。

**戻り値:**
int

### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

セルがカバーする最初の列のインデックスを返します。読み取り専用 int。

**戻り値:**
int

### getWidth() {#getWidth--}
```
public final double getWidth()
```

セルの幅を返します。読み取り専用 double。

**戻り値:**
double

### getHeight() {#getHeight--}
```
public final double getHeight()
```

セルの高さを返します。読み取り専用 double。

**戻り値:**
double

### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

セルの最小高さを返します。これはセルがカバーするすべての行の最小高さの合計です。読み取り専用 double。

**戻り値:**
double

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

TextFrame の左余白を取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

TextFrame の左余白を取得または設定します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

TextFrame の右余白を取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

TextFrame の右余白を取得または設定します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

TextFrame の上余白を取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

TextFrame の上余白を取得または設定します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

TextFrame の下余白を取得または設定します。読み取り/書き込み double。

**戻り値:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

TextFrame の下余白を取得または設定します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

縦書きテキストのタイプを取得または設定します。読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**戻り値:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

縦書きテキストのタイプを取得または設定します。読み取り/書き込み [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

テキストアンカーのタイプを取得または設定します。読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype)。

**戻り値:**
byte

### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

テキストアンカーのタイプを取得または設定します。読み取り/書き込み [TextAnchorType](../../com.aspose.slides/textanchortype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

テキスト ボックスがセル内で中央揃えかどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

テキスト ボックスがセル内で中央揃えかどうかを判定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

セルの最初の行を取得します。読み取り専用 [IRow](../../com.aspose.slides/irow)。

**戻り値:**
[IRow](../../com.aspose.slides/irow)

### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

セルの最初の列を取得します。読み取り専用 [IColumn](../../com.aspose.slides/icolumn)。

**戻り値:**
[IColumn](../../com.aspose.slides/icolumn)

### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

現在のセルが跨ぐ、親テーブルのテーブルグリッド内の列数を返します。読み取り専用 int。

**戻り値:**
int

### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

結合されたセルが跨ぐ行数を返します。読み取り専用 int。

**戻り値:**
int

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

セルのテキストフレームを取得します。読み取り専用 [ITextFrame](../../com.aspose.slides/itextframe)。

**戻り値:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTable() {#getTable--}
```
public final ITable getTable()
```

セルの親 Table オブジェクトを返します。読み取り専用 [ITable](../../com.aspose.slides/itable)。

**戻り値:**
[ITable](../../com.aspose.slides/itable)

### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

セルが調整されたセルと結合されているかどうかを示す true/false を返します。読み取り専用 boolean。

**戻り値:**
boolean

### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

このセルの書式設定プロパティを含む CellFormat オブジェクトを返します。読み取り専用 [ICellFormat](../../com.aspose.slides/icellformat)。

**戻り値:**
[ICellFormat](../../com.aspose.slides/icellformat)

### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

列のインデックスでセルを 2 つに分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 列のインデックス。 |

### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

行のインデックスでセルを 2 つに分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 行のインデックス。 |

### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

高さでセルを分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| height | double | 行の高さ。 |

### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

幅でセルを分割します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | double | 列の幅。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

セルの親スライドを取得します。読み取り専用 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

セルの親プレゼンテーションを取得します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを取得します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject