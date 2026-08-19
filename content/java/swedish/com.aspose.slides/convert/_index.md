---
title: Convert
second_title: Aspose.Slides för Java API-referens
description: Representerar en grupp av metoder avsedda att konvertera .
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

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) med den angivna filändelsen på utdata-sökvägen för att bestämma det erforderliga exportformatet. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till ett set av PNG-formatbilder. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konverterar inmatningspresentationen till ett set av PNG-formatbilder. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konverterar inmatningspresentationen till ett set av PNG-formatbilder. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Konverterar inmatningspresentationen till ett set av TIFF-formatbilder. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Konverterar inmatningspresentationen till TIFF-format med anpassade alternativ. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Konverterar [Presentation](../../com.aspose.slides/presentation) med den angivna filändelsen på utdata-sökvägen för att bestämma det erforderliga exportformatet.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| outPath | java.lang.String | Utdata-sökväg |

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
| outPath | java.lang.String | Utdata-sökväg |

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
| outPath | java.lang.String | Utdata-sökväg |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Utdata-PDF-alternativ |

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
| outPath | java.lang.String | Utdata-sökväg |

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
| outPath | java.lang.String | Utdata-sökväg |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Utdata-PDF-alternativ |

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
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presPath | java.lang.String | Sökväg till inmatningspresentationen |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Återanropsfunktion som returnerar SVG-utdata-sökvägen för varje bild i presentationen |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Konverterar [Presentation](../../com.aspose.slides/presentation) till SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Återanropsfunktion som returnerar SVG-utdata-sökvägen för varje bild i presentationen |

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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Återanropsfunktion som returnerar SVG-utdata-sökvägen för varje bild i presentationen |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-exportalternativ |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som ett set av "myPath/myFilename\_N.jpeg"-filer, där N är bildens nummer.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```


Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som ett set av "myPath/myFilename\_N.jpeg"-filer, där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentationen |
| outputFileName | java.lang.String | Utdata-filnamnet. |
| imageSize | java.awt.Dimension | Storleken på varje genererad bild. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Konverterar inmatningspresentationen till ett set av JPEG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.jpeg" sparas resultatet som ett set av "myPath/myFilename\_N.jpeg"-filer, där N är bildens nummer.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |
| scale | float | Skalningsfaktor som appliceras på de genererade bilderna i förhållande till originalbildens storlek. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Konverterar inmatningspresentationen till ett set av PNG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.png" sparas resultatet som ett set av "myPath/myFilename\_N.png"-filer, där N är bildens nummer.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```


Konverterar inmatningspresentationen till ett set av PNG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.png" sparas resultatet som ett set av "myPath/myFilename\_N.png"-filer, där N är bildens nummer.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Inmatningspresentation |
| outputFileName | java.lang.String | Utdata-filnamnet. |
| imageSize | java.awt.Dimension | Storleken på varje genererad bild. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Konverterar inmatningspresentationen till ett set av PNG-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.png" sparas resultatet som ett set av "myPath/myFilename\_N.png"-filer, där N är bildens nummer.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |
| scale | float | Skalningsfaktor som appliceras på de genererade bilderna i förhållande till originalbildens storlek. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Konverterar inmatningspresentationen till ett set av TIFF-formatbilder. Om utdata-filnamnet anges som "myPath/myFilename.tiff" sparas resultatet som ett set av "myPath/myFilename\_N.tiff"-filer, där N är bildens nummer.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Konverterar inmatningspresentationen till TIFF-format med anpassade alternativ. Om utdata-filnamnet anges som "myPath/myFilename.tiff" och multipage är false, sparas resultatet som ett set av "myPath/myFilename\_N.tiff"-filer, där N är bildens nummer. Annars, om multipage är true, blir resultatet ett flersidigt "myPath/myFilename.tiff"-dokument.

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
| outputFileName | java.lang.String | Utdata-filnamnet. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF-sparalternativ. |
| multipage | boolean | Anger om det genererade TIFF-dokumentet ska vara flersidigt. |