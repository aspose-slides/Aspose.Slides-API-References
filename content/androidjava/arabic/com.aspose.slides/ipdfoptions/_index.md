---
title: IPdfOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق PDF.
type: docs
url: /ar/com.aspose.slides/ipdfoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPdfOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق Pdf.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextCompression()](#getTextCompression--) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتوى النصي في المستند. |
| [setTextCompression(int value)](#setTextCompression-int-) | يحدد نوع الضغط الذي سيُستخدم لجميع المحتوى النصي في المستند. |
| [getBestImagesCompressionRatio()](#getBestImagesCompressionRatio--) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [setBestImagesCompressionRatio(boolean value)](#setBestImagesCompressionRatio-boolean-) | يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. |
| [getEmbedTrueTypeFontsForASCII()](#getEmbedTrueTypeFontsForASCII--) | صحيح لتضمين خطوط True Type لأحرف ASCII من 32 إلى 127. |
| [setEmbedTrueTypeFontsForASCII(boolean value)](#setEmbedTrueTypeFontsForASCII-boolean-) | صحيح لتضمين خطوط True Type لأحرف ASCII من 32 إلى 127. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
| [getAdditionalCommonFontFamilies()](#getAdditionalCommonFontFamilies--) | إرجاع أو تعيين مصفوفة من الأسماء التي يحددها المستخدم لعائلات الخطوط التي ينبغي على Aspose.Slides اعتبارها شائعة. |
| [setAdditionalCommonFontFamilies(String[] value)](#setAdditionalCommonFontFamilies-java.lang.String---) | إرجاع أو تعيين مصفوفة من الأسماء التي يحددها المستخدم لعائلات الخطوط التي ينبغي على Aspose.Slides اعتبارها شائعة. |
| [getEmbedFullFonts()](#getEmbedFullFonts--) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط مجموعة فرعية مستخدمة. |
| [setEmbedFullFonts(boolean value)](#setEmbedFullFonts-boolean-) | يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط مجموعة فرعية مستخدمة. |
| [getRasterizeUnsupportedFontStyles()](#getRasterizeUnsupportedFontStyles--) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط النمط العريض. |
| [setRasterizeUnsupportedFontStyles(boolean value)](#setRasterizeUnsupportedFontStyles-boolean-) | يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط النمط العريض. |
| [getJpegQuality()](#getJpegQuality--) | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getCompliance()](#getCompliance--) | مستوى التوافق المطلوب للمستند PDF المُنشأ. |
| [setCompliance(int value)](#setCompliance-int-) | مستوى التوافق المطلوب للمستند PDF المُنشأ. |
| [getPassword()](#getPassword--) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [setPassword(String value)](#setPassword-java.lang.String-) | تعيين كلمة مرور المستخدم لحماية مستند PDF. |
| [getAccessPermissions()](#getAccessPermissions--) | يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عندما يُفتح المستند بصلاحية المستخدم. |
| [setAccessPermissions(int value)](#setAccessPermissions-int-) | يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عندما يُفتح المستند بصلاحية المستخدم. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [getSufficientResolution()](#getSufficientResolution--) | إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. |
| [setSufficientResolution(float value)](#setSufficientResolution-float-) | إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | الحصول أو تعيين الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | الحصول أو تعيين الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getImageTransparentColor()](#getImageTransparentColor--) | الحصول أو تعيين لون الشفافية للصورة. |
| [setImageTransparentColor(Integer value)](#setImageTransparentColor-java.lang.Integer-) | الحصول أو تعيين لون الشفافية للصورة. |
| [getApplyImageTransparent()](#getApplyImageTransparent--) | يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا. |
| [setApplyImageTransparent(boolean value)](#setApplyImageTransparent-boolean-) | يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا. |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |
| [getIncludeOleData()](#getIncludeOleData--) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في PDF الناتج. |
| [setIncludeOleData(boolean value)](#setIncludeOleData-boolean-) | صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في PDF الناتج. |

### getTextCompression() {#getTextCompression--}
```
public abstract int getTextCompression()
```

يحدد نوع الضغط الذي سيُستخدم لجميع المحتوى النصي في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

القيمة الافتراضية هي [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**القيمة المرجعة:**
int
### setTextCompression(int value) {#setTextCompression-int-}
```
public abstract void setTextCompression(int value)
```

يحدد نوع الضغط الذي سيُستخدم لجميع المحتوى النصي في المستند. قراءة/كتابة [PdfTextCompression](../../com.aspose.slides/pdftextcompression).

--------------------

القيمة الافتراضية هي [PdfTextCompression.Flate](../../com.aspose.slides/pdftextcompression\#Flate).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getBestImagesCompressionRatio() {#getBestImagesCompressionRatio--}
```
public abstract boolean getBestImagesCompressionRatio()
```

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى true، سيُختار أفضل خوارزمية ضغط لكل صورة في العرض، ما سيؤدي إلى تقليل حجم مستند PDF الناتج.

--------------------

اختيار نسبة ضغط الصورة المثلى يتطلب حسابًا مكثفًا ويستهلك كمية إضافية من الذاكرة، وهذا الخيار غير مفعل بشكل افتراضي.

--------------------

القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setBestImagesCompressionRatio(boolean value) {#setBestImagesCompressionRatio-boolean-}
```
public abstract void setBestImagesCompressionRatio(boolean value)
```

يشير إلى ما إذا كان يجب اختيار أكثر ضغط فعّال (بدلاً من الافتراضي) لكل صورة تلقائيًا. إذا تم تعيينه إلى true، سيُختار أفضل خوارزمية ضغط لكل صورة في العرض، ما سيؤدي إلى تقليل حجم مستند PDF الناتج.

--------------------

اختيار نسبة ضغط الصورة المثلى يتطلب حسابًا مكثفًا ويستهلك كمية إضافية من الذاكرة، وهذا الخيار غير مفعل بشكل افتراضي.

--------------------

القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getEmbedTrueTypeFontsForASCII() {#getEmbedTrueTypeFontsForASCII--}
```
public abstract boolean getEmbedTrueTypeFontsForASCII()
```

صحيح لتضمين خطوط True Type لأحرف ASCII من 32 إلى 127. الخطوط لأكواد الأحرف التي تزيد عن 127 تُضمّن دائمًا. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**القيمة المرجعة:**
boolean
### setEmbedTrueTypeFontsForASCII(boolean value) {#setEmbedTrueTypeFontsForASCII-boolean-}
```
public abstract void setEmbedTrueTypeFontsForASCII(boolean value)
```

صحيح لتضمين خطوط True Type لأحرف ASCII من 32 إلى 127. الخطوط لأكواد الأحرف التي تزيد عن 127 تُضمّن دائمًا. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعة:**
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

### getAdditionalCommonFontFamilies() {#getAdditionalCommonFontFamilies--}
```
public abstract String[] getAdditionalCommonFontFamilies()
```

إرجاع أو تعيين مصفوفة من الأسماء التي يحددها المستخدم لعائلات الخطوط التي ينبغي على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[].

**القيمة المرجعة:**
java.lang.String[]
### setAdditionalCommonFontFamilies(String[] value) {#setAdditionalCommonFontFamilies-java.lang.String---}
```
public abstract void setAdditionalCommonFontFamilies(String[] value)
```

إرجاع أو تعيين مصفوفة من الأسماء التي يحددها المستخدم لعائلات الخطوط التي ينبغي على Aspose.Slides اعتبارها شائعة. قراءة/كتابة String[].

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getEmbedFullFonts() {#getEmbedFullFonts--}
```
public abstract boolean getEmbedFullFonts()
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط مجموعة فرعية مستخدمة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**القيمة المرجعة:**
boolean
### setEmbedFullFonts(boolean value) {#setEmbedFullFonts-boolean-}
```
public abstract void setEmbedFullFonts(boolean value)
```

يحدد ما إذا كان يجب تضمين جميع أحرف الخط أم فقط مجموعة فرعية مستخدمة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRasterizeUnsupportedFontStyles() {#getRasterizeUnsupportedFontStyles--}
```
public abstract boolean getRasterizeUnsupportedFontStyles()
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط النمط العريض. هذا النهج يمكن أن يحسن جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**القيمة المرجعة:**
boolean
### setRasterizeUnsupportedFontStyles(boolean value) {#setRasterizeUnsupportedFontStyles-boolean-}
```
public abstract void setRasterizeUnsupportedFontStyles(boolean value)
```

يشير إلى ما إذا كان يجب تحويل النص إلى صورة نقطية وحفظه في PDF عندما لا يدعم الخط النمط العريض. هذا النهج يمكن أن يحسن جودة النص في PDF الناتج لبعض الخطوط. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو تعيين جودة الصور داخل المستند عند الحفظ بصيغة PDF. قد تتراوح القيمة من 0 إلى 100 حيث يعني 0 أقل جودة مع أقصى ضغط و100 أفضل جودة مع أقل ضغط.

القيمة الافتراضية هي **100**.

**القيمة المرجعة:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

يؤثر فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو تعيين جودة الصور داخل المستند عند الحفظ بصيغة PDF. قد تتراوح القيمة من 0 إلى 100 حيث يعني 0 أقل جودة مع أقصى ضغط و100 أفضل جودة مع أقل ضغط.

القيمة الافتراضية هي **100**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getCompliance() {#getCompliance--}
```
public abstract int getCompliance()
```

مستوى التوافق المطلوب للمستند PDF المُنشأ. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

القيمة الافتراضية هي [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**القيمة المرجعة:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public abstract void setCompliance(int value)
```

مستوى التوافق المطلوب للمستند PDF المُنشأ. قراءة/كتابة [PdfCompliance](../../com.aspose.slides/pdfcompliance).

--------------------

القيمة الافتراضية هي [PdfCompliance.Pdf17](../../com.aspose.slides/pdfcompliance\#Pdf17).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

تعيين كلمة مرور المستخدم لحماية مستند PDF. قراءة/كتابة String.

**القيمة المرجعة:**
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

يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عندما يُفتح المستند بصلاحية المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

**القيمة المرجعة:**
int
### setAccessPermissions(int value) {#setAccessPermissions-int-}
```
public abstract void setAccessPermissions(int value)
```

يحتوي على مجموعة من العلامات التي تحدد أية أذونات وصول يجب منحها عندما يُفتح المستند بصلاحية المستخدم. راجع [PdfAccessPermissions](../../com.aspose.slides/pdfaccesspermissions).

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

صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**. يمكن أن يحتوي مستند PDF على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true، سيتم تحويل صورة الميتا المصدر إلى صيغة PNG وحفظها في PDF كصورة نقطية. إذا تم تعيينه إلى false، سيتم تحويل الميتا إلى رسومات متجهة في PDF. كل نهج له مميزات وعيوب. على سبيل المثال، إذا تم تحويل الميتا إلى PNG، قد يحدث فقدان بسيط للجودة عند تغيير حجم المستند الناتج. إذا تم تحويله إلى رسومات متجهة، قد تظهر مشكلات أداء في أدوات عرض PDF.

**القيمة المرجعة:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **true**. يمكن أن يحتوي مستند PDF على رسومات متجهة وصور نقطية. إذا تم تعيين SaveMetafilesAsPng إلى true، سيتم تحويل صورة الميتا المصدر إلى صيغة PNG وحفظها في PDF كصورة نقطية. إذا تم تعيينه إلى false، سيتم تحويل الميتا إلى رسومات متجهة في PDF. كل نهج له مميزات وعيوب. على سبيل المثال، إذا تم تحويل الميتا إلى PNG، قد يحدث فقدان بسيط للجودة عند تغيير حجم المستند الناتج. إذا تم تحويله إلى رسومات متجهة، قد تظهر مشكلات أداء في أدوات عرض PDF.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSufficientResolution() {#getSufficientResolution--}
```
public abstract float getSufficientResolution()
```

إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذا المعامل يعتمد على عدة عوامل. يحاول الخوارزمية الحصول على أفضل حجم للصورة الناتجة وفقًا لقيمة الخاصية، حجم الصورة المصدر، وحجم إطار الصورة. قد تعطي قيم خصائص مماثلة نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير مرئي.

--------------------

تؤثر الخاصية على حجم الملف، زمن التصدير، وجودة الصورة.

القيمة الافتراضية هي **96**.

**القيمة المرجعة:**
float
### setSufficientResolution(float value) {#setSufficientResolution-float-}
```
public abstract void setSufficientResolution(float value)
```

إرجاع أو تعيين قيمة تحدد دقة الصور داخل مستند PDF. قراءة/كتابة float.

القيمة: تأثير هذا المعامل يعتمد على عدة عوامل. يحاول الخوارزمية الحصول على أفضل حجم للصورة الناتجة وفقًا لقيمة الخاصية، حجم الصورة المصدر، وحجم إطار الصورة. قد تعطي قيم خصائص مماثلة نفس النتيجة. يُنصح باستخدام خطوة 16 أو 32 للحصول على تأثير مرئي.

--------------------

تؤثر الخاصية على حجم الملف، زمن التصدير، وجودة الصورة.

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

القيمة الافتراضية هي **false**.

**القيمة المرجعة:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

الحصول أو تعيين الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

الحصول أو تعيين الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract Integer getImageTransparentColor()
```

الحصول أو تعيين لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**القيمة المرجعة:**
java.lang.Integer
### setImageTransparentColor(Integer value) {#setImageTransparentColor-java.lang.Integer-}
```
public abstract void setImageTransparentColor(Integer value)
```

الحصول أو تعيين لون الشفافية للصورة.

القيمة: لون الشفافية للصورة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getApplyImageTransparent() {#getApplyImageTransparent--}
```
public abstract boolean getApplyImageTransparent()
```

يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا.

**القيمة المرجعة:**
boolean
### setApplyImageTransparent(boolean value) {#setApplyImageTransparent-boolean-}
```
public abstract void setApplyImageTransparent(boolean value)
```

يطبق لون الشفافية المحدد على صورة إذا كان صحيحًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getIncludeOleData() {#getIncludeOleData--}
```
public abstract boolean getIncludeOleData()
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في PDF الناتج. قراءة/كتابة boolean.

--------------------

> ```
> مثال:
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

القيمة الافتراضية هي **false**.

**القيمة المرجعة:**
boolean
### setIncludeOleData(boolean value) {#setIncludeOleData-boolean-}
```
public abstract void setIncludeOleData(boolean value)
```

صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في PDF الناتج. قراءة/كتابة boolean.

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

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |