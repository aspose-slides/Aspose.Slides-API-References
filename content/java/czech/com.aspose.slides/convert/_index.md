---
title: Convert
second_title: Aspose.Slides pro Java API Reference
description: Představuje skupinu metod určených k převodu.
type: docs
url: /cs/com.aspose.slides/convert/
---
**Dědičnost:**
java.lang.Object
```
public class Convert
```

Představuje skupinu metod určených pro konverzi [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) pomocí předané přípony výstupní cesty pro určení požadovaného formátu exportu. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Konvertuje vstupní prezentaci na sadu obrázků ve formátu TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Konvertuje vstupní prezentaci do formátu TIFF s vlastním nastavením. |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) pomocí předané přípony výstupní cesty pro určení požadovaného formátu exportu.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta vstupní prezentace |
| outPath | java.lang.String | Výstupní cesta |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta vstupní prezentace |
| outPath | java.lang.String | Výstupní cesta |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta vstupní prezentace |
| outPath | java.lang.String | Výstupní cesta |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Možnosti výstupního PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outPath | java.lang.String | Výstupní cesta |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do PDF.

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outPath | java.lang.String | Výstupní cesta |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Možnosti výstupního PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta vstupní prezentace |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta vstupní prezentace |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Zpětné volání vracející výstupní cestu SVG pro každý snímek v prezentaci |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Zpětné volání vracející výstupní cestu SVG pro každý snímek v prezentaci |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG.

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti exportu SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Konvertuje [Presentation](../../com.aspose.slides/presentation) do SVG.

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Zpětné volání vracející výstupní cestu SVG pro každý snímek v prezentaci |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti exportu SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outputFileName | java.lang.String | Jméno výstupního souboru. |
| imageSize | java.awt.Dimension | Velikost každého generovaného obrázku. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |
| scale | float | Faktor škálování aplikovaný na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslování. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outputFileName | java.lang.String | Jméno výstupního souboru. |
| imageSize | java.awt.Dimension | Velikost každého generovaného obrázku. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |
| scale | float | Faktor škálování aplikovaný na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti vykreslování. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Konvertuje vstupní prezentaci na sadu obrázků ve formátu TIFF. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.tiff", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.tiff", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Konvertuje vstupní prezentaci do formátu TIFF s vlastním nastavením. Pokud je zadáno jméno výstupního souboru jako "myPath/myFilename.tiff" a multipage je false, výsledek bude uložen jako sada souborů "myPath/myFilename\_N.tiff", kde N je číslo snímku. V opačném případě, pokud je multipage true, výsledek bude více-stránkový dokument "myPath/myFilename.tiff".

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
**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace. |
| outputFileName | java.lang.String | Jméno výstupního souboru. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Možnosti ukládání TIFF. |
| multipage | boolean | Určuje, zda má být generovaný dokument TIFF více-stránkový. |