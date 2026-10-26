---
title: ILineFillFormatEffectiveData
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 有効な行塗りつぶしプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ilinefillformateffectivedata/
---
**実装されたすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

効果的な行塗りつぶしプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしタイプを返します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 単色塗りつぶしの色を返します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶし形式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶし形式を返します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転すべきかどうかを判定します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

塗りつぶしタイプを返します。 読み取り専用 [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

単色塗りつぶしの色を返します。 読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

グラデーション塗りつぶし形式を返します。 読み取り専用 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**戻り値:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

パターン塗りつぶし形式を返します。 読み取り専用 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**戻り値:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

塗りつぶしがシェイプとともに回転すべきかどうかを判定します。 読み取り専用 boolean。

**戻り値:**
boolean