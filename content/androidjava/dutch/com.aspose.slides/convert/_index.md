---
title: Convert
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om te converteren .
type: docs
url: /nl/com.aspose.slides/convert/
---
**Erfenis:**
java.lang.Object
```
public class Convert
```

Stelt een groep methoden voor die bedoeld zijn om [Presentation](../../com.aspose.slides/presentation) te converteren.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [Convert()](#Convert--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Converteert [Presentation](../../com.aspose.slides/presentation) met behulp van de opgegeven extensie van het uitvoerpad om het vereiste exportformaat te bepalen. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Converteert de invoerpresentatie naar een reeks TIFF-afbeeldingen. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) met behulp van de opgegeven extensie van het uitvoerpad om het vereiste exportformaat te bepalen.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Pad van de invoerpresentatie |
| outPath | java.lang.String | Uitvoerpad |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Pad van de invoerpresentatie |
| outPath | java.lang.String | Uitvoerpad |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Pad van de invoerpresentatie |
| outPath | java.lang.String | Uitvoerpad |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Uitvoer-PDF-opties |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Invoerpresentatie |
| outPath | java.lang.String | Uitvoerpad |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar PDF.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Invoerpresentatie |
| outPath | java.lang.String | Uitvoerpad |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Uitvoer-PDF-opties |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Pad van de invoerpresentatie |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Pad van de invoerpresentatie |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback die het SVG-uitvoerpad retourneert voor elke dia in de presentatie |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Invoerpresentatie |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback die het SVG-uitvoerpad retourneert voor elke dia in de presentatie |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Invoerpresentatie |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-exportopties |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Invoerpresentatie |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback die het SVG-uitvoerpad retourneert voor elke dia in de presentatie |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-exportopties |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.jpeg", waarbij N een slide-nummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.jpeg", waarbij N een slide-nummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |
| imageSize | [Size](../../com.aspose.slides.android/size) | De afmeting van elke gegenereerde afbeelding. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.jpeg", waarbij N een slide-nummer is.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |
| scale | float | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke dia-grootte. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | De renderopties. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.png", waarbij N een slide-nummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.png", waarbij N een slide-nummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |
| imageSize | [Size](../../com.aspose.slides.android/size) | De afmeting van elke gegenereerde afbeelding. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.png", waarbij N een slide-nummer is.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |
| scale | float | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke dia-grootte. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | De renderopties. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Converteert de invoerpresentatie naar een reeks TIFF-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.tiff", wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.tiff", waarbij N een slide-nummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.tiff" en multipage is false, wordt het resultaat opgeslagen als een reeks bestanden "myPath/myFilename\_N.tiff", waarbij N een slide-nummer is. Anders, als multipage true is, wordt het resultaat een meer-pagina “myPath/myFilename.tiff”-document.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De invoerpresentatie. |
| outputFileName | java.lang.String | De bestandsnaam voor de uitvoer. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | De TIFF-opslaagopties. |
| multipage | boolean | Geeft aan of het gegenereerde TIFF-document een meer-pagina document moet zijn. |