---
title: Convert
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un gruppo di metodi destinati a convertire .
type: docs
url: /it/com.aspose.slides/convert/
---
**Ereditarietà:**
java.lang.Object
```
public class Convert
```

Rappresenta un gruppo di metodi destinati a convertire [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) utilizzando l'estensione del percorso di output fornita per determinare il formato di esportazione richiesto. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) in PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Converte [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Converte [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Converte [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Converte [Presentation](../../com.aspose.slides/presentation) in SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Converte la presentazione di input in un insieme di immagini in formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converte la presentazione di input in un insieme di immagini in formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converte la presentazione di input in un insieme di immagini in formato JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Converte la presentazione di input in un insieme di immagini in formato PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converte la presentazione di input in un insieme di immagini in formato PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converte la presentazione di input in un insieme di immagini in formato PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Converte la presentazione di input in un insieme di immagini in formato TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Converte la presentazione di input in formato TIFF con opzioni personalizzate. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) utilizzando l'estensione del percorso di output fornita per determinare il formato di esportazione richiesto.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | java.lang.String | Percorso della presentazione di input |
| outPath | java.lang.String | Percorso di output |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | java.lang.String | Percorso della presentazione di input |
| outPath | java.lang.String | Percorso di output |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | java.lang.String | Percorso della presentazione di input |
| outPath | java.lang.String | Percorso di output |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opzioni PDF di output |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) in PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione di input |
| outPath | java.lang.String | Percorso di output |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) in PDF.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione di input |
| outPath | java.lang.String | Percorso di output |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opzioni PDF di output |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) in SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | java.lang.String | Percorso della presentazione di input |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) in SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presPath | java.lang.String | Percorso della presentazione di input |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Converte [Presentation](../../com.aspose.slides/presentation) in SVG.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione di input |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) in SVG.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione di input |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di esportazione SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Converte [Presentation](../../com.aspose.slides/presentation) in SVG.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentazione di input |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback che restituisce il percorso di output SVG per ogni diapositiva nella presentazione |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opzioni di esportazione SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Converte la presentazione di input in un insieme di immagini in formato JPEG. Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Converte la presentazione di input in un insieme di immagini in formato JPEG. Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input |
| outputFileName | java.lang.String | Il nome del file di output. |
| imageSize | [Size](../../com.aspose.slides.android/size) | La dimensione di ogni immagine generata. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converte la presentazione di input in un insieme di immagini in formato JPEG. Se il nome del file di output è fornito come "myPath/myFilename.jpeg", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.jpeg", dove N è il numero della diapositiva.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |
| scale | float | Il fattore di scala applicato alle immagini di output rispetto alle dimensioni originali della diapositiva. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Le opzioni di rendering. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Converte la presentazione di input in un insieme di immagini in formato PNG. Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Converte la presentazione di input in un insieme di immagini in formato PNG. Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input |
| outputFileName | java.lang.String | Il nome del file di output. |
| imageSize | [Size](../../com.aspose.slides.android/size) | La dimensione di ogni immagine generata. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Converte la presentazione di input in un insieme di immagini in formato PNG. Se il nome del file di output è fornito come "myPath/myFilename.png", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.png", dove N è il numero della diapositiva.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |
| scale | float | Il fattore di scala applicato alle immagini di output rispetto alle dimensioni originali della diapositiva. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Le opzioni di rendering. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Converte la presentazione di input in un insieme di immagini in formato TIFF. Se il nome del file di output è fornito come "myPath/myFilename.tiff", il risultato verrà salvato come un insieme di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Converte la presentazione di input in formato TIFF con opzioni personalizzate. Se il nome del file di output è fornito come "myPath/myFilename.tiff" e multipage è false, il risultato verrà salvato come un insieme di file "myPath/myFilename_N.tiff", dove N è il numero della diapositiva. Altrimenti, se multipage è true, il risultato sarà un documento multipagina "myPath/myFilename.tiff".

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentazione di input. |
| outputFileName | java.lang.String | Il nome del file di output. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Le opzioni di salvataggio TIFF. |
| multipage | boolean | Specifica se il documento TIFF generato deve essere multipagina. |