---
title: DataTable
second_title: Aspose.Slides for Java API リファレンス
description: データテーブルのプロパティを表します。
type: docs
url: /ja/com.aspose.slides/datatable/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IDataTable](../../com.aspose.slides/idatatable)  
```
public class DataTable extends DomObject<Chart> implements IDataTable
```

データテーブルのプロパティを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFormat()](#getFormat--) | オブジェクトの線、塗り、および効果スタイルを返します。 |
| [hasBorderHorizontal()](#hasBorderHorizontal--) | チャートのデータテーブルに水平セル境界線がある場合は true です。 |
| [setBorderHorizontal(boolean value)](#setBorderHorizontal-boolean-) | チャートのデータテーブルに水平セル境界線がある場合は true です。 |
| [hasBorderOutline()](#hasBorderOutline--) | チャートのデータテーブルに外枠境界線がある場合は true です。 |
| [setBorderOutline(boolean value)](#setBorderOutline-boolean-) | チャートのデータテーブルに外枠境界線がある場合は true です。 |
| [hasBorderVertical()](#hasBorderVertical--) | チャートのデータテーブルに垂直セル境界線がある場合は true です。 |
| [setBorderVertical(boolean value)](#setBorderVertical-boolean-) | チャートのデータテーブルに垂直セル境界線がある場合は true です。 |
| [getShowLegendKey()](#getShowLegendKey--) | データ ラベルの凡例キーが表示されている場合は true です。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | データ ラベルの凡例キーが表示されている場合は true です。 |
| [getChart()](#getChart--) | チャートを返します。 |
| [getTextFormat()](#getTextFormat--) | テキスト形式を返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

オブジェクトの線、塗り、および効果スタイルを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)

### hasBorderHorizontal() {#hasBorderHorizontal--}
```
public final boolean hasBorderHorizontal()
```

チャートのデータテーブルに水平セル境界線がある場合は true です。読み書き可能な boolean。

**戻り値:**
boolean

### setBorderHorizontal(boolean value) {#setBorderHorizontal-boolean-}
```
public final void setBorderHorizontal(boolean value)
```

チャートのデータテーブルに水平セル境界線がある場合は true です。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderOutline() {#hasBorderOutline--}
```
public final boolean hasBorderOutline()
```

チャートのデータテーブルに外枠境界線がある場合は true です。読み書き可能な boolean。

**戻り値:**
boolean

### setBorderOutline(boolean value) {#setBorderOutline-boolean-}
```
public final void setBorderOutline(boolean value)
```

チャートのデータテーブルに外枠境界線がある場合は true です。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### hasBorderVertical() {#hasBorderVertical--}
```
public final boolean hasBorderVertical()
```

チャートのデータテーブルに垂直セル境界線がある場合は true です。読み書き可能な boolean。

**戻り値:**
boolean

### setBorderVertical(boolean value) {#setBorderVertical-boolean-}
```
public final void setBorderVertical(boolean value)
```

チャートのデータテーブルに垂直セル境界線がある場合は true です。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

データ ラベルの凡例キーが表示されている場合は true です。読み書き可能な boolean。

**戻り値:**
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

データ ラベルの凡例キーが表示されている場合は true です。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト形式を返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)