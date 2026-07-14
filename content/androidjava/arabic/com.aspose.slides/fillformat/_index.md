---
title: FillFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خيارات تنسيق الملء.
type: docs
url: /ar/com.aspose.slides/fillformat/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)  
```
public final class FillFormat extends PVIObject implements IFillFormat
```

يمثل خيارات تنسيق الملء.  
## الطرق

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | إرجاع أو تعيين نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | إرجاع أو تعيين نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | إرجاع لون الملء. |
| [getGradientFormat()](#getGradientFormat--) | إرجاع تنسيق الملء التدرجي. |
| [getPatternFormat()](#getPatternFormat--) | إرجاع تنسيق نمط الملء. |
| [getPictureFillFormat()](#getPictureFillFormat--) | إرجاع تنسيق ملء الصورة. |
| [getRotateWithShape()](#getRotateWithShape--) | تحديد ما إذا كان يجب تدوير الملء مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تحديد ما إذا كان يجب تدوير الملء مع الشكل. |
| [getEffective()](#getEffective--) | الحصول على بيانات تنسيق الملء الفعّالة مع تطبيق الوراثة. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**  
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

إرجاع أو تعيين نوع التعبئة. للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

إرجاع أو تعيين نوع التعبئة. للقراءة والكتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

إرجاع لون الملء. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

إرجاع تنسيق الملء التدرجي. للقراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

إرجاع تنسيق نمط الملء. للقراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

إرجاع تنسيق ملء الصورة. للقراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

تحديد ما إذا كان يجب تدوير الملء مع الشكل. للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

تحديد ما إذا كان يجب تدوير الملء مع الشكل. للقراءة والكتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

الحصول على بيانات تنسيق الملء الفعّالة مع تطبيق الوراثة.

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


**الإرجاع:**  
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - أ [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).