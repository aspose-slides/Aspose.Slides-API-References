---
title: FillFormat
second_title: مرجع API جاوا برای Aspose.Slides در Android
description: نمایانگر گزینه‌های قالب‌بندی پر کردن است.
type: docs
url: /fa/com.aspose.slides/fillformat/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IFillFormat](../../com.aspose.slides/ifillformat)  
```
public final class FillFormat extends PVIObject implements IFillFormat
```

نمایانگر گزینه‌های قالب‌بندی پر کردن است.
## متدها

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillType()](#getFillType--) | مقدار نوع پر کردن را برمی‌گرداند یا تنظیم می‌کند. |
| [setFillType(byte value)](#setFillType-byte-) | مقدار نوع پر کردن را برمی‌گرداند یا تنظیم می‌کند. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر شدن گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر شدن طرح را برمی‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب پر شدن تصویر را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی پر کردن مؤثر را با درنظر گرفتن ارث‌بری دریافت می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازگشت:**  
long
### getFillType() {#getFillType--}
```
public final byte getFillType()
```

مقدار نوع پر کردن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [FillType](../../com.aspose.slides/filltype).

**بازگشت:**  
byte
### setFillType(byte value) {#setFillType-byte-}
```
public final void setFillType(byte value)
```

مقدار نوع پر کردن را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [FillType](../../com.aspose.slides/filltype).

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public final IColorFormat getSolidFillColor()
```

رنگ پر کردن را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public final IGradientFormat getGradientFormat()
```

قالب پر شدن گرادیان را برمی‌گرداند. فقط‌خواندنی [IGradientFormat](../../com.aspose.slides/igradientformat).

**بازگشت:**  
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public final IPatternFormat getPatternFormat()
```

قالب پر شدن طرح را برمی‌گرداند. فقط‌خواندنی [IPatternFormat](../../com.aspose.slides/ipatternformat).

**بازگشت:**  
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public final IPictureFillFormat getPictureFillFormat()
```

قالب پر شدن تصویر را برمی‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**  
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public final byte getRotateWithShape()
```

تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**  
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public final void setRotateWithShape(byte value)
```

تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. قابل خواندن/نوشتن [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public final IFillFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی پر کردن مؤثر را با درنظر گرفتن ارث‌بری دریافت می‌کند.

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
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - یک [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).