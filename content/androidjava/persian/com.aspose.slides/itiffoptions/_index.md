---
title: ITiffOptions
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره یک ارائه به فرمت TIFF را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/itiffoptions/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌ی یک ارائه در قالب TIFF را کنترل می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getImageSize()](#getImageSize--) | اندازه تصویر TIFF تولید‌شده را مشخص می‌کند. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | اندازه تصویر TIFF تولید‌شده را مشخص می‌کند. |
| [getDpiX()](#getDpiX--) | رزولوشن افقی را بر حسب نقاط بر اینچ مشخص می‌کند. |
| [setDpiX(long value)](#setDpiX-long-) | رزولوشن افقی را بر حسب نقاط بر اینچ مشخص می‌کند. |
| [getDpiY()](#getDpiY--) | رزولوشن عمودی را بر حسب نقاط بر اینچ مشخص می‌کند. |
| [setDpiY(long value)](#setDpiY-long-) | رزولوشن عمودی را بر حسب نقاط بر اینچ مشخص می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند که آیا سند تولید‌شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند که آیا سند تولید‌شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getCompressionType()](#getCompressionType--) | نوع فشرده‌سازی را مشخص می‌کند. |
| [setCompressionType(int value)](#setCompressionType-int-) | نوع فشرده‌سازی را مشخص می‌کند. |
| [getPixelFormat()](#getPixelFormat--) | قالب پیکسل برای تصاویر تولید‌شده را مشخص می‌کند. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | قالب پیکسل برای تصاویر تولید‌شده را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | الگوریتم تبدیل تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | الگوریتم تبدیل تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند صادرات‌شده را کنترل می‌کنند. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

اندازه تصویر TIFF تولید‌شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید‌شده بر اساس مقدار اندازه اسلاید ارائه محاسبه خواهد شد. خواندن/نوشتن [Size](../../com.aspose.slides.android/size).

**بازگشت:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

اندازه تصویر TIFF تولید‌شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است که به این معنی است که اندازه‌های تصویر تولید‌شده بر اساس مقدار اندازه اسلاید ارائه محاسبه خواهد شد. خواندن/نوشتن [Size](../../com.aspose.slides.android/size).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

رزولوشن افقی را بر حسب نقاط بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**بازگشت:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

رزولوشن افقی را بر حسب نقاط بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

رزولوشن عمودی را بر حسب نقاط بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**بازگشت:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

رزولوشن عمودی را بر حسب نقاط بر اینچ مشخص می‌کند. خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخص می‌کند که آیا سند تولید‌شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگشت:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند که آیا سند تولید‌شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

نوع فشرده‌سازی را مشخص می‌کند. خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**بازگشت:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

نوع فشرده‌سازی را مشخص می‌کند. خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

قالب پیکسل برای تصاویر تولید‌شده را مشخص می‌کند. خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**بازگشت:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

قالب پیکسل برای تصاویر تولید‌شده را مشخص می‌کند. خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract int getBwConversionMode()
```

الگوریتم تبدیل تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) بر روی [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) تنظیم شده باشد. خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public abstract void setBwConversionMode(int value)
```

الگوریتم تبدیل تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) بر روی [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) تنظیم شده باشد. خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink در سند صادرات‌شده را کنترل می‌کند. فقط‌خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگشت:**
[IInkOptions](../../com.aspose.slides/iinkoptions)