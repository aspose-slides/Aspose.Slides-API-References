---
title: TiffOptions
second_title: Aspose.Slides for Android عبر مرجع واجهة برمجة تطبيقات جافا
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة TIFF.
type: docs
url: /ar/com.aspose.slides/tiffoptions/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)  
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بصيغة TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // حفظ العرض التقديمي إلى مستند TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != nil) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // إنشاء فئة TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // تعيين نوع الضغط
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // أنواع الضغط
>      // Default - يحدد مخطط الضغط الافتراضي (LZW).
>      // None - يحدد عدم وجود ضغط.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // العمق يعتمد على نوع الضغط ولا يمكن تعيينه يدويًا.
>      // وحدة الدقة دائمًا تساوي 2 (نقطة لكل بوصة)
>      // تعيين DPI للصورة
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // تعيين حجم الصورة
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != nil) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat يحتوي على القيم التالية (كما هو موضح في الوثائق):
>      //Format1bppIndexed; // 1 بت لكل بكسل، مفهرس.
>      //Format4bppIndexed; // 4 بت لكل بكسل، مفهرس.
>      //Format8bppIndexed; // 8 بت لكل بكسل، مفهرس.
>      //Format24bppRgb; // 24 بت لكل بكسل، RGB.
>      //Format32bppArgb; // 32 بت لكل بكسل، ARGB.
> 
>      // حفظ العرض التقديمي إلى TIFF بالحجم المحدد للصورة
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != nil) pres.dispose();
>  }
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | المنشئ الافتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدّر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. |
| [getImageSize()](#getImageSize--) | يحدد حجم صورة TIFF مُولدة. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | يحدد حجم صورة TIFF مُولدة. |
| [getDpiX()](#getDpiX--) | يحدد الدقة الأفقية بوحدات النقاط لكل بوصة. |
| [setDpiX(long value)](#setDpiX-long-) | يحدد الدقة الأفقية بوحدات النقاط لكل بوصة. |
| [getDpiY()](#getDpiY--) | يحدد الدقة الرأسية بوحدات النقاط لكل بوصة. |
| [setDpiY(long value)](#setDpiY-long-) | يحدد الدقة الرأسية بوحدات النقاط لكل بوصة. |
| [getCompressionType()](#getCompressionType--) | يحدد نوع الضغط. |
| [setCompressionType(int value)](#setCompressionType-int-) | يحدد نوع الضغط. |
| [getPixelFormat()](#getPixelFormat--) | يحدد تنسيق البكسل للصور المُولدة. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | يحدد تنسيق البكسل للصور المُولدة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يُحصل أو يُعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يُحصل أو يُعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```

المنشئ الافتراضي.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدّر. للقراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولد الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```

يحدد حجم صورة TIFF مُولدة. القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُولدة سُتُحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة/كتابة [Size](../../com.aspose.slides.android/size).

**القيمة المرجعة:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```

يحدد حجم صورة TIFF مُولدة. القيمة الافتراضية هي 0x0، ما يعني أن أحجام الصور المُولدة سُتُحسب بناءً على قيمة حجم شريحة العرض التقديمي. قراءة/كتابة [Size](../../com.aspose.slides.android/size).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |
### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```

يحدد الدقة الأفقية بوحدات النقاط لكل بوصة. قراءة/كتابة long.

**القيمة المرجعة:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```

يحدد الدقة الأفقية بوحدات النقاط لكل بوصة. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |
### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```

يحدد الدقة الرأسية بوحدات النقاط لكل بوصة. قراءة/كتابة long.

**القيمة المرجعة:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```

يحدد الدقة الرأسية بوحدات النقاط لكل بوصة. قراءة/كتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |
### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```

يحدد نوع الضغط. قراءة/كتابة [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**القيمة المرجعة:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```

يحدد نوع الضغط. قراءة/كتابة [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```

يحدد تنسيق البكسل للصور المُولدة. قراءة/كتابة [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**القيمة المرجعة:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```

يحدد تنسيق البكسل للصور المُولدة. قراءة/كتابة [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

يُحصل أو يُعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يُحصل أو يُعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيُطبق هذا الخيار فقط إذا تم ضبط CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) إلى [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) أو [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) قراءة/كتابة [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). القيمة الافتراضية هي [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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

**القيمة المرجعة:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```

يحدد الخوارزمية لتحويل صورة ملونة إلى صورة أبيض وأسود. سيُطبق هذا الخيار فقط إذا تم ضبط CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) إلى [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) أو [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) قراءة/كتابة [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). القيمة الافتراضية هي [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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