---
title: FillFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili opsi pemformatan pengisian.
type: docs
url: /id/com.aspose.slides/fillformat/
---
**Pewarisan:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)  
```
public final class FillFormat extends PVIObject implements IFillFormat
```

Mewakili opsi pemformatan pengisian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | Mengembalikan atau mengatur tipe pengisian. |
| [setFillType(byte value)](#setFillType-byte-) | Mengembalikan atau mengatur tipe pengisian. |
| [getSolidFillColor()](#getSolidFillColor--) | Mengembalikan warna pengisian. |
| [getGradientFormat()](#getGradientFormat--) | Mengembalikan format pengisian gradien. |
| [getPatternFormat()](#getPatternFormat--) | Mengembalikan format pengisian pola. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Mengembalikan format pengisian gambar. |
| [getRotateWithShape()](#getRotateWithShape--) | Menentukan apakah pengisian harus diputar bersama bentuk. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | Menentukan apakah pengisian harus diputar bersama bentuk. |
| [getEffective()](#getEffective--) | Mendapatkan data format pengisian yang efektif dengan pewarisan yang diterapkan. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

Mengembalikan atau mengatur tipe pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Mengembalikan:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

Mengembalikan atau mengatur tipe pengisian. Baca/tulis [FillType](../../com.aspose.slides/filltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

Mengembalikan warna pengisian. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

Mengembalikan format pengisian gradien. Baca-saja [IGradientFormat](../../com.aspose.slides/igradientformat).

**Mengembalikan:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

Mengembalikan format pengisian pola. Baca-saja [IPatternFormat](../../com.aspose.slides/ipatternformat).

**Mengembalikan:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

Mengembalikan format pengisian gambar. Baca-saja [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

Menentukan apakah pengisian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

Menentukan apakah pengisian harus diputar bersama bentuk. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

Mendapatkan data format pengisian yang efektif dengan pewarisan yang diterapkan.

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

**Mengembalikan:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).