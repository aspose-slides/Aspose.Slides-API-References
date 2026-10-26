---
title: Convert
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un groupe de méthodes destinées à convertir .
type: docs
url: /fr/com.aspose.slides/convert/
---
**Héritage:**
java.lang.Object
```
public class Convert
```

Représente un groupe de méthodes destinées à convertir [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Convert()](#Convert--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Convertit [Presentation](../../com.aspose.slides/presentation) en utilisant l'extension de chemin de sortie fournie pour déterminer le format d'exportation requis. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Convertit [Presentation](../../com.aspose.slides/presentation) en PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Convertit [Presentation](../../com.aspose.slides/presentation) en PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Convertit [Presentation](../../com.aspose.slides/presentation) en PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Convertit [Presentation](../../com.aspose.slides/presentation) en PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Convertit [Presentation](../../com.aspose.slides/presentation) en SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Convertit [Presentation](../../com.aspose.slides/presentation) en SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Convertit [Presentation](../../com.aspose.slides/presentation) en SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Convertit [Presentation](../../com.aspose.slides/presentation) en SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Convertit [Presentation](../../com.aspose.slides/presentation) en SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Convertit la présentation d'entrée en un ensemble d'images au format TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Convertit la présentation d'entrée au format TIFF avec des options personnalisées. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en utilisant l'extension de chemin de sortie fournie pour déterminer le format d'exportation requis.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Chemin de la présentation d'entrée |
| outPath | java.lang.String | Chemin de sortie |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Chemin de la présentation d'entrée |
| outPath | java.lang.String | Chemin de sortie |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Chemin de la présentation d'entrée |
| outPath | java.lang.String | Chemin de sortie |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Options de sortie PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation d'entrée |
| outPath | java.lang.String | Chemin de sortie |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en PDF.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation d'entrée |
| outPath | java.lang.String | Chemin de sortie |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Options de sortie PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Chemin de la présentation d'entrée |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Chemin de la présentation d'entrée |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation d'entrée |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en SVG.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation d'entrée |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options d'exportation SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Convertit [Presentation](../../com.aspose.slides/presentation) en SVG.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Présentation d'entrée |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Fonction de rappel qui renvoie le chemin de sortie SVG pour chaque diapositive de la présentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Options d'exportation SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.jpeg", où N est le numéro de la diapositive.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.jpeg", où N est le numéro de la diapositive.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |
| imageSize | java.awt.Dimension | La taille de chaque image générée. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.jpeg", où N est le numéro de la diapositive.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |
| scale | float | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille originale de la diapositive. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Les options de rendu. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.png", où N est le numéro de la diapositive.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. }

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.png", où N est le numéro de la diapositive.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |
| imageSize | java.awt.Dimension | La taille de chaque image générée. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Convertit la présentation d'entrée en un ensemble d'images au format PNG. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.png", où N est le numéro de la diapositive.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |
| scale | float | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille originale de la diapositive. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Les options de rendu. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Convertit la présentation d'entrée en un ensemble d'images au format TIFF. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.tiff", où N est le numéro de la diapositive.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. }

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Convertit la présentation d'entrée au format TIFF avec des options personnalisées. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff" et que multipage est false, le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename\_N.tiff", où N est le numéro de la diapositive. Sinon, si multipage est true, le résultat sera un document "myPath/myFilename.tiff" multi-pages.

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

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La présentation d'entrée. |
| outputFileName | java.lang.String | Le nom du fichier de sortie. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Les options d'enregistrement TIFF. |
| multipage | boolean | Spécifie si le document TIFF généré doit être multi-pages.