---
title: Convert
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر گروهی از متدهایی است که برای تبدیل . در نظر گرفته شده‌اند.
type: docs
url: /fa/com.aspose.slides/convert/
---
**ارث‌بری:**
java.lang.Object
```
public class Convert
```

نمایانگر یک گروه از متدهایی است که برای تبدیل [Presentation](../../com.aspose.slides/presentation) در نظر گرفته شده‌اند.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## سازنده‌ها

| سازنده | شرح |
| --- | --- |
| [Convert()](#Convert--) |  |

## متدها

| متد | شرح |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) را با استفاده از پسوند مسیر خروجی داده شده برای تعیین فرمت خروجی مورد نیاز تبدیل می‌کند. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت TIFF تبدیل می‌کند. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | ارائه‌ ورودی را به فرمت TIFF با گزینه‌های سفارشی تبدیل می‌کند. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) را با استفاده از پسوند مسیر خروجی داده شده برای تعیین فرمت خروجی مورد نیاز تبدیل می‌کند.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | java.lang.String | مسیر ارائه ورودی |
| outPath | java.lang.String | مسیر خروجی |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | java.lang.String | مسیر ارائه ورودی |
| outPath | java.lang.String | مسیر خروجی |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | java.lang.String | مسیر ارائه ورودی |
| outPath | java.lang.String | مسیر خروجی |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | گزینه‌های خروجی PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outPath | java.lang.String | مسیر خروجی |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) را به PDF تبدیل می‌کند.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outPath | java.lang.String | مسیر خروجی |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | گزینه‌های خروجی PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

[Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | java.lang.String | مسیر ارائه ورودی |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presPath | java.lang.String | مسیر ارائه ورودی |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback که مسیر خروجی SVG را برای هر اسلاید ارائه بازمی‌گرداند |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback که مسیر خروجی SVG را برای هر اسلاید ارائه بازمی‌گرداند |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های خروجی SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) را به SVG تبدیل می‌کند.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback که مسیر خروجی SVG را برای هر اسلاید ارائه بازمی‌گرداند |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های خروجی SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.jpeg" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.jpeg" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |
| imageSize | java.awt.Dimension | اندازه هر تصویر تولید شده |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت JPEG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.jpeg" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |
| scale | float | ضریب مقیاس اعمال‌شده به تصاویر خروجی نسبت به اندازهٔ اسلاید اصلی |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.png" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.png" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |
| imageSize | java.awt.Dimension | اندازه هر تصویر تولید شده |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت PNG تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.png" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.png" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |
| scale | float | ضریب مقیاس اعمال‌شده به تصاویر خروجی نسبت به اندازهٔ اسلاید اصلی |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | گزینه‌های رندرینگ |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

ارائه‌ ورودی را به مجموعه‌ای از تصاویر فرمت TIFF تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.tiff" داده شود، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.tiff" فایل‌ها ذخیره می‌شود که N شماره اسلاید است.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

ارائه‌ ورودی را به فرمت TIFF با گزینه‌های سفارشی تبدیل می‌کند. اگر نام فایل خروجی به صورت "myPath/myFilename.tiff" داده شود و multipage برابر false باشد، نتیجه به صورت مجموعه‌ای از "myPath/myFilename_N.tiff" فایل‌ها ذخیره می‌شود که N شماره اسلاید است. در غیر این صورت، اگر multipage برابر true باشد، نتیجه یک سند چندصفحه‌ای "myPath/myFilename.tiff" خواهد بود.

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
**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | ارائه‌ ورودی |
| outputFileName | java.lang.String | نام فایل خروجی |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | گزینه‌های ذخیره‌سازی TIFF |
| multipage | boolean | مشخص می‌کند که آیا سند TIFF تولید شده باید چندصفحه‌ای باشد یا نه |
