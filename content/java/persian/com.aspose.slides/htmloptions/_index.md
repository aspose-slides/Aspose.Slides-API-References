---
title: HtmlOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر گزینه‌های صادرات HTML.
type: docs
url: /fa/com.aspose.slides/htmloptions/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

نمایش‌دهنده گزینه‌های صادرات HTML است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | یک شیء HtmlOptions جدید را با تعیین callback ایجاد می‌کند. |
| [HtmlOptions()](#HtmlOptions--) | یک شیء HtmlOptions جدید را برای ذخیره‌سازی در یک فایل HTML منفرد ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کنند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. |
| [getHtmlFormatter()](#getHtmlFormatter--) | قالب HTML را دریافت یا تنظیم می‌کند. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | قالب HTML را دریافت یا تنظیم می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [getSlideImageFormat()](#getSlideImageFormat--) | گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. |
| [getJpegQuality()](#getJpegQuality--) | مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | درست برای حذف ویژگی‌های width و height از کانتینر svg - که به طراحی واکنش‌گرا منجر می‌شود. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | درست برای حذف ویژگی‌های width و height از کانتینر svg - که به طراحی واکنش‌گرا منجر می‌شود. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```


یک شیء HtmlOptions جدید را با تعیین callback ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | شیء callback که ذخیره‌سازی پروژه را کنترل می‌کند. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```


یک شیء HtmlOptions جدید را برای ذخیره‌سازی در یک فایل HTML منفرد ایجاد می‌کند.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


حالت قرارگیری اسलایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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


حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) را دریافت یا تنظیم می‌کند.

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


گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کنند. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```


قالب HTML را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**بازگشت:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```


قالب HTML را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. هنگام تنظیم به true، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی برابر false است.

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


مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. هنگام تنظیم به true، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی برابر false است.

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


گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**بازگشت:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```


گزینه‌های فرمت تصویر اسلاید را دریافت یا تنظیم می‌کند. خواندنی/قابل نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/قابل نوشتن byte.

فقط وقتی سند حاوی تصاویر JPEG باشد اثر می‌گذارد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 متغیر باشد که 0 به معنای بدترین کیفیت ولی حداکثر فشرده‌سازی و 100 به معنای بهترین کیفیت ولی حداقل فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**بازگشت:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


مقداری را دریافت یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/قابل نوشتن byte.

فقط وقتی سند حاوی تصاویر JPEG باشد اثر می‌گذارد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 متغیر باشد که 0 به معنای بدترین کیفیت ولی حداکثر فشرده‌سازی و 100 به معنای بهترین کیفیت ولی حداقل فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


سطح فشرده‌سازی تصاویر را نمایش می‌دهد

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


سطح فشرده‌سازی تصاویر را نمایش می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های برش خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که می‌تواند منجر به فایل بزرگ‌تر شود)

**بازگشت:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


یک پرچم بولی نشان می‌دهد آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد بخش‌های برش خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که می‌تواند منجر به فایل بزرگ‌تر شود)

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```


درست برای حذف ویژگی‌های width و height از کانتینر svg - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. غلط در غیر این صورت. بولی خواندنی/قابل نوشتن.

**بازگشت:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```


درست برای حذف ویژگی‌های width و height از کانتینر svg - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. غلط در غیر این صورت. بولی خواندنی/قابل نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |