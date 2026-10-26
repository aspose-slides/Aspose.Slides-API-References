---
title: IHtmlOptions
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر گزینه‌های صادرات HTML است.
type: docs
url: /fa/com.aspose.slides/ihtmloptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

نمایش گزینه‌های صادرات HTML.
## متدها

| متد | توضیح |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | قالب HTML را برمی‌گرداند یا تنظیم می‌کند. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | قالب HTML را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlideImageFormat()](#getSlideImageFormat--) | گزینه‌های فرمت تصویر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | گزینه‌های فرمت تصویر اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getJpegQuality()](#getJpegQuality--) | مقداری را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | مقداری را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. |
| [getPicturesCompression()](#getPicturesCompression--) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد خواندنی/نوشتنی [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | سطح فشرده‌سازی تصاویر را نمایش می‌دهد خواندنی/نوشتنی [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True برای حذف ویژگی‌های عرض و ارتفاع از کانتینر SVG - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True برای حذف ویژگی‌های عرض و ارتفاع از کانتینر SVG - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

قالب HTML را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**بازگشت:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

قالب HTML را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

گزینه‌های فرمت تصویر اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**بازگشت:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

گزینه‌های فرمت تصویر اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/نوشتنی byte.

--------------------

فقط وقتی سند شامل تصاویر JPEG باشد اثر می‌گذارد.

از این خصوصیت برای دریافت یا تنظیم کیفیت تصاویر داخل یک سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای کیفیت پایین‌ترین ولی بیشترین فشرده‌سازی و 100 به معنای بهترین کیفیت ولی کمترین فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**بازگشت:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

مقداری را برمی‌گرداند یا تنظیم می‌کند که کیفیت تصاویر JPEG داخل سند PDF را تعیین می‌کند. خواندنی/نوشتنی byte.

--------------------

فقط وقتی سند شامل تصاویر JPEG باشد اثر می‌گذارد.

از این خصوصیت برای دریافت یا تنظیم کیفیت تصاویر داخل یک سند هنگام ذخیره در قالب PDF استفاده کنید. مقدار می‌تواند از 0 تا 100 باشد که 0 به معنای کیفیت پایین‌ترین ولی بیشترین فشرده‌سازی و 100 به معنای بهترین کیفیت ولی کمترین فشرده‌سازی است.

مقدار پیش‌فرض **95** است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

سطح فشرده‌سازی تصاویر را نمایش می‌دهد خواندنی/نوشتنی [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**بازگشت:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

سطح فشرده‌سازی تصاویر را نمایش می‌دهد خواندنی/نوشتنی [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، بخش‌های برش خورده حذف می‌شوند، اگر false باشد، در سند سریالایز می‌شوند (که ممکن است منجر به فایل بزرگ‌تری شود) خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

یک پرچم بولی نشان می‌دهد که آیا بخش‌های برش خورده به عنوان بخشی از سند باقی می‌مانند یا نه. اگر true باشد، بخش‌های برش خورده حذف می‌شوند، اگر false باشد، در سند سریالایز می‌شوند (که ممکن است منجر به فایل بزرگ‌تری شود) خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True برای حذف ویژگی‌های عرض و ارتفاع از کانتینر SVG - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. False - در غیر این صورت. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True برای حذف ویژگی‌های عرض و ارتفاع از کانتینر SVG - که باعث می‌شود طرح‌بندی واکنش‌گرا باشد. False - در غیر این صورت. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی مقدار true باشد، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

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

مقداری را دریافت یا تنظیم می‌کند که نشان می‌دهد آیا متن بدون استفاده از لیگچرها رندر می‌شود یا نه. وقتی مقدار true باشد، لیگچرها در خروجی رندر شده غیرفعال می‌شوند. به‌طور پیش‌فرض این خصوصیت false است.

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

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کند. فقط-خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)