---
title: Convert
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من الأساليب المقصودة لتحويل .
type: docs
url: /ar/com.aspose.slides/convert/
---
**الوراثة:**
java.lang.Object
```
public class Convert
```

يمثل مجموعة من الأساليب المخصصة لتحويل [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## المنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Convert()](#Convert--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) باستخدام امتداد مسار الإخراج الممرّر لتحديد تنسيق التصدير المطلوب. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | يقوم بتحويل العرض التقديمي المدخل إلى تنسيق TIFF مع خيارات مخصصة. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) باستخدام امتداد مسار الإخراج الممرّر لتحديد تنسيق التصدير المطلوب.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |
| outPath | java.lang.String | مسار الإخراج |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |
| outPath | java.lang.String | مسار الإخراج |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |
| outPath | java.lang.String | مسار الإخراج |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | خيارات PDF للإخراج |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outPath | java.lang.String | مسار الإخراج |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outPath | java.lang.String | مسار الإخراج |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | خيارات PDF للإخراج |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة استرجاعية تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة استرجاعية تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات تصدير SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      }, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة استرجاعية تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات تصدير SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم كل صورة مُنشأة. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| scale | float | عامل القياس المطبق على صور الإخراج نسبةً إلى حجم الشريحة الأصلي. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| imageSize | [Size](../../com.aspose.slides.android/size) | حجم كل صورة مُنشأة. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| scale | float | عامل القياس المطبق على صور الإخراج نسبةً إلى حجم الشريحة الأصلي. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات العرض. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور تنسيق TIFF. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff"، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.tiff"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

يقوم بتحويل العرض التقديمي المدخل إلى تنسيق TIFF مع خيارات مخصصة. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff" وكان multipage يساوي false، سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename\_N.tiff"، حيث N هو رقم الشريحة. وإلا إذا كان multipage يساوي true، ستكون النتيجة مستند TIFF متعدد الصفحات "myPath/myFilename.tiff".

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات حفظ TIFF. |
| multipage | boolean | يحدد ما إذا كان مستند TIFF المُنتج يجب أن يكون متعدد الصفحات. |