---
title: Convert
second_title: Aspose.Slides Java API referencia
description: Egy olyan metóduscsoportot képvisel, amely a konvertálásra szolgál.
type: docs
url: /hu/com.aspose.slides/convert/
---
**Öröklés:**
java.lang.Object
```
public class Convert
```

Egy olyan metóduscsoportot képvisel, amely a [Presentation](../../com.aspose.slides/presentation) átalakítására szolgál.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) a megadott kimeneti útvonal kiterjesztésének felhasználásával a szükséges exportformátum meghatározásához. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti prezentációt TIFF formátumú képek egy sorozatává. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Átalakítja a bemeneti prezentációt TIFF formátumba egyedi beállításokkal. |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) a megadott kimeneti útvonal kiterjesztésének felhasználásával a szükséges exportformátum meghatározásához.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti prezentáció elérési útja |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti prezentáció elérési útja |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti prezentáció elérési útja |
| outPath | java.lang.String | Kimeneti útvonal |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Kimeneti PDF beállítások |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti prezentáció |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti prezentáció |
| outPath | java.lang.String | Kimeneti útvonal |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Kimeneti PDF beállítások |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti prezentáció elérési útja |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti prezentáció elérési útja |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely minden diához visszaadja az SVG kimeneti útvonalat |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti prezentáció |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely minden diához visszaadja az SVG kimeneti útvonalat |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti prezentáció |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG exportálási beállítások |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Átalakítja a [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti prezentáció |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely minden diához visszaadja az SVG kimeneti útvonalat |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG exportálási beállítások |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formájában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol az N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formájában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol az N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| imageSize | java.awt.Dimension | Az egyes létrehozott képek mérete. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Átalakítja a bemeneti prezentációt JPEG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formájában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol az N a dia száma.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| scale | float | A kimeneti képekre alkalmazott skálázási tényező az eredeti diák méretéhez képest. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | A renderelési beállítások. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formájában van megadva, az eredmény "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol az N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formájában van megadva, az eredmény "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol az N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| imageSize | java.awt.Dimension | Az egyes létrehozott képek mérete. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Átalakítja a bemeneti prezentációt PNG formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formájában van megadva, az eredmény "myPath/myFilename_N.png" fájlok sorozataként lesz mentve, ahol az N a dia száma.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| scale | float | A kimeneti képekre alkalmazott skálázási tényező az eredeti diák méretéhez képest. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | A renderelési beállítások. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Átalakítja a bemeneti prezentációt TIFF formátumú képek egy sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.tiff" formájában van megadva, az eredmény "myPath/myFilename_N.tiff" fájlok sorozataként lesz mentve, ahol az N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Átalakítja a bemeneti prezentációt TIFF formátumba egyedi beállításokkal. Ha a kimeneti fájlnév "myPath/myFilename.tiff" és a multipage false, az eredmény "myPath/myFilename_N.tiff" fájlok sorozataként lesz mentve, ahol az N a dia száma. Egyébként, ha a multipage true, az eredmény egy többoldalas "myPath/myFilename.tiff" dokumentum lesz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti prezentáció. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | A TIFF mentési beállítások. |
| multipage | boolean | Meghatározza, hogy a létrehozott TIFF dokumentum többoldalas legyen-e. |