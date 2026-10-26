---
title: Convert
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Gruppe von Methoden dar, die zum Konvertieren bestimmt sind.
type: docs
url: /de/com.aspose.slides/convert/
---
**Vererbung:**
java.lang.Object
```
public class Convert
```

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, [Presentation](../../com.aspose.slides/presentation) zu konvertieren.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Convert()](#Convert--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) mit der übergebenen Ausgabepfad-Erweiterung, um das erforderliche Exportformat zu bestimmen. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Konvertiert die Eingabepraesentation in einen Satz von TIFF-Format-Bildern. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Konvertiert die Eingabepraesentation in das TIFF-Format mit benutzerdefinierten Optionen. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) mit der übergebenen Ausgabepfad-Erweiterung, um das erforderliche Exportformat zu bestimmen.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | java.lang.String | Pfad der Eingabepraesentation |
| outPath | java.lang.String | Ausgabepfad |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | java.lang.String | Pfad der Eingabepraesentation |
| outPath | java.lang.String | Ausgabepfad |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | java.lang.String | Pfad der Eingabepraesentation |
| outPath | java.lang.String | Ausgabepfad |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Ausgabe-PDF-Optionen |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Eingabepraesentation |
| outPath | java.lang.String | Ausgabepfad |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in PDF.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Eingabepraesentation |
| outPath | java.lang.String | Ausgabepfad |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Ausgabe-PDF-Optionen |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | java.lang.String | Pfad der Eingabepraesentation |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| presPath | java.lang.String | Pfad der Eingabepraesentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, der den SVG-Ausgabepfad für jede Folie in der Praesentation zurückgibt |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Eingabepraesentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, der den SVG-Ausgabepfad für jede Folie in der Praesentation zurückgibt |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Eingabepraesentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-Export-Optionen |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Konvertiert [Presentation](../../com.aspose.slides/presentation) in SVG.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Eingabepraesentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, der den SVG-Ausgabepfad für jede Folie in der Praesentation zurückgibt |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG-Export-Optionen |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N die Foliennummer ist.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N die Foliennummer ist.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation |
| outputFileName | java.lang.String | Der Ausgabedateiname. |
| imageSize | java.awt.Dimension | Die Größe jedes erzeugten Bildes. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konvertiert die Eingabepraesentation in einen Satz von JPEG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.jpeg" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.jpeg"-Dateien gespeichert, wobei N die Foliennummer ist.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |
| scale | float | Der Skalierungsfaktor, der auf die Ausgabebilder relativ zur Originalfoliengröße angewendet wird. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Die Rendering-Optionen. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation |
| outputFileName | java.lang.String | Der Ausgabedateiname. |
| imageSize | java.awt.Dimension | Die Größe jedes erzeugten Bildes. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konvertiert die Eingabepraesentation in einen Satz von PNG-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.png" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.png"-Dateien gespeichert, wobei N die Foliennummer ist.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |
| scale | float | Der Skalierungsfaktor, der auf die Ausgabebilder relativ zur Originalfoliengröße angewendet wird. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Die Rendering-Optionen. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Konvertiert die Eingabepraesentation in einen Satz von TIFF-Format-Bildern. Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird, wird das Ergebnis als ein Satz von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N die Foliennummer ist.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Konvertiert die Eingabepraesentation in das TIFF-Format mit benutzerdefinierten Optionen. Wenn der Ausgabedateiname als "myPath/myFilename.tiff" angegeben wird und multipage false ist, wird das Ergebnis als ein Satz von "myPath/myFilename_N.tiff"-Dateien gespeichert, wobei N die Foliennummer ist. Andernfalls, wenn multipage true ist, ergibt das Ergebnis ein mehrseitiges "myPath/myFilename.tiff"-Dokument.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Eingabepraesentation. |
| outputFileName | java.lang.String | Der Ausgabedateiname. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Die TIFF-Speicheroptionen. |
| multipage | boolean | Gibt an, ob das erzeugte TIFF-Dokument mehrseitig sein soll. |