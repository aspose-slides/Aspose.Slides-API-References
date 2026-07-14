---
title: PdfOptions
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: توفر خيارات تتحكم في كيفية حفظ عرض تقديمي بتنسيق PDF.
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

توفر خيارات تتحكم في كيفية حفظ عرض تقديمي بتنسيق PDF.

--------------------

> ```
> The following example shows how to convert PowerPoint to PDF with custom options.
>  
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Sets the Jpeg quality
>      pdfOptions.setJpegQuality((byte)90);
>      // Sets the behavior for metafiles
>      pdfOptions.setSaveMetafilesAsPng(true);
>      // Sets the text compression level
>      pdfOptions.setTextCompression(PdfTextCompression.Flate);
>      // Defines the PDF standard
>      pdfOptions.setCompliance(PdfCompliance.Pdf15);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with hidden slides.
>  
>  // Instantiates a Presentation class that represents a PowerPoint file
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Adds hidden slides
>      pdfOptions.setShowHiddenSlides(true);
>      // Saves the presentation as a PDF
>      pres.save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to password protected PDF.
>  
>  // Instantiates a Presentation object that represents a PowerPoint file
>  Presentation pres = new Presentation("PowerPoint.pptx");
>  try {
>      // Instantiates the PdfOptions class
>      PdfOptions pdfOptions = new PdfOptions();
>      // Sets PDF password and access permissions
>      pdfOptions.setPassword("password");
>      pdfOptions.setAccessPermissions(PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint);
>      // Saves the presentation as a PDF
>      pres.save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PDF with notes.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation("SelectedSlides.pptx");
>  try {
>      Presentation auxPres = new Presentation();
>      try {
>          ISlide slide = pres.getSlides().get_Item(0);
>          auxPres.getSlides().insertClone(0, slide);
>          // Setting Slide Type and Size
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
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | المنشئ الافتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | توفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. |
| [getTextCompression()](#getTextCompression--) | يحدد نوع الضغط الذي يُستخدم لجميع المحتويات النصية في المستند. |
| [setTextCompression(int value)](#setTextCompression-int-) | يحدد نوع الضغط الذي يُستخدم لجميع المحتويات النصية في المستند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | يعيد أو يضبط مصفوفة من أسماء عائلات الخطوط التي يحددها المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | يعيد أو يضبط مصفوفة من أسماء عائلات الخطوط التي يحددها المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط الجزء المستخدم. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط الجزء المستخدم. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط عريض. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط عريض. |
| [getJpegQuality()](#getJpegQuality--) | يعيد أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يعيد أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getCompliance()](#getCompliance--) | مستوى التوافق المطلوب للمستند PDF المُنشأ. |
| [setCompliance(int value)](#setCompliance-int-) | مستوى التوافق المطلوب للمستند PDF المُنشأ. |
| [getPassword()](#getPassword--) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عند فتح المستند باستخدام صلاحية المستخدم. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عند فتح المستند باستخدام صلاحية المستخدم. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | يعيد أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | يعيد أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
| [getImageTransparentColor()](#getImageTransparentColor--) | يحصل أو يضبط لون الشفافية للصورة. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | يحصل أو يضبط لون الشفافية للصورة. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | يطبق اللون الشفاف المحدد على الصورة إذا كان صحيحًا. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | يطبق اللون الشفاف المحدد على الصورة إذا كان صحيحًا. |
| [getIncludeOleData()](#getIncludeOleData--) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. |

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

**القيمة المعادة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يضبط الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

توفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. للقراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المعادة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. **القيمة الافتراضية هي** **خاطئ**.

**القيمة المعادة:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن شرائح مخفية أم لا. **القيمة الافتراضية هي** **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getTextCompression() {#getTextCompression--}
```
public final int getTextCompression()
```

يحدد نوع الضغط الذي يُستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

القيمة الافتراضية هي [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**القيمة المعادة:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public final void setTextCompression(int value)
```

يحدد نوع الضغط الذي يُستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

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

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم ضبطه على صحيح، سيُختار لكل صورة في العرض خوارزمية الضغط الأنسب، ما سيؤدي إلى تقليل حجم مستند PDF الناتج.

--------------------

اختيار نسبة أفضل ضغط للصور يستغرق حسابيًا موارد كثيرة ويحتاج إلى مقدار إضافي من الذاكرة RAM، وهذا الخيار **خاطئ** بشكل افتراضي.

--------------------

القيمة الافتراضية هي **خاطئ**.

**القيمة المعادة:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public final void setBestImagesCompressionRatio(boolean value)
```

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم ضبطه على صحيح، سيُختار لكل صورة في العرض خوارزمية الضغط الأنسب، ما سيؤدي إلى تقليل حجم مستند PDF الناتج.

--------------------

اختيار نسبة أفضل ضغط للصور يستغرق حسابيًا موارد كثيرة ويحتاج إلى مقدار إضافي من الذاكرة RAM، وهذا الخيار **خاطئ** بشكل افتراضي.

--------------------

القيمة الافتراضية هي **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public final boolean getEmbedTrueTypeFontsForASCII()
```

يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط لأكواد الأحرف أعلى من 127 دائمًا مُضمَّنة. قائمة الخطوط الشائعة تشمل الخطوط الأساسية الـ14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **صحيح**.

**القيمة المعادة:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public final void setEmbedTrueTypeFontsForASCII(boolean value)
```

يحدد ما إذا كان Aspose.Slides سيضمّن الخطوط الشائعة لنص ASCII (نطاق الرموز 33..127). الخطوط لأكواد الأحرف أعلى من 127 دائمًا مُضمَّنة. قائمة الخطوط الشائعة تشمل الخطوط الأساسية الـ14 في PDF وخطوط إضافية يحددها المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **صحيح**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public final String[] getAdditionalCommonFontFamilies()
```

