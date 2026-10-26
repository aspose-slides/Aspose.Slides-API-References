---
title: FillFormat
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة Java
description: يمثل خيارات تنسيق التعبئة.
type: docs
url: /ar/com.aspose.slides/fillformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

يمثل خيارات تنسيق التعبئة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | تُرجع أو تُحدد نوع التعبئة. |
| [setFillType(byte value)](#setFillType-byte-) | تُرجع أو تُحدد نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | تُرجع لون التعبئة. |
| [getGradientFormat()](#getGradientFormat--) | تُرجع تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | تُرجع تنسيق تعبئة النمط. |
| [getPictureFillFormat()](#getPictureFillFormat--) | تُرجع تنسيق تعبئة الصورة. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

تُرجع أو تُحدد نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

تُرجع أو تُحدد نوع التعبئة. قراءة/كتابة [FillType](../../com.aspose.slides/filltype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

تُرجع لون التعبئة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

تُرجع تنسيق تعبئة التدرج. قراءة فقط [IGradientFormat](../../com.aspose.slides/igradientformat).

**الإرجاع:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

تُرجع تنسيق تعبئة النمط. قراءة فقط [IPatternFormat](../../com.aspose.slides/ipatternformat).

**الإرجاع:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

تُرجع تنسيق تعبئة الصورة. قراءة فقط [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**الإرجاع:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. قراءة/كتابة [NullableBool](../../com.aspose.slides/nullablebool).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق التعبئة الفعّالة مع تطبيق الوراثة.

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
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).