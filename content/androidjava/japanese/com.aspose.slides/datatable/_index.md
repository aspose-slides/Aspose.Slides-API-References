---
title: DataTable
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
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
| [getFormat()](#getFormat--) | オブジェクトの線、塗りつぶし、効果スタイルを返します。 |
| [hasBorderHorizontal()](#hasBorderHorizontal--) | チャート データ テーブルに水平セル境界がある場合は true。 |
| [setBorderHorizontal(boolean value)](#setBorderHorizontal-boolean-) | チャート データ テーブルに水平セル境界がある場合は true。 |
| [hasBorderOutline()](#hasBorderOutline--) | チャート データ テーブルにアウトライン境界がある場合は true。 |
| [setBorderOutline(boolean value)](#setBorderOutline-boolean-) | チャート データ テーブルにアウトライン境界がある場合は true。 |
| [hasBorderVertical()](#hasBorderVertical--) | チャート データ テーブルに垂直セル境界がある場合は true。 |
| [setBorderVertical(boolean value)](#setBorderVertical-boolean-) | チャート データ テーブルに垂直セル境界がある場合は true。 |
| [getShowLegendKey()](#getShowLegendKey--) | データ ラベルの凡例キーが表示されている場合は true。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | データ ラベルの凡例キーが表示されている場合は true。 |
| [getChart()](#getChart--) | チャートを返します。 |
| [getTextFormat()](#getTextFormat--) | テキスト形式を返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

オブジェクトの線、塗りつぶし、効果スタイルを返します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### hasBorderHorizontal() {#hasBorderHorizontal--}
```
public final boolean hasBorderHorizontal()
```

チャート データ テーブルに水平セル境界がある場合は true。読み書き可能な boolean。

**戻り値:**
boolean
### setBorderHorizontal(boolean value) {#setBorderHorizontal-boolean-}
```
public final void setBorderHorizontal(boolean value)
```

チャート データ テーブルに水平セル境界がある場合は true。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### hasBorderOutline() {#hasBorderOutline--}
```
public final boolean hasBorderOutline()
```

チャート データ テーブルにアウトライン境界がある場合は true。読み書き可能な boolean。

**戻り値:**
boolean
### setBorderOutline(boolean value) {#setBorderOutline-boolean-}
```
public final void setBorderOutline(boolean value)
```

チャート データ テーブルにアウトライン境界がある場合は true。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### hasBorderVertical() {#hasBorderVertical--}
```
public final boolean hasBorderVertical()
```

チャート データ テーブルに垂直セル境界がある場合は true。読み書き可能な boolean。

**戻り値:**
boolean
### setBorderVertical(boolean value) {#setBorderVertical-boolean-}
```
public final void setBorderVertical(boolean value)
```

チャート データ テーブルに垂直セル境界がある場合は true。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

データ ラベルの凡例キーが表示されている場合は true。読み書き可能な boolean。

**戻り値:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

データ ラベルの凡例キーが表示されている場合は true。読み書き可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
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