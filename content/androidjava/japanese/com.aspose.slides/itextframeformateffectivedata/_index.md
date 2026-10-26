---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /ja/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

実効的なテキストフレームの書式設定プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは、[ITextFrameFormat](../../com.aspose.slides/itextframeformat) インターフェイスと組み合わせて、継承が適用された実効的な書式設定値を返すために使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | 実効的なテキストのスタイルを返します。 |
| [getMarginLeft()](#getMarginLeft--) | TextFrame の左余白（ポイント）を返します。 |
| [getMarginRight()](#getMarginRight--) | TextFrame の右余白（ポイント）を返します。 |
| [getMarginTop()](#getMarginTop--) | TextFrame の上余白（ポイント）を返します。 |
| [getMarginBottom()](#getMarginBottom--) | TextFrame の下余白（ポイント）を返します。 |
| [getWrapText()](#getWrapText--) | TextFrame の余白でテキストが折り返されるかどうかを返します。 |
| [getAnchoringType()](#getAnchoringType--) | TextFrame の縦方向アンカー テキストを返します。 |
| [getCenterText()](#getCenterText--) | テキストがボックス内で横方向に中央揃えにすべきかどうかを返します。 |
| [getTextVerticalType()](#getTextVerticalType--) | テキストの向きを返します。 |
| [getAutofitType()](#getAutofitType--) | テキストの自動フィットモードを返します。 |
| [getColumnCount()](#getColumnCount--) | バウンディング矩形内のテキスト列数を指定します。 |
| [getColumnSpacing()](#getColumnSpacing--) | テキスト領域内のテキスト列間のスペース（ポイント）を指定します。 |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

実効的なテキストのスタイルを返します。読み取り専用 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。

**戻り値:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

TextFrame の左余白（ポイント）を返します。読み取り専用 double。

**戻り値:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

TextFrame の右余白（ポイント）を返します。読み取り専用 double。

**戻り値:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

TextFrame の上余白（ポイント）を返します。読み取り専用 double。

**戻り値:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

TextFrame の下余白（ポイント）を返します。読み取り専用 double。

**戻り値:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

TextFrame の余白でテキストが折り返されるかどうかを返します。読み取り専用 boolean。

**戻り値:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

TextFrame の縦方向アンカー テキストを返します。読み取り専用 [TextAnchorType](../../com.aspose.slides/textanchortype)。

**戻り値:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

テキストがボックス内で横方向に中央揃えにすべきかどうかを返します。読み取り専用 boolean。

**戻り値:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

テキストの向きを返します。読み取り専用 [TextVerticalType](../../com.aspose.slides/textverticaltype)。

**戻り値:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

テキストの自動フィットモードを返します。読み取り専用 [TextAutofitType](../../com.aspose.slides/textautofittype)。

**戻り値:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

バウンディング矩形内のテキスト列数を指定します。読み取り専用 int。

**戻り値:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

テキスト領域内のテキスト列間のスペース（ポイント）を指定します。読み取り専用 float。

**戻り値:**
float