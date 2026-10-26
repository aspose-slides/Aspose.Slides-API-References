---
title: CommonSlideViewProperties
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش ویژگی‌های عمومی اسلاید را توصیف می‌کند.
type: docs
url: /fa/com.aspose.slides/commonslideviewproperties/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های اجرا شده:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

نمایش عمومی اسلاید را توصیف می‌کند.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است، ایجاد کنید
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // تنظیم ویژگی‌های نمای ارائه
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // مقدار زوم به درصد برای نمای اسلاید
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // مقدار زوم به درصد برای نمای یادداشت‌ها
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getScale()](#getScale--) | نسبت مقیاس نمایی را برحسب درصد مشخص می‌کند. |
| [setScale(int value)](#setScale-int-) | نسبت مقیاس نمایی را برحسب درصد مشخص می‌کند. |
| [getVariableScale()](#getVariableScale--) | مشخص می‌کند که محتوای نمایی به‌طور خودکار برای مناسب‌ترین اندازه پنجره فعلی مقیاس شود. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | مشخص می‌کند که محتوای نمایی به‌طور خودکار برای مناسب‌ترین اندازه پنجره فعلی مقیاس شود. |
| [getDrawingGuides()](#getDrawingGuides--) | مجموعه راهنمای رسم را برمی‌گرداند. |
### getScale() {#getScale--}
```
public final int getScale()
```

نسبت مقیاس نمایی را برحسب درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**بازگشت:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

نسبت مقیاس نمایی را برحسب درصد مشخص می‌کند. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

مشخص می‌کند که محتوای نمایی به‌طور خودکار برای مناسب‌ترین اندازه پنجره فعلی مقیاس شود. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

مشخص می‌کند که محتوای نمایی به‌طور خودکار برای مناسب‌ترین اندازه پنجره فعلی مقیاس شود. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

مجموعه راهنمای رسم را برمی‌گرداند. فقط-خواندنی [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // افزودن راهنمای رسم عمودی جدید به سمت راست مرکز اسلاید
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // افزودن راهنمای رسم افقی جدید زیر مرکز اسلاید
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)