---
title: FillFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر گزینه‌های قالب‌بندی پر است.
type: docs
url: /fa/com.aspose.slides/fillformat/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)
```
public final class FillFormat extends PVIObject implements IFillFormat
```

نمایانگر گزینه‌های قالب‌بندی پر است.
## متدها

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | مقدار یا تنظیم نوع پر کردن. |
| [setFillType(byte value)](#setFillType-byte-) | مقدار یا تنظیم نوع پر کردن. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر الگو را برمی‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب پر تصویر را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | مشخص می‌کند آیا پر باید همراه شکل چرخانده شود یا خیر. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | مشخص می‌کند آیا پر باید همراه شکل چرخانده شود یا خیر. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر پر را با اعمال وراثت دریافت می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. long فقط‌خواندنی.

**بازگشت:**
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

مقدار یا تنظیم نوع پر کردن. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**بازگشت:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

مقدار یا تنظیم نوع پر کردن. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

رنگ پر را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

قالب پر گرادیان را برمی‌گرداند. فقط‌خواندنی [IGradientFormat](../../com.aspose.slides/igradientformat).

**بازگشت:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

قالب پر الگو را برمی‌گرداند. فقط‌خواندنی [IPatternFormat](../../com.aspose.slides/ipatternformat).

**بازگشت:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

قالب پر تصویر را برمی‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

مشخص می‌کند آیا پر باید همراه شکل چرخانده شود یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

مشخص می‌کند آیا پر باید همراه شکل چرخانده شود یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر پر را با اعمال وراثت دریافت می‌کند.

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


**بازگشت:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).