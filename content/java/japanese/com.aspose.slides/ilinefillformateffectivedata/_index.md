---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 有効な行埋めプロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ilinefillformateffectivedata/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

有効な行埋めプロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata)の一部として使用されます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしタイプを返します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 単色塗りつぶしの色を返します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶしの書式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶしの書式を返します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプと共に回転すべきかどうかを判断します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

塗りつぶしタイプを返します。読み取り専用 [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

単色塗りつぶしの色を返します。読み取り専用 java.awt.Color。

**戻り値:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

グラデーション塗りつぶしの書式を返します。読み取り専用 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**戻り値:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

パターン塗りつぶしの書式を返します。読み取り専用 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**戻り値:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

塗りつぶしがシェイプと共に回転すべきかどうかを判断します。読み取り専用 boolean。

**戻り値:**
boolean