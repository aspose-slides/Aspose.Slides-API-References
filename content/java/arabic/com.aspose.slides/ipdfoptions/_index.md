---
title: IPdfOptions
second_title: مرجع API لـ Aspose.Slides for Java
description: يوفر خيارات تتحكم في طريقة حفظ عرض تقديمي بصيغة PDF.
type: docs
url: /ar/com.aspose.slides/ipdfoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

يوفر خيارات تتحكم في طريقة حفظ عرض تقديمي بصيغة PDF.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. |
| [setTextCompression(int value)](#setTextCompression-int-) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | يفيد ما إذا كان يجب اختيار أقوى ضغط (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | يفيد ما إذا كان يجب اختيار أقوى ضغط (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | صحيح لتضمين خطوط TrueType لأحرف ASCII من 32 إلى 127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | صحيح لتضمين خطوط TrueType لأحرف ASCII من 32 إلى 127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان يجب أن يحتوي المستند المُولد على الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان يجب أن يحتوي المستند المُولد على الشرائح المخفية أم لا. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | يرجع أو يضبط مصفوفة من أسماء عائلات الخطوط التي يحددها المستخدم والتي يجب على Aspose.Slides اعتبارها شائعة. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | Returns or sets an array of user-defined names of font families which Aspose.Slides should consider common. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط المجموعة الفرعية المستخدمة. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط المجموعة الفرعية المستخدمة. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | يفيد ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط نمط الخط العريض. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | يفيد ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط نمط الخط العريض. |
| [getJpegQuality()](#getJpegQuality--) | يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getCompliance()](#getCompliance--) | مستوى الامتثال المطلوب للمستند PDF المُولد. |
| [setCompliance(int value)](#setCompliance-int-) | مستوى الامتثال المطلوب للمستند PDF المُولد. |
| [getPassword()](#getPassword--) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بإذن المستخدم. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بإذن المستخدم. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يضبط الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يضبط الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | يحصل أو يضبط لون الشفافية للصورة. |
| [setImageTransparentColor(Color value)](#setImageTransparentColor-java.awt.Color-) | يحصل أو يضبط لون الشفافية للصورة. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | يطبق لون الشفافية المحدد على الصورة إذا كان صحيحًا. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | يطبق لون الشفافية المحدد على الصورة إذا كان صحيحًا. |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. |
| [getIncludeOleData()](#getIncludeOleData--) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

الافتراضي هو [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**الإرجاع:**
int

### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

يحدد نوع الضغط الذي سيُستخدم لجميع المحتويات النصية في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

الافتراضي هو [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

يفيد ما إذا كان يجب اختيار أقوى ضغط (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى صحيح، سيتم اختيار خوارزمية الضغط الأنسب لكل صورة في العرض، مما يؤدي إلى حجم أصغر للمستند PDF الناتج.

--------------------

اختيار أفضل نسبة ضغط للصور يتطلب حسابًا مكثفًا ويستهلك كمية إضافية من الذاكرة، وهذا الخيار يكون false بشكل افتراضي.

--------------------

الافتراضي هو false.

**الإرجاع:**
boolean

### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

يفيد ما إذا كان يجب اختيار أقوى ضغط (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى صحيح، سيتم اختيار خوارزمية الضغط الأنسب لكل صورة في العرض، مما يؤدي إلى حجم أصغر للمستند PDF الناتج.

--------------------

اختيار أفضل نسبة ضغط للصور يتطلب حسابًا مكثفًا ويستهلك كمية إضافية من الذاكرة، وهذا الخيار يكون false بشكل افتراضي.

--------------------

الافتراضي هو false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

صحيح لتضمين خطوط TrueType لأحرف ASCII من 32 إلى 127. الخطوط لأكواد الأحرف التي تزيد عن 127 تُضمّن دائمًا. قراءة/كتابة boolean.

--------------------

الافتراضي هو **true**.

**الإرجاع:**
boolean

### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

صحيح لتضمين خطوط TrueType لأحرف ASCII من 32 إلى 127. الخطوط لأكواد الأحرف التي تزيد عن 127 تُضمّن دائمًا. قراءة/كتابة boolean.

--------------------

الافتراضي هو **true**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان يجب أن يحتوي المستند المُولد على الشرائح المخفية أم لا. الافتراضي هو false.

**الإرجاع:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان يجب أن يحتوي المستند المُولد على الشرائح المخفية أم لا. الافتراضي هو false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

يرجع أو يضبط مصفوفة من الأسماء المعرفة من قبل المستخدم لعائلات الخطوط التي يجب على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[].

**الإرجاع:**
java.lang.String[]

### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

يرجع أو يضبط مصفوفة من الأسماء المعرفة من قبل المستخدم لعائلات الخطوط التي يجب على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[].

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط المجموعة الفرعية المستخدمة. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**الإرجاع:**
boolean

### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أو فقط المجموعة الفرعية المستخدمة. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

يفيد ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط نمط الخط العريض. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**الإرجاع:**
boolean

### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

يفيد ما إذا كان يجب تحويل النص إلى صورة نقطية (bitmap) وحفظه في PDF عندما لا يدعم الخط نمط الخط العريض. يمكن لهذا الأسلوب تحسين جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يعمل فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على جودة الصور أو تعيينها عند حفظ المستند بصيغة PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **100**.

**الإرجاع:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

يرجع أو يضبط قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يعمل فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على جودة الصور أو تعيينها عند حفظ المستند بصيغة PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **100**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

مستوى الامتثال المطلوب للمستند PDF المُولد. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

الافتراضي هو [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**الإرجاع:**
int

### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

مستوى الامتثال المطلوب للمستند PDF المُولد. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

الافتراضي هو [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessPermissions() {#getAccessPermissions--}
```
public abstract int getAccessPermissions()
```

يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بإذن المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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
public abstract void setAccessPermissions(int value)
```

يحتوي على مجموعة من العلامات التي تحدد أذونات الوصول التي يجب منحها عند فتح المستند بإذن المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

الافتراضي هو **true**. يمكن لمستند PDF أن يحتوي على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة ملف الميتا المصدر تُحوَّل إلى صيغة PNG وتُحفظ في PDF كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن ملف الميتا المصدر يُحوَّل إلى رسومات متجهة في PDF. لكل طريقة مميزات وعيوب. على سبيل المثال، إذا تم تحويل ملف الميتا إلى PNG قد يحدث فقدان بعض الجودة أثناء تكبير المستند الناتج. إذا تم تحويل ملف الميتا إلى رسومات متجهة في PDF قد تظهر مشكلات أداء في أداة عرض PDF.

**الإرجاع:**
boolean

### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

الافتراضي هو **true**. يمكن لمستند PDF أن يحتوي على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true فإن صورة ملف الميتا المصدر تُحوَّل إلى صيغة PNG وتُحفظ في PDF كصورة نقطية. إذا تم تعيين SaveMetafilesAsPng إلى false فإن ملف الميتا المصدر يُحوَّل إلى رسومات متجهة في PDF. لكل طريقة مميزات وعيوب. على سبيل المثال، إذا تم تحويل ملف الميتا إلى PNG قد يحدث فقدان بعض الجودة أثناء تكبير المستند الناتج. إذا تم تحويل ملف الميتا إلى رسومات متجهة في PDF قد تظهر مشكلات أداء في أداة عرض PDF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذه المعلمة يعتمد على عدة عوامل. يحاول الخوارزم الحصول على أفضل حجم صورة إخرج وفقًا لقيمة الخاصية، حجم الصورة المصدر وحجم إطار الصورة. قد تعطي قيم مشابهة للخاصية نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير ملحوظ.

--------------------

تؤثر الخاصية على حجم الملف، وقت التصدير وجودة الصورة.

القيمة الافتراضية هي **96**.

**الإرجاع:**
float

### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

يرجع أو يضبط قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذه المعلمة يعتمد على عدة عوامل. يحاول الخوارزم الحصول على أفضل حجم صورة إخرج وفقًا لقيمة الخاصية، حجم الصورة المصدر وحجم إطار الصورة. قد تعطي قيم مشابهة للخاصية نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير ملحوظ.

--------------------

تؤثر الخاصية على حجم الملف، وقت التصدير وجودة الصورة.

القيمة الافتراضية هي **96**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**الإرجاع:**
boolean

### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يضبط الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يضبط الوضع الذي تُوضَع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getImageTransparentColor() {#getImageTransparentColor--}
```
public abstract Color getImageTransparentColor()
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**الإرجاع:**
java.awt.Color

### setImageTransparentColor(Color value) {#setImageTransparentColor-java.awt.Color-}
```
public abstract void setImageTransparentColor(Color value)
```

يحصل أو يضبط لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.awt.Color |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

يطبق لون الشفافية المحدد على الصورة إذا كان صحيحًا.

**الإرجاع:**
boolean

### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

يطبق لون الشفافية المحدد على الصورة إذا كان صحيحًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. قراءة/كتابة [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج. قراءة/كتابة boolean.

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

الافتراضي هو **false**.

**الإرجاع:**
boolean

### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مضمَّنة في PDF الناتج. قراءة/كتابة boolean.

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

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |