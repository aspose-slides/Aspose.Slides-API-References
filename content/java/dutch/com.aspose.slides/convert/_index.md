---
title: Convert
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om te converteren.
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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Convert()](#Convert--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Converteert [Presentation](../../com.aspose.slides/presentation) met behulp van de doorgegeven outputpad-extensie om het vereiste exportformaat te bepalen. |
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
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. |
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


Converteert [Presentation](../../com.aspose.slides/presentation) met behulp van de doorgegeven outputpad-extensie om het vereiste exportformaat te bepalen.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |

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
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |

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
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Output PDF options |

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| outPath | java.lang.String | Output path |

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| outPath | java.lang.String | Output path |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Output PDF options |

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
| presPath | java.lang.String | Path of the input presentation |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Converteert [Presentation](../../com.aspose.slides/presentation) naar SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG export options |

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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG export options |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.jpeg"-bestanden, waarbij N een slidennummer is.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.jpeg"-bestanden, waarbij N een slidennummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation |
| outputFileName | java.lang.String | The output file name. |
| imageSize | java.awt.Dimension | The size of each generated image. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.jpeg", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.jpeg"-bestanden, waarbij N een slidennummer is.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | The rendering options. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.png"-bestanden, waarbij N een slidennummer is.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```


Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.png"-bestanden, waarbij N een slidennummer is.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation |
| outputFileName | java.lang.String | The output file name. |
| imageSize | java.awt.Dimension | The size of each generated image. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Converteert de invoerpresentatie naar een reeks PNG-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.png"-bestanden, waarbij N een slidennummer is.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | The rendering options. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Converteert de invoerpresentatie naar een reeks TIFF-afbeeldingen. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.tiff", wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.tiff"-bestanden, waarbij N een slidennummer is.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.tiff" en multipage false is, wordt het resultaat opgeslagen als een reeks "myPath/myFilename\_N.tiff"-bestanden, waarbij N een slidennummer is. Anders, als multipage true is, wordt het resultaat een meerpagina "myPath/myFilename.tiff"-document.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | The TIFF saving options. |
| multipage | boolean | Specifies whether the generated TIFF document should be a multi-page. |