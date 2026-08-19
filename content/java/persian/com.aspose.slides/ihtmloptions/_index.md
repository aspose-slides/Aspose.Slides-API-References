---
title: IHtmlOptions
second_title: مرجع API Aspose.Slides برای Java
description: نمایش‌دهنده گزینه‌های صادرات HTML.
type: docs
url: /fa/com.aspose.slides/ihtmloptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

نمایش‌دهنده گزینه‌های صادرات HTML.
## متدها

| متد | توضیح |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | بازگرداندن یا تنظیم قالب HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | بازگرداندن یا تنظیم قالب HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | بازگرداندن یا تنظیم گزینه‌های قالب تصویر اسلاید. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | بازگرداندن یا تنظیم گزینه‌های قالب تصویر اسلاید. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. |
| [getJpegQuality()](#getJpegQuality--) | بازگرداندن یا تنظیم مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | بازگرداندن یا تنظیم مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | نمایش‌دهنده سطح فشرده‌سازی تصاویر. خواندنی/قابِل نوشتن [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | نمایش‌دهنده سطح فشرده‌سازی تصاویر. خواندنی/قابِل نوشتن [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | درست برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که لایه‌بندی را واکنش‌گرا می‌کند. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | درست برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که لایه‌بندی را واکنش‌گرا می‌کند. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | ارائه گزینه‌ها برای کنترل ظاهر اشیاء Ink در سند صادرشده. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```


بازگرداندن یا تنظیم قالب HTML. خواندنی/قابِل نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**بازگشت:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```


بازگرداندن یا تنظیم قالب HTML. خواندنی/قابِل نوشتن [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```


بازگرداندن یا تنظیم گزینه‌های قالب تصویر اسلاید. خواندنی/قابِل نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**بازگشت:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```


بازگرداندن یا تنظیم گزینه‌های قالب تصویر اسلاید. خواندنی/قابِل نوشتن [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا خیر. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


بازگرداندن یا تنظیم مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF. خواندنی/قابِل نوشتن byte.

--------------------

فقط زمانی موثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره‌سازی در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای پایین‌ترین کیفیت ولی بیشترین فشرده‌سازی و 100 به معنای بالاترین کیفیت ولی کمترین فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**بازگشت:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


بازگرداندن یا تنظیم مقدار تعیین‌کننده کیفیت تصاویر JPEG داخل سند PDF. خواندنی/قابِل نوشتن byte.

--------------------

فقط زمانی موثر است که سند شامل تصاویر JPEG باشد.

از این ویژگی برای دریافت یا تنظیم کیفیت تصاویر داخل سند هنگام ذخیره‌سازی در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای پایین‌ترین کیفیت ولی بیشترین فشرده‌سازی و 100 به معنای بالاترین کیفیت ولی کمترین فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


نمایش‌دهنده سطح فشرده‌سازی تصاویر. خواندنی/قابِل نوشتن [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**بازگشت:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


نمایش‌دهنده سطح فشرده‌سازی تصاویر. خواندنی/قابِل نوشتن [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. اگر true باشد بخش‌های برش‌خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود) خواندنی/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


پرچم بولی نشان می‌دهد آیا بخش‌های برش‌خورده به عنوان بخشی از سند باقی می‌مانند یا خیر. اگر true باشد بخش‌های برش‌خورده حذف می‌شوند، اگر false باشند در سند سریال‌سازی می‌شوند (که ممکن است منجر به فایل بزرگتر شود) خواندنی/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```


درست برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که لایه‌بندی را واکنش‌گرا می‌کند. False - در غیر این صورت. خواندنی/قابِل نوشتن boolean.

**بازگشت:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```


درست برای حذف ویژگی‌های عرض و ارتفاع از محفظه SVG - که لایه‌بندی را واکنش‌گرا می‌کند. False - در غیر این صورت. خواندنی/قابِل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی برابر false است.

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
public abstract void setDisableFontLigatures(boolean value)
```


دریافت یا تنظیم مقداری که نشان می‌دهد متن بدون استفاده از لیگچرها رندر می‌شود. وقتی به true تنظیم شود، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به طور پیش‌فرض این ویژگی برابر false است.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> مثال:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


دریافت یا تنظیم حالت قرارگیری اسلایدها روی صفحه هنگام صادرات یک ارائه [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract IInkOptions getInkOptions()
```


ارائه گزینه‌ها برای کنترل ظاهر اشیاء Ink در سند صادرشده. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)