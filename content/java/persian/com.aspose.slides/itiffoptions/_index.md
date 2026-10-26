---
title: ITiffOptions
second_title: مرجع API Aspose.Slides برای جاوا
description: گزینه‌هایی را فراهم می‌کند که نحوه ذخیره‌سازی یک ارائه در قالب TIFF را کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/itiffoptions/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

گزینه‌هایی که نحوه ذخیره‌سازی یک ارائه در فرمت TIFF را کنترل می‌کند فراهم می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [getImageSize()](#getImageSize--) | اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. |
| [setImageSize(Dimension value)](#setImageSize-java.awt.Dimension-) | اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. |
| [getDpiX()](#getDpiX--) | رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. |
| [setDpiX(long value)](#setDpiX-long-) | رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. |
| [getDpiY()](#getDpiY--) | رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. |
| [setDpiY(long value)](#setDpiY-long-) | رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. |
| [getCompressionType()](#getCompressionType--) | نوع فشرده‌سازی را مشخص می‌کند. |
| [setCompressionType(int value)](#setCompressionType-int-) | نوع فشرده‌سازی را مشخص می‌کند. |
| [getPixelFormat()](#getPixelFormat--) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. |
| [getInkOptions()](#getInkOptions--) | گزینه‌هایی که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند ارائه می‌دهد. |

### getImageSize() {#getImageSize--}
```
public abstract Dimension getImageSize()
```

اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است، به این معنی که اندازه تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه خواهد شد. قابل خواندن/نوشتن java.awt.Dimension.

**بازگرداندن:**
java.awt.Dimension

### setImageSize(Dimension value) {#setImageSize-java.awt.Dimension-}
```
public abstract void setImageSize(Dimension value)
```

اندازه یک تصویر TIFF تولید شده را مشخص می‌کند. مقدار پیش‌فرض 0x0 است، به این معنی که اندازه تصویر تولید شده بر اساس مقدار اندازه اسلاید ارائه محاسبه خواهد شد. قابل خواندن/نوشتن java.awt.Dimension.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Dimension |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. قابل خواندن/نوشتن long.

**بازگرداندن:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

رزولوشن افقی را بر حسب نقطه در اینچ مشخص می‌کند. قابل خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. قابل خواندن/نوشتن long.

**بازگرداندن:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

رزولوشن عمودی را بر حسب نقطه در اینچ مشخص می‌کند. قابل خواندن/نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**بازگرداندن:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

مشخص می‌کند آیا سند تولید شده باید اسلایدهای مخفی را شامل شود یا نه. مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

نوع فشرده‌سازی را مشخص می‌کند. قابل خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**بازگرداندن:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

نوع فشرده‌سازی را مشخص می‌کند. قابل خواندن/نوشتن [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. قابل خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**بازگرداندن:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

قالب پیکسل برای تصاویر تولید شده را مشخص می‌کند. قابل خواندن/نوشتن [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**بازگرداندن:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

حالت قرارگیری اسلایدها بر روی صفحه هنگام صادرات یک ارائه را دریافت یا تنظیم می‌کند [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) بر روی [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) تنظیم شده باشد. قابل خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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


**بازگرداندن:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

الگوریتم تبدیل یک تصویر رنگی به تصویر سیاه‌سفید را مشخص می‌کند. این گزینه تنها در صورتی اعمال می‌شود که CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) بر روی [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) یا [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) تنظیم شده باشد. قابل خواندن/نوشتن [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). مقدار پیش‌فرض [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

گزینه‌هایی که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند ارائه می‌دهد. فقط خواندنی [IInkOptions](../../com.aspose.slides/iinkoptions)

**بازگرداندن:**
[IInkOptions](../../com.aspose.slides/iinkoptions)