---
title: HtmlOptions
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: گزینه‌های خروجی HTML را نمایان می‌کند.
type: docs
url: /fa/com.aspose.slides/htmloptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

نمایانگر گزینه‌های خروجی HTML است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | یک شی HtmlOptions جدید ایجاد می‌کند که کال‌بک را مشخص می‌کند. |
| [HtmlOptions()](#HtmlOptions--) | یک شی HtmlOptions جدید ایجاد می‌کند برای ذخیره‌سازی در یک فایل HTML تک. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند خروجی کنترل می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getHtmlFormatter()](#getHtmlFormatter--) | قالب HTML را دریافت یا تنظیم می‌کند. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | قالب HTML را دریافت یا تنظیم می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [getSlideImageFormat()](#getSlideImageFormat--) | گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. |
| [getJpegQuality()](#getJpegQuality--) | مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایانگر سطح فشرده‌سازی تصاویر است |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایانگر سطح فشرده‌سازی تصاویر است |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | پرچم بولی نشان می‌دهد آیا بخش‌های برش‌داده شده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | پرچم بولی نشان می‌دهد آیا بخش‌های برش‌داده شده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | درست برای حذف ویژگی‌های width و height از کانتینر svg - این کار طرح‌بندی را واکنش‌گرا می‌کند. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | درست برای حذف ویژگی‌های width و height از کانتینر svg - این کار طرح‌بندی را واکنش‌گرا می‌کند. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

یک شی HtmlOptions جدید ایجاد می‌کند که کال‌بک را مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | شی کال‌بکی که روند ذخیره‌سازی پروژه را کنترل می‌کند. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

یک شی HtmlOptions جدید ایجاد می‌کند برای ذخیره‌سازی در یک فایل HTML تک.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
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

حالت قرارگیری اسلایدها روی صفحه را هنگام خروجی‌گیری ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) دریافت یا تنظیم می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند خروجی کنترل می‌کند. فقط‌خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

قالب HTML را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**بازگشت:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

قالب HTML را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌طور پیش‌فرض این ویژگی false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**بازگشت:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی به true تنظیم شود، لیگچرها در خروجی رندر غیرفعال می‌شوند. به‌طور پیش‌فرض این ویژگی false است.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**بازگشت:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. قابل‌خواندن/نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. قابل‌خواندن/نوشتن byte.

---
این ویژگی فقط زمانی مؤثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد که ۰ یعنی کمترین کیفیت اما بیشترین فشرده‌سازی و ۱۰۰ یعنی بالاترین کیفیت اما کمترین فشرده‌سازی.

مقدار پیش‌فرض **95** است.

**بازگشت:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. قابل‌خواندن/نوشتن byte.

---
این ویژگی فقط زمانی مؤثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند بین ۰ تا ۱۰۰ باشد که ۰ یعنی کمترین کیفیت اما بیشترین فشرده‌سازی و ۱۰۰ یعنی بالاترین کیفیت اما کمترین فشرده‌سازی.

مقدار پیش‌فرض **95** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

نمایانگر سطح فشرده‌سازی تصاویر است

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

نمایانگر سطح فشرده‌سازی تصاویر است

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

پرچم بولی نشان می‌دهد آیا بخش‌های برش داده شده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های برش داده شده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود)

**بازگشت:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

پرچم بولی نشان می‌دهد آیا بخش‌های برش داده شده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های برش داده شده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

درست برای حذف ویژگی‌های width و height از کانتینر svg - این کار طرح‌بندی را واکنش‌گرا می‌کند. نادرست در غیر این صورت. بولی قابل‌خواندن/نوشتن.

**بازگشت:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

درست برای حذف ویژگی‌های width و height از کانتینر svg - این کار طرح‌بندی را واکنش‌گرا می‌کند. نادرست در غیر این صورت. بولی قابل‌خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |