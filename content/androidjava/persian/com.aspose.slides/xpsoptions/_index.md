---
title: XpsOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب XPS را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/xpsoptions/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

گزینه‌هایی را فراهم می‌کند که کنترل می‌کند یک ارائه چگونه در قالب XPS ذخیره شود.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // یک شیء Presentation ایجاد می‌کند که یک فایل ارائه را نمایندگی می‌کند
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // ذخیرهٔ ارائه به سند XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // یک شیء Presentation ایجاد می‌کند که یک فایل ارائه را نمایندگی می‌کند
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // ایجاد کلاس TiffOptions
>      XpsOptions options = new XpsOptions();
>      // ذخیرهٔ متافایل‌ها به صورت PNG
>      options.setSaveMetafilesAsPng(true);
>      // ذخیرهٔ ارائه به سند XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | تعیین می‌کند آیا سند تولید شده شامل اسلایدهای مخفی باشد یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | تعیین می‌کند آیا سند تولید شده شامل اسلایدهای مخفی باشد یا نه. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | درست برای رسم قاب سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | درست برای رسم قاب سیاه دور هر اسلاید. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

سازنده پیش‌فرض.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

تعیین می‌کند آیا سند تولید شده شامل اسلایدهای مخفی باشد یا نه. مقدار پیش‌فرض false است.

**بازگشت:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

تعیین می‌کند آیا سند تولید شده شامل اسلایدهای مخفی باشد یا نه. مقدار پیش‌فرض false است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

درست برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. بولی خواندنی/نوشتنی.

--------------------

مقدار پیش‌فرض **true**.

**بازگشت:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

درست برای تبدیل تمام متافایل‌های استفاده‌شده در ارائه به تصاویر PNG. بولی خواندنی/نوشتنی.

--------------------

مقدار پیش‌فرض **true**.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

درست برای رسم قاب سیاه دور هر اسلاید. بولی خواندنی/نوشتنی.

--------------------

مقدار پیش‌فرض **false**.

**بازگشت:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

درست برای رسم قاب سیاه دور هر اسلاید. بولی خواندنی/نوشتنی.

--------------------

مقدار پیش‌فرض **false**.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |