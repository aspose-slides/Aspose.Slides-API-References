---
title: Convert
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة من الطرق التي تهدف إلى تحويل .
type: docs
url: /ar/com.aspose.slides/convert/
---
**الوراثة:**
java.lang.Object
```
public class Convert
```

يمثل مجموعة من الطرق تهدف إلى تحويل [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## المُنشئات

| Constructor | الوصف |
| --- | --- |
| [Convert()](#Convert--) |  |
## الأساليب

| Method | الوصف |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) باستخدام امتداد مسار الإخراج الممرر لتحديد صيغة التصدير المطلوبة. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | يقوم بتحويل العرض التقديمي المدخل إلى صيغة TIFF بخيارات مخصصة. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) باستخدام امتداد مسار الإخراج الممرر لتحديد صيغة التصدير المطلوبة.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**المعلمات:**
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
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
| Parameter | Type | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**المعلمات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| presPath | java.lang.String | مسار العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة رد نداء تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

يقوم بتحويل [Presentation](../../com.aspose.slides/presentation) إلى SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة رد نداء تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |

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
| Parameter | Type | الوصف |
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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | دالة رد نداء تُعيد مسار إخراج SVG لكل شريحة في العرض التقديمي |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات تصدير SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| imageSize | java.awt.Dimension | حجم كل صورة مُولدة. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة JPEG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.jpeg"، حيث N هو رقم الشريحة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| scale | float | عامل التحجيم المطبق على صور الإخراج نسبةً إلى حجم الشريحة الأصلي. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| imageSize | java.awt.Dimension | حجم كل صورة مُولدة. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.png"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.png"، حيث N هو رقم الشريحة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| scale | float | عامل التحجيم المطبق على صور الإخراج نسبةً إلى حجم الشريحة الأصلي. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | خيارات التصيير. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة TIFF. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff"، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.tiff"، حيث N هو رقم الشريحة.

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

يقوم بتحويل العرض التقديمي المدخل إلى صيغة TIFF بخيارات مخصصة. إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff" وكان multipage غير مفعل (false)، فإن النتيجة ستحفظ كمجموعة من الملفات "myPath/myFilename\_N.tiff"، حيث N هو رقم الشريحة. أما إذا كان multipage مفعلاً (true)، فستكون النتيجة مستند TIFF متعدد الصفحات باسم "myPath/myFilename.tiff".

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
| Parameter | Type | الوصف |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | العرض التقديمي المدخل. |
| outputFileName | java.lang.String | اسم ملف الإخراج. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | خيارات حفظ TIFF. |
| multipage | boolean | حدد ما إذا كان مستند TIFF الناتج يجب أن يكون متعدد الصفحات. |