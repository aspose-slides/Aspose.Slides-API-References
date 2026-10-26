---
title: CommonSlideViewProperties
second_title: مرجع API Aspose.Slides برای Java
description: ویژگی‌های عمومی نمای اسلاید را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/commonslideviewproperties/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

نمایش ویژگی‌های عمومی اسلاید را نشان می‌دهد.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // یک شیء Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // تنظیم ویژگی‌های نمای ارائه
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // مقدار بزرگ‌نمایی به درصد برای نمای اسلاید
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // مقدار بزرگ‌نمایی به درصد برای نمای یادداشت‌ها
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getScale()](#getScale--) | نسبت مقیاس نمایش را به درصد مشخص می‌کند. |
| [setScale(int value)](#setScale-int-) | نسبت مقیاس نمایش را به درصد مشخص می‌کند. |
| [getVariableScale()](#getVariableScale--) | مشخص می‌کند که محتوای نمایش باید به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ جاری مقیاس‌بندی شود. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | مشخص می‌کند که محتوای نمایش باید به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ جاری مقیاس‌بندی شود. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعهٔ راهنمای‌های رسم را برمی‌گرداند. |

### getScale() {#getScale--}
```
public final int getScale()
```

نسبت مقیاس نمایش را به درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**باز می‌گرداند:**
int

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

نسبت مقیاس نمایش را به درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

مشخص می‌کند که محتوای نمایش باید به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ جاری مقیاس‌بندی شود. قابل خواندن/نوشتن boolean.

**باز می‌گرداند:**
boolean

### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

مشخص می‌کند که محتوای نمایش باید به‌طور خودکار برای بهترین تناسب با اندازهٔ پنجرهٔ جاری مقیاس‌بندی شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

مجموعهٔ راهنمای‌های رسم را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // افزودن راهنمای عمودی جدید به سمت راست مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // افزودن راهنمای افقی جدید زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**باز می‌گرداند:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)