يعيد أو يضبط مصفوفة من أسماء عائلات الخطوط التي يحددها المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. قراءة/كتابة String[].

**القيمة المعادة:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public final void setAdditionalCommonFontFamilies(String[] value)
```

يعيد أو يضبط مصفوفة من أسماء عائلات الخطوط التي يحددها المستخدم والتي يجب أن يعتبرها Aspose.Slides شائعة. قراءة/كتابة String[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public final boolean getEmbedFullFonts()
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط الجزء المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **خاطئ**.

**القيمة المعادة:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public final void setEmbedFullFonts(boolean value)
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط الجزء المستخدم. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public final boolean getRasterizeUnsupportedFontStyles()
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط عريض. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **خاطئ**.

**القيمة المعادة:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public final void setRasterizeUnsupportedFontStyles(boolean value)
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط نمط عريض. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

يعيد أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل المستند عند الحفظ بتنسيق PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة ولكن أقصى ضغط و100 تعني أفضل جودة ولكن أقل ضغط.

القيمة الافتراضية هي **100**.

**القيمة المعادة:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

يعيد أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل المستند عند الحفظ بتنسيق PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة ولكن أقصى ضغط و100 تعني أفضل جودة ولكن أقل ضغط.

القيمة الافتراضية هي **100**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```

مستوى التوافق المطلوب للمستند PDF المُنشأ. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

القيمة الافتراضية هي [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**القيمة المعادة:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```

مستوى التوافق المطلوب للمستند PDF المُنشأ. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

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

**القيمة المعادة:**
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

يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عند فتح المستند باستخدام صلاحية المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**القيمة المعادة:**
int

### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public final void setAccessPermissions(int value)
```

يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عند فتح المستند باستخدام صلاحية المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

القيمة الافتراضية هي **صحيح**. يمكن أن يحتوي مستند PDF على رسومات متجهة وصور نقطية. إذا تم ضبط SaveMetafilesAsPng على صحيح، يتم تحويل صورة الميتافا الأصلية إلى صيغة PNG وحفظها في PDF كصورة نقطية. إذا تم ضبطه على خاطئ، يتم تحويل الميتافا إلى رسومات متجهة في PDF. كل طريقة لها مزايا وعيوب. على سبيل المثال، إذا تم تحويل الميتافا إلى PNG، قد يحدث فقدان بعض الجودة عند تكبير المستند الناتج. إذا تم تحويل الميتافا إلى رسومات متجهة في PDF، قد تظهر مشاكل أداء في أداة عرض PDF.

**القيمة المعادة:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **صحيح**. يمكن أن يحتوي مستند PDF على رسومات متجهة وصور نقطية. إذا تم ضبط SaveMetafilesAsPng على صحيح، يتم تحويل صورة الميتافا الأصلية إلى صيغة PNG وحفظها في PDF كصورة نقطية. إذا تم ضبطه على خاطئ، يتم تحويل الميتافا إلى رسومات متجهة في PDF. كل طريقة لها مزايا وعيوب. على سبيل المثال، إذا تم تحويل الميتافا إلى PNG، قد يحدث فقدان بعض الجودة عند تكبير المستند الناتج. إذا تم تحويل الميتافا إلى رسومات متجهة في PDF، قد تظهر مشاكل أداء في أداة عرض PDF.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public final float getSufficientResolution()
```

يعيد أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذا المعامل يعتمد على عدة عوامل. تحاول الخوارزمية الحصول على أفضل حجم صورة ناتج وفقًا لقيمة الخاصية، وحجم الصورة الأصلي، وحجم إطار الصورة. استخدام قيم خصائص مماثلة قد يعطي نفس النتيجة. يوصى باستخدام خطوة 16 أو 32 للحصول على تأثير مرئي.

--------------------

تؤثر الخاصية على حجم الملف، ووقت التصدير، وجودة الصورة.

القيمة الافتراضية هي **96**.

**القيمة المعادة:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public final void setSufficientResolution(float value)
```

يعيد أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذا المعامل يعتمد على عدة عوامل. تحاول الخوارزمية الحصول على أفضل حجم صورة ناتج وفقًا لقيمة الخاصية، وحجم الصورة الأصلي، وحجم إطار الصورة. استخدام قيم خصائص مماثلة قد يعطي نفس النتيجة. يوصى باستخدام خطوة 16 أو 32 للحصول على تأثير مرئي.

--------------------

تؤثر الخاصية على حجم الملف، ووقت التصدير، وجودة الصورة.

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

القيمة الافتراضية هي **خاطئ**.

**القيمة المعادة:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public final Integer getImageTransparentColor()
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**القيمة المعادة:**
java.lang.Integer

### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public final void setImageTransparentColor(Integer value)
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public final boolean getApplyImageTransparent()
```

يطبق اللون الشفاف المحدد على الصورة إذا كان صحيحًا.

**القيمة المعادة:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public final void setApplyImageTransparent(boolean value)
```

يطبق اللون الشفاف المحدد على الصورة إذا كان صحيحًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getIncludeOleData() {#getIncludeOleData--}
```
public final boolean getIncludeOleData()
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة boolean .

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

القيمة الافتراضية هي **خاطئ**.

**القيمة المعادة:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public final void setIncludeOleData(boolean value)
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمّنة في PDF الناتج. قراءة/كتابة boolean .

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

القيمة الافتراضية هي **خاطئ**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |