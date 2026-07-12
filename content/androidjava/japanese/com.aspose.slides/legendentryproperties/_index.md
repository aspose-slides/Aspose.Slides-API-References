---
title: LegendEntryProperties
second_title: Aspose.Slides for Android の Java API リファレンス
description: チャートの凡例プロパティを表します。
type: docs
url: /ja/com.aspose.slides/legendentryproperties/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties), com.aspose.slides.IDOMObject
```
public class LegendEntryProperties implements ILegendEntryProperties, IDOMObject
```

チャートの凡例プロパティを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextFormat()](#getTextFormat--) | テキスト形式を返します。 |
| [getHide()](#getHide--) | 凡例エントリが非表示かどうかを判定します。 |
| [setHide(boolean value)](#setHide-boolean-) | 凡例エントリが非表示かどうかを判定します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

テキスト形式を返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getHide() {#getHide--}
```
public final boolean getHide()
```

凡例エントリが非表示かどうかを判定します。読み書き可能な boolean。

**戻り値:**
boolean
### setHide(boolean value) {#setHide-boolean-}
```
public final void setHide(boolean value)
```

凡例エントリが非表示かどうかを判定します。読み書き可能な boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)
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