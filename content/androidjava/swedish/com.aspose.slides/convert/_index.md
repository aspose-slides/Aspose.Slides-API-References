---
title: Convert
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en grupp metoder avsedda att konvertera.
type: docs
url: /sv/com.aspose.slides/convert/
---
**Arv:**
java.lang.Object
```
public class Convert
```

Representerar en grupp metoder avsedda att konvertera [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) med den angivna utgångssökvägsslutet för att bestämma det erforderliga exportformatet. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till en uppsättning JPEG-formatbilder. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Konverterar inmatningspresentationen till en uppsättning JPEG-formatbilder. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konverterar inmatningspresentationen till en uppsättning JPEG-formatbilder. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till en uppsättning PNG-formatbilder. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Konverterar inmatningspresentationen till en uppsättning PNG-formatbilder. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konverterar inmatningspresentationen till en uppsättning PNG-formatbilder. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till en uppsättning TIFF-formatbilder. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Konverterar inmatningspresentationen till TIFF-format med anpassade alternativ. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) med den angivna utgångssökvägsslutet för att bestämma det erforderliga exportformatet.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| outPath | java.lang.String | Utgångssökväg |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| outPath | java.lang.String | Utgångssökväg |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| outPath | java.lang.String | Utgångssökväg |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Alternativ för utdata-PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| outPath | java.lang.String | Utgångssökväg |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| outPath | java.lang.String | Utgångssökväg |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Alternativ för utdata-PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Tillbakakallning som returnerar SVG-utgångssökvägen för varje bild i presentationen |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Tillbakakallning som returnerar SVG-utgångssökvägen för varje bild i presentationen |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-exportalternativ |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Tillbakakallning som returnerar SVG-utgångssökvägen för varje bild i presentationen |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-exportalternativ |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Konverterar den inmatningspresentationen till en uppsättning JPEG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Konverterar den inmatningspresentationen till en uppsättning JPEG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen |
| outputFileName | java.lang.String | Utdatasfilnamnet. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på varje genererad bild. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konverterar den inmatningspresentationen till en uppsättning JPEG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |
| scale | float | Skalningsfaktorn som tillämpas på de genererade bilderna i förhållande till originalbildens storlek. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Konverterar den inmatningspresentationen till en uppsättning PNG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Konverterar den inmatningspresentationen till en uppsättning PNG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen |
| outputFileName | java.lang.String | Utdatasfilnamnet. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på varje genererad bild. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konverterar den inmatningspresentationen till en uppsättning PNG-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.png" sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |
| scale | float | Skalningsfaktorn som tillämpas på de genererade bilderna i förhållande till originalbildens storlek. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Konverterar den inmatningspresentationen till en uppsättning TIFF-formatbilder. Om utdatasfilnamnet anges som "myPath/myFilename.tiff" sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Konverterar den inmatningspresentationen till TIFF-format med anpassade alternativ. Om utdatasfilnamnet anges som "myPath/myFilename.tiff" och multipage är falskt sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är bildens nummer. Annars, om multipage är sant, blir resultatet ett flersidigt dokument "myPath/myFilename.tiff".

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen. |
| outputFileName | java.lang.String | Utdatasfilnamnet. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF-sparalternativ. |
| multipage | boolean | Anger om det genererade TIFF-dokumentet ska vara flersidigt. |