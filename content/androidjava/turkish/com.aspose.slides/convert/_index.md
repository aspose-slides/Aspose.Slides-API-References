---
title: Convert
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Dönüştürmeyi amaçlayan bir grup yöntemi temsil eder.
type: docs
url: /tr/com.aspose.slides/convert/
---
**Kalıtım:**
java.lang.Object
```
public class Convert
```

[Presentation](../../com.aspose.slides/presentation)'yi dönüştürmeyi amaçlayan bir grup yöntemi temsil eder.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Convert()](#Convert--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)'yi verilen çıktı yolu uzantısını kullanarak gerekli dışa aktarma formatını belirler. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Girdi sunumunu bir dizi TIFF formatında görüntüye dönüştürür. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Girdi sunumunu özel seçeneklerle TIFF formatına dönüştürür. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi verilen çıktı yolu uzantısını kullanarak gerekli dışa aktarma formatını belirler.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | java.lang.String | Giriş sunumunun yolu |
| outPath | java.lang.String | Çıktı yolu |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | java.lang.String | Giriş sunumunun yolu |
| outPath | java.lang.String | Çıktı yolu |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | java.lang.String | Giriş sunumunun yolu |
| outPath | java.lang.String | Çıktı yolu |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Çıktı PDF seçenekleri |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| outPath | java.lang.String | Çıktı yolu |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation)'yi PDF'ye dönüştürür.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| outPath | java.lang.String | Çıktı yolu |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Çıktı PDF seçenekleri |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | java.lang.String | Giriş sunumunun yolu |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| presPath | java.lang.String | Giriş sunumunun yolu |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG dışa aktarma seçenekleri |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation)'yi SVG'ye dönüştürür.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Sunumdaki her slayt için SVG çıktı yolunu döndüren geri çağırma |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG dışa aktarma seçenekleri |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| outputFileName | java.lang.String | Çıktı dosya adı. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Her oluşturulan görüntünün boyutu. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Girdi sunumunu bir dizi JPEG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.jpeg" olarak verilirse, sonuç "myPath/myFilename_N.jpeg" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |
| scale | float | Orijinal slayt boyutuna göre çıktı görüntülerine uygulanacak ölçek faktörü. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu |
| outputFileName | java.lang.String | Çıktı dosya adı. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Her oluşturulan görüntünün boyutu. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Girdi sunumunu bir dizi PNG formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.png" olarak verilirse, sonuç "myPath/myFilename_N.png" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |
| scale | float | Orijinal slayt boyutuna göre çıktı görüntülerine uygulanacak ölçek faktörü. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Render seçenekleri. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Girdi sunumunu bir dizi TIFF formatında görüntüye dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse, sonuç "myPath/myFilename_N.tiff" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Girdi sunumunu özel seçeneklerle TIFF formatına dönüştürür. Çıktı dosya adı "myPath/myFilename.tiff" olarak verilirse ve multipage false ise, sonuç "myPath/myFilename_N.tiff" dosyaları kümesi olarak kaydedilir; burada N bir slayt numarasıdır. Aksi takdirde, multipage true ise, sonuç çok sayfalı bir "myPath/myFilename.tiff" belgesi olur.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Giriş sunumu. |
| outputFileName | java.lang.String | Çıktı dosya adı. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF kaydetme seçenekleri. |
| multipage | boolean | Oluşturulan TIFF belgesinin çok sayfalı olup olmayacağını belirtir. |