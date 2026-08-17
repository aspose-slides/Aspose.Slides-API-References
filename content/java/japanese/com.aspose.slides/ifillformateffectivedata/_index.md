---
title: IFillFormatEffectiveData
second_title: Aspose.Slides for Java API リファレンス
description: 有効な塗りつぶし書式プロパティを含む不変オブジェクトです。
type: docs
url: /ja/com.aspose.slides/ifillformateffectivedata/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

有効な塗りつぶし書式プロパティを含む不変オブジェクトです。

--------------------

このインターフェイスは [IFillFormat](../../com.aspose.slides/ifillformat) インターフェイスと共に使用され、継承が適用された有効な書式設定値を返します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFillType()](#getFillType--) | 塗りつぶしのタイプを返します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 塗りつぶしカラーを返します。 |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | カラースキームで定義された塗りつぶしカラーを取得します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶし形式を返します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶし形式を返します。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 画像塗りつぶし形式を返します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしをシェイプとともに回転させるかどうかを判断します。 |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


塗りつぶしのタイプを返します。読み取り専用 [FillType](../../com.aspose.slides/filltype)。

**戻り値:**  
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


塗りつぶしカラーを返します。読み取り専用 java.awt.Color。

**戻り値:**  
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


カラースキームで定義された塗りつぶしカラーを取得します。[SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) の値は SolidFillColor (\#getSolidFillColor.getSolidFillColor) がスキームカラーではないことを示します。読み取り専用 [SchemeColor](../../com.aspose.slides/schemecolor)。

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


塗りつぶしをシェイプとともに回転させるかどうかを判断します。読み取り専用 boolean。

**戻り値:**  
boolean