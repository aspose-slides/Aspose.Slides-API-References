---
title: TiffOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه در قالب TIFF را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/tiffoptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های اجرا شده:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // ذخیره ارائه به صورت سند TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // یک شی از کلاس TiffOptions ایجاد می‌کند
>      TiffOptions opts = new TiffOptions();
>      // تنظیم نوع فشرده‌سازی
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // انواع فشرده‌سازی
>      // پیش‌فرض - طرح فشرده‌سازی پیش‌فرض (LZW) را مشخص می‌کند.
>      // هیچ‌کدام - عدم فشرده‌سازی را مشخص می‌کند.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // عمق وابسته به نوع فشرده‌سازی است و نمی‌تواند به‌صورت دستی تنظیم شود.
>      // واحد وضوح همیشه برابر 2 (نقطه بر اینچ) است.
>      // تنظیم DPI تصویر
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // تنظیم اندازه تصویر
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // ذخیره ارائه به صورت TIFF با اندازه تصویر مشخص شده
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // یک شی Presentation ایجاد می‌کند که نمایانگر یک فایل ارائه است
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat شامل مقادیر زیر است (همان‌طور که در مستندات دیده می‌شود):
>      //Format1bppIndexed; // 1 بیت در هر پیکسل، ایندکس شده.
>      //Format4bppIndexed; // 4 بیت در هر پیکسل، ایندکس شده.
>      //Format8bppIndexed; // 8 بیت در هر پیکسل، ایندکس شده.
>      //Format24bppRgb; // 24 بیت در هر پیکسل، RGB.
>      //Format32bppArgb; // 32 بیت در هر پیکسل، ARGB.
> 
>      // ذخیره ارائه به صورت TIFF با اندازه تصویر مشخص شده
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## سازندگان

| سازنده | توضیح |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | سازنده پیش‌فرض. |
## متدها

| متد | توضیح |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getImageSize()](#getImageSize--) | اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. |
| [getDpiX()](#getDpiX--) | وضوح افقی را بر حسب نقطه بر اینچ مشخص می‌کند. |
| [setDpiX(long value)](#setDpiX-long-) | وضوح افقی را بر حسب نقطه بر اینچ مشخص می‌کند. |
| [getDpiY()](#getDpiY--) | وضوح عمودی را بر حسب نقطه بر اینچ مشخص می‌کند. |
| [setDpiY(long value)](#setDpiY-long-) | وضوح عمودی را بر حسب نقطه بر اینچ مشخص می‌کند. |
| [getCompressionType()](#getCompressionType--) | نوع فشرده‌سازی را مشخص می‌کند. |
| [setCompressionType(int value)](#setCompressionType-int-) | نوع فشرده‌سازی را مشخص می‌کند. |
| [getPixelFormat()](#getPixelFormat--) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

سازنده پیش‌فرض.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است اندازه تصاویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شود. خواندن/نوشتن [Size](../../com.aspose.slides.android/size).

**بازگشت:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است اندازه تصاویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه می‌شود. خواندن/نوشتن [Size](../../com.aspose.slides.android/size).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

وضوح افقی را بر حسب نقطه بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**بازگشت:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

وضوح افقی را بر حسب نقطه بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

وضوح عمودی را بر حسب نقطه بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**بازگشت:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

وضوح عمودی را بر حسب نقطه بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

نوع فشرده‌سازی را مشخص می‌کند. خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**بازگشت:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

نوع فشرده‌سازی را مشخص می‌کند. خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**بازگشت:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادر کردن یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```

الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که نوع فشرده‌سازی ({{#getCompressionType.getCompressionType}}/{{#setCompressionType(int).setCompressionType(int)}}) برابر [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) باشد. خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**بازگشت:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه-سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که نوع فشرده‌سازی ({{#getCompressionType.getCompressionType}}/{{#setCompressionType(int).setCompressionType(int)}}) برابر [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) باشد. خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |