---
title: XpsOptions
second_title: مرجع API Aspose.Slides برای Java
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیرهٔ یک ارائه در قالب XPS را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/xpsoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیرهٔ ارائه در قالب XPS را کنترل می‌کند.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است، ایجاد کنید
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
>  // یک شیء Presentation را که نمایانگر یک فایل ارائه است، ایجاد کنید
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // یک شیء از کلاس TiffOptions ایجاد کنید
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
| [XpsOptions()](#XpsOptions--) | سازندهٔ پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | درست برای رسم قاب سیاه دور هر اسلاید. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | درست برای رسم قاب سیاه دور هر اسلاید. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

سازندهٔ پیش‌فرض.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**برمی‌گرداند:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. بولی خواندنی/قابل نوشتن.

--------------------

پیش‌فرض **true** است.

**برمی‌گرداند:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

درست برای تبدیل تمام متافایل‌های استفاده‌شده در یک ارائه به تصاویر PNG. بولی خواندنی/قابل نوشتن.

--------------------

پیش‌فرض **true** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

درست برای رسم قاب سیاه دور هر اسلاید. بولی خواندنی/قابل نوشتن.

--------------------

پیش‌فرض **false** است.

**برمی‌گرداند:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

درست برای رسم قاب سیاه دور هر اسلاید. بولی خواندنی/قابل نوشتن.

--------------------

پیش‌فرض **false** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |