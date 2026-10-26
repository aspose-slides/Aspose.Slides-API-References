---
title: IFillFormatEffectiveData
second_title: Java APIリファレンスによる Android 用 Aspose.Slides
description: 有効な塗りつぶし書式プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ifillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

有効な塗りつぶし書式プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IFillFormat](../../com.aspose.slides/ifillformat) インターフェイスと共に使用され、継承が適用された有効な書式値を返します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしの種類を返します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 塗りつぶしの色を返します。 |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | カラースキームで定義された塗りつぶしの色を取得します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶし形式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶし形式を返します。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 画像塗りつぶし形式を返します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転するかどうかを判定します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

塗りつぶしの種類を返します。読み取り専用 [FillType](../../com.aspose.slides/filltype)。

**戻り値:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

塗りつぶしの色を返します。読み取り専用 java.lang.Integer。

**戻り値:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

カラースキームで定義された塗りつぶしの色を取得します。[SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) の値は SolidFillColor (\#getSolidFillColor.getSolidFillColor) がスキームカラーでないことを示します。読み取り専用 [SchemeColor](../../com.aspose.slides/schemecolor)。

**戻り値:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

グラデーション塗りつぶし形式を返します。読み取り専用 [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)。

**戻り値:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

パターン塗りつぶし形式を返します。読み取り専用 [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)。

**戻り値:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

画像塗りつぶし形式を返します。読み取り専用 [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)。

**戻り値:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

シェイプとともに塗りつぶしが回転するかどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean