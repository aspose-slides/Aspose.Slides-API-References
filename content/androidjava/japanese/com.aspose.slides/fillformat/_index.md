---
title: FillFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 塗りつぶし書式オプションを表します。
type: docs
url: /ja/com.aspose.slides/fillformat/
---
**継承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

塗りつぶし書式オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | 塗りつぶしのタイプを取得または設定します。 |
| [setFillType(byte value)](#setFillType-byte-) | 塗りつぶしのタイプを取得または設定します。 |
| [getSolidFillColor()](#getSolidFillColor--) | 塗りつぶしの色を取得します。 |
| [getGradientFormat()](#getGradientFormat--) | グラデーション塗りつぶし形式を取得します。 |
| [getPatternFormat()](#getPatternFormat--) | パターン塗りつぶし形式を取得します。 |
| [getPictureFillFormat()](#getPictureFillFormat--) | 画像塗りつぶし形式を取得します。 |
| [getRotateWithShape()](#getRotateWithShape--) | 塗りつぶしがシェイプとともに回転するかどうかを決定します。 |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | 塗りつぶしがシェイプとともに回転するかどうかを決定します。 |
| [getEffective()](#getEffective--) | 継承が適用された実効的な塗りつぶし書式データを取得します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long.

**戻り値:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

塗りつぶしのタイプを取得または設定します。読み取り/書き込み [FillType](../../com.aspose.slides/filltype).

**戻り値:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

塗りつぶしのタイプを取得または設定します。読み取り/書き込み [FillType](../../com.aspose.slides/filltype).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

塗りつぶしの色を取得します。読み取り専用 [IColorFormat](../../com.aspose.slides/icolorformat).

**戻り値:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

グラデーション塗りつぶし形式を取得します。読み取り専用 [IGradientFormat](../../com.aspose.slides/igradientformat).

**戻り値:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

パターン塗りつぶし形式を取得します。読み取り専用 [IPatternFormat](../../com.aspose.slides/ipatternformat).

**戻り値:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

画像塗りつぶし形式を取得します。読み取り専用 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**戻り値:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

塗りつぶしがシェイプとともに回転するかどうかを決定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**戻り値:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

塗りつぶしがシェイプとともに回転するかどうかを決定します。読み取り/書き込み [NullableBool](../../com.aspose.slides/nullablebool).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

継承が適用された実効的な塗りつぶし書式データを取得します。

--------------------

> ```
> This example demonstrates getting shape's effective fill format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IFillFormatEffectiveData effectiveFillFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getFillFormat().getEffective();
>  	System.out.println("Type: " + effectiveFillFormat.getFillType());
>  	switch (effectiveFillFormat.getFillType())
>  	{
>  		case FillType.Solid:
>  			System.out.println("Fill color: " + effectiveFillFormat.getSolidFillColor());
>  			break;
>  		case FillType.Pattern:
>  			System.out.println("Pattern style: " + effectiveFillFormat.getPatternFormat().getPatternStyle());
>  			System.out.println("Fore color: " + effectiveFillFormat.getPatternFormat().getForeColor());
>  			System.out.println("Back color: " + effectiveFillFormat.getPatternFormat().getBackColor());
>  			break;
>  		case FillType.Gradient:
>  			System.out.println("Gradient direction: " + effectiveFillFormat.getGradientFormat().getGradientDirection());
>  			System.out.println("Gradient stops count: " + effectiveFillFormat.getGradientFormat().getGradientStops().size());
>  			break;
>  		case FillType.Picture:
>  			System.out.println("Picture width: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getWidth());
>  			System.out.println("Picture height: " + effectiveFillFormat.getPictureFillFormat().getPicture().getImage().getHeight());
>  			break;
>  	}
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).