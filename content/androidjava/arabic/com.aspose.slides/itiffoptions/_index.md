---
title: ITiffOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.
type: docs
url: /ar/com.aspose.slides/itiffoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getImageSize()](#getImageSize--) | يحدد حجم صورة TIFF تم إنشاؤها. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | يحدد حجم صورة TIFF تم إنشاؤها. |
| [getDpiX()](#getDpiX--) | يحدد الدقة الأفقية بالنقاط في البوصة. |
| [setDpiX(long value)](#setDpiX-long-) | يحدد الدقة الأفقية بالنقاط في البوصة. |
| [getDpiY()](#getDpiY--) | يحدد الدقة العمودية بالنقاط في البوصة. |
| [setDpiY(long value)](#setDpiY-long-) | يحدد الدقة العمودية بالنقاط في البوصة. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
| [getCompressionType()](#getCompressionType--) | يحدد نوع الضغط. |
| [setCompressionType(int value)](#setCompressionType-int-) | يحدد نوع الضغط. |
| [getPixelFormat()](#getPixelFormat--) | يحدد تنسيق البكسل للصور المُنشأة. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | يحدد تنسيق البكسل للصور المُنشأة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

يحدد حجم صورة TIFF تم إنشاؤها. القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُنشأة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة/كتابة [Size](../../com.aspose.slides.android/size).

**الإرجاع:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

يحدد حجم صورة TIFF تم إنشاؤها. القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُنشأة ستحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة/كتابة [Size](../../com.aspose.slides.android/size).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

يحدد الدقة الأفقية بالنقاط في البوصة. قراءة/كتابة long.

**الإرجاع:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

يحدد الدقة الأفقية بالنقاط في البوصة. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

يحدد الدقة العمودية بالنقاط في البوصة. قراءة/كتابة long.

**الإرجاع:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

يحدد الدقة العمودية بالنقاط في البوصة. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**الإرجاع:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

يحدد نوع الضغط. قراءة/كتابة [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**الإرجاع:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

يحدد نوع الضغط. قراءة/كتابة [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

يحدد تنسيق البكسل للصور المُنشأة. قراءة/كتابة [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**الإرجاع:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

يحدد تنسيق البكسل للصور المُنشأة. قراءة/كتابة [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**الإرجاع:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيتم تطبيق هذا الخيار فقط إذا كان CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) مضبوطًا على [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) أو [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) قراءة/كتابة [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). القيمة الافتراضية هي [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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


**الإرجاع:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة بالأبيض والأسود. سيتم تطبيق هذا الخيار فقط إذا كان CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) مضبوطًا على [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) أو [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) قراءة/كتابة [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). القيمة الافتراضية هي [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)