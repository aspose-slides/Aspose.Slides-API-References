---
title: Ink
second_title: مرجع API Aspose.Slides برای Java
description: یک شیء جوهر را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ink/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

یک شیء جوهر را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [getTraces()](#getTraces--) | دریافت تمام ردپاهای موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | دریافت مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات تصویری قلم‌موهای جوهر استفاده می‌شوند. |

### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

دریافت تمام ردپاهای موجود در عنصر IInk [IInkTrace](../../com.aspose.slides/iinktrace). فقط‌خواندنی.

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


**بازگشت:**
com.aspose.slides.IInkTrace[]

### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

دریافت مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات تصویری قلم‌موهای جوهر استفاده می‌شوند. این تصاویر هنگام رندر کردن جوهر با مقادیر خاص [InkEffectType](../../com.aspose.slides/inkeffecttype)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با فراهم کردن تصاویر خودتان می‌توانید کنترل کنید که هر اثر جوهر چگونه ظاهر شود.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

این ویژگی امکان جایگزینی بافت‌های پیش‌فرض اثر جوهر را با بافت‌های تعریف‌شده توسط کاربر فراهم می‌کند، که به‌ویژه زمانی مفید است که دارایی‌های پیش‌فرض به دلیل مجوز محدود شوند یا در زمان اجرا در دسترس نباشند. هر ورودی در دیکشنری باید مقدار [InkEffectType](../../com.aspose.slides/inkeffecttype) را با شیء [IImage](../../com.aspose.slides/iimage) متناظر (مثلاً Bitmap یا یک رابط تصویر Aspose) مرتبط سازد.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>