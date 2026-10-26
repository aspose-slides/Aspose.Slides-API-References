---
title: FillFormat
second_title: Aspose.Slides Android için, Java API Referansı
description: Dolgu biçimlendirme seçeneklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/fillformat/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Dolgu biçimlendirme seçeneklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Dolgu türünü alır veya ayarlar. |
| [setFillType(byte value)](#setFillType-byte-) | Dolgu türünü alır veya ayarlar. |
| [getSolidFillColor()](#getSolidFillColor--) | Dolgu rengini alır. |
| [getGradientFormat()](#getGradientFormat--) | Gradyan dolgu formatını alır. |
| [getPatternFormat()](#getPatternFormat--) | Desen dolgu formatını alır. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Resim dolgu formatını alır. |
| [getRotateWithShape()](#getRotateWithShape--) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. |
| [getEffective()](#getEffective--) | Uygulanan kalıtım ile etkili dolgu biçimlendirme verilerini alır. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Sürüm. Salt okunur uzun.

**Döndürür:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Dolgu türünü alır veya ayarlar. Okunur/yazılabilir [FillType](../../com.aspose.slides/filltype).

**Döndürür:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Dolgu türünü alır veya ayarlar. Okunur/yazılabilir [FillType](../../com.aspose.slides/filltype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Dolgu rengini alır. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Gradyan dolgu formatını alır. Salt okunur [IGradientFormat](../../com.aspose.slides/igradientformat).

**Döndürür:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Desen dolgu formatını alır. Salt okunur [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Döndürür:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

Resim dolgu formatını alır. Salt okunur [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Döndürür:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Döndürür:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Okunur/yazılabilir [NullableBool](../../com.aspose.slides/nullablebool).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

Uygulanan kalıtım ile etkili dolgu biçimlendirme verilerini alır.

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


**Döndürür:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - Bir [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).