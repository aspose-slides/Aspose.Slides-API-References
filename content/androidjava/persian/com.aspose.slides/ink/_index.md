---
title: Ink
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء جوهر را بر روی یک اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ink/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

نمایش می‌دهد یک شیء جوهر را در یک اسلاید.

## متدها

| Method | Description |
| --- | --- |
| [getTraces()](#getTraces--) | تمام ردهایی که در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) وجود دارند را دریافت می‌کند. |
| [getInkEffectImages()](#getInkEffectImages--) | مجموعه‌ای از تصاویر سفارشی را که برای شبیه‌سازی جلوه‌های بصری براش‌های جوهر استفاده می‌شوند، دریافت می‌کند. |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

تمام ردهایی که در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace) وجود دارند را دریافت می‌کند. فقط-خواندنی.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
com.aspose.slides.IInkTrace[]

### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

مجموعه‌ای از تصاویر سفارشی را که برای شبیه‌سازی جلوه‌های بصری براش‌های جوهر استفاده می‌شوند، دریافت می‌کند. این تصاویر هنگام رندر جوهر با مقادیر خاص [InkEffectType](../../com.aspose.slides/inkeffecttype)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با فراهم کردن تصاویر خود می‌توانید نحوه نمایش هر اثر جوهر را کنترل کنید.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

این ویژگی امکان جایگزینی بافت‌های پیش‌فرض اثر جوهر با بافت‌های تعریف‌شده توسط کاربر را فراهم می‌کند، که به‌ویژه زمانی مفید است که دارایی‌های پیش‌فرض به‌دلیل محدودیت‌های مجوز یا عدم دسترسی در زمان اجرا محدود شده باشند. هر ورودی در دیکشنری باید یک مقدار [InkEffectType](../../com.aspose.slides/inkeffecttype) را با یک شیء [IImage](../../com.aspose.slides/iimage) مربوطه (مثلاً Bitmap یا یک رابط تصویر Aspose) مرتبط کند.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>