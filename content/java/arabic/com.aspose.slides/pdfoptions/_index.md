---
title: PdfOptions
second_title: مرجع API ل Aspose.Slides للغة Java
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Pdf.
type: docs
url: /ar/com.aspose.slides/pdfoptions/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IPdfOptions](../../com.aspose.slides/ipdfoptions)  
```
public class PdfOptions extends SaveOptions implements IPdfOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة Pdf.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // ينشئ فئة PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // يضبط جودة JPEG
>      pdfOptions.setJpegQuality((byte)90);
>      // يضبط سلوك ملفات الميتا
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // يضبط مستوى ضغط النص
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // يحدد معيار PDF
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // يحفظ العرض التقديمي كملف PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // ينشئ فئة Presentation التي تمثل ملف PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // ينشئ فئة PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // يضيف الشرائح المخفية
>      pdfOptions.setShowHiddenSlides(true);
>      // يحفظ العرض التقديمي كملف PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // ينشئ كائن Presentation الذي يمثل ملف PowerPoint
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // ينشئ فئة PdfOptions
>      PdfOptions pdfOptions = new PdfOptions();
>      // يضبط كلمة مرور PDF وأذونات الوصول
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // يحفظ العرض التقديمي كملف PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // ينشئ كائن Presentation الذي يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // ضبط نوع الشريحة وحجمها
>          auxPres.getSlideSize().setSize(612F, 792F, SlideSizeScaleType.EnsureFit);
>          PdfOptions pdfOptions = new PdfOptions();
>          pdfOptions.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomFull);
>          auxPres.save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
>      } finally {
>          if (auxPres != null) auxPres.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | المنشئ الافتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفيّة أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفيّة أم لا. |
| [getTextCompression()](#getTextCompression--) | يحدد نوع الضغط الذي سيُستخدم لكل المحتوى النصي في المستند. |
| [setTextCompression(int value)](#setTextCompression-int-) | يحدد نوع الضغط الذي سيُستخدم لكل المحتوى النصي في المستند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضبط الافتراضي) لكل صورة تلقائيًا. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضبط الافتراضي) لكل صورة تلقائيًا. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط المحددة من قبل المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط المحددة من قبل المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط الجزء المستخدم. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط الجزء المستخدم. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه كملف PDF عندما لا يدعم الخط تنسيق عريض. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه كملف PDF عندما لا يدعم الخط تنسيق عريض. |
| [getJpegQuality()](#getJpegQuality--) | يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getCompliance()](#getCompliance--) | مستوى التوافق المطلوب للمستند PDF المُولَّد. |
| [setCompliance(int value)](#setCompliance-int-) | مستوى التوافق المطلوب للمستند PDF المُولَّد. |
| [getPassword()](#getPassword--) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند بوصول المستخدم. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند بوصول المستخدم. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
| [getImageTransparentColor()](#getImageTransparentColor--) | يحصل أو يضبط لون الشفافية للصورة. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | يحصل أو يضبط لون الشفافية للصورة. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا. |
| [getIncludeOleData()](#getIncludeOleData--) | صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في PDF الناتج. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في PDF الناتج. |

### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```

المنشئ الافتراضي.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفيّة أم لا. القيمة الافتراضية هي false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن الشرائح المخفيّة أم لا. القيمة الافتراضية هي false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

يحدد نوع الضغط الذي سيُستخدم لكل المحتوى النصي في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

القيمة الافتراضية هي [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**الإرجاع:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

يحدد نوع الضغط الذي سيُستخدم لكل المحتوى النصي في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

القيمة الافتراضية هي [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public final boolean getBestImagesCompressionRatio()
```

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضبط الافتراضي) لكل صورة تلقائيًا. إذا تم التعيين إلى true، سيُختار أفضل خوارزمية ضغط لكل صورة في العرض التقديمي، ما سيؤدي إلى حجم أصغر للملف PDF الناتج.

--------------------

اختيار أفضل نسبة ضغط للصور يستغرق حسابيًا موارد كبيرة ويتطلب مقدارًا إضافيًا من الذاكرة، وهذا الخيار false بشكل افتراضي.

--------------------

القيمة الافتراضية هي false.

**الإرجاع:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الضبط الافتراضي) لكل صورة تلقائيًا. إذا تم التعيين إلى true، سيُختار أفضل خوارزمية ضغط لكل صورة في العرض التقديمي، ما سيؤدي إلى حجم أصغر للملف PDF الناتج.

--------------------

اختيار أفضل نسبة ضغط للصور يستغرق حسابيًا موارد كبيرة ويتطلب مقدارًا إضافيًا من الذاكرة، وهذا الخيار false بشكل افتراضي.

--------------------

القيمة الافتراضية هي false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط للرموز التي تزيد عن 127 ستكون دائمًا مضمّنة. قائمة الخطوط الشائعة تشمل الخطوط الأساسية 14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**الإرجاع:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط للرموز التي تزيد عن 127 ستكون دائمًا مضمّنة. قائمة الخطوط الشائعة تشمل الخطوط الأساسية 14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط المحددة من قبل المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. قراءة/كتابة String[].

**الإرجاع:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط المحددة من قبل المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. قراءة/كتابة String[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط الجزء المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط الجزء المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه كملف PDF عندما لا يدعم الخط تنسيق عريض. يمكن أن يحسّن هذا النهج جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه كملف PDF عندما لا يدعم الخط تنسيق عريض. يمكن أن يحسّن هذا النهج جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل المستند عند الحفظ بصيغة PDF. القيمة قد تتراوح بين 0 إلى 100 حيث 0 تعني أسوأ جودة ولكن أقصى ضغط و100 تعني أفضل جودة ولكن أقل ضغط.

القيمة الافتراضية هي **100**.

**الإرجاع:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل المستند عند الحفظ بصيغة PDF. القيمة قد تتراوح بين 0 إلى 100 حيث 0 تعني أسوأ جودة ولكن أقصى ضغط و100 تعني أفضل جودة ولكن أقل ضغط.

القيمة الافتراضية هي **100**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

مستوى التوافق المطلوب للمستند PDF المُولَّد. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

القيمة الافتراضية هي [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**الإرجاع:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

مستوى التوافق المطلوب للمستند PDF المُولَّد. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

القيمة الافتراضية هي [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public final int getAccessPermissions()
```

يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند بوصول المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**الإرجاع:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

يحتوي على مجموعة من العلامات التي تحدد أي أذونات وصول يجب منحها عندما يُفتح المستند بوصول المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setPassword("my_password");
>  pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>  Presentation presentation = new Presentation();
>  try
>  {
>      presentation.save(pdfFilePath, SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**. مستند PDF يمكن أن يحتوي على رسومات متجهية وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فسيتم تحويل صورة الميتا المصدر إلى صيغة PNG وحفظها كصورة نقطية في PDF. إذا تم تعيينه إلى false فسيتم تحويل الميتا إلى رسومات متجهية في PDF. كل طريقة لها مزايا وعيوب. على سبيل المثال، إذا تم تحويل الميتا إلى PNG، قد يحدث فقدان جودة أثناء تحجيم المستند الناتج. إذا تم تحويل الميتا إلى رسومات متجهية، قد تظهر مشكلات أداء في عارض PDF.

**الإرجاع:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**. مستند PDF يمكن أن يحتوي على رسومات متجهية وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فسيتم تحويل صورة الميتا المصدر إلى صيغة PNG وحفظها كصورة نقطية في PDF. إذا تم تعيينه إلى false فسيتم تحويل الميتا إلى رسومات متجهية في PDF. كل طريقة لها مزايا وعيوب. على سبيل المثال، إذا تم تحويل الميتا إلى PNG، قد يحدث فقدان جودة أثناء تحجيم المستند الناتج. إذا تم تحويل الميتا إلى رسومات متجهية، قد تظهر مشكلات أداء في عارض PDF.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: يعتمد تأثير هذا المعامل على عدة عوامل. تحاول الخوارزمية الحصول على أفضل حجم للصورة الناتجة وفقًا لقيمة الخاصية، حجم الصورة المصدر، وحجم إطار الصورة. قد يعطي استخدام قيم مماثلة نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير واضح.

--------------------

تؤثر الخاصية على حجم الملف، وقت التصدير، وجودة الصورة.

القيمة الافتراضية هي **96**.

**الإرجاع:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: يعتمد تأثير هذا المعامل على عدة عوامل. تحاول الخوارزمية الحصول على أفضل حجم للصورة الناتجة وفقًا لقيمة الخاصية، حجم الصورة المصدر، وحجم إطار الصورة. قد يعطي استخدام قيم مماثلة نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير واضح.

--------------------

تؤثر الخاصية على حجم الملف، وقت التصدير، وجودة الصورة.

القيمة الافتراضية هي **96**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Color getImageTransparentColor()
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**الإرجاع:**
java.awt.Color
### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public final void setImageTransparentColor(Color value)
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا.

**الإرجاع:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

القيمة الافتراضية هي  **false** .

**الإرجاع:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة  boolean .

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions options = new PdfOptions();
>      options.setIncludeOleData(true);
>      pres.save("pres.pdf", SaveFormat.Pdf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

القيمة الافتراضية هي  **false** .

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |