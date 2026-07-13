---
title: Convert
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje skupinu metod určených k převodu.
type: docs
url: /cs/com.aspose.slides/convert/
---
**Dědičnost:**
java.lang.Object
```
public class Convert
```

Reprezentuje skupinu metod určených k převodu [Presentation](../../com.aspose.slides/presentation).

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
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Převádí [Presentation](../../com.aspose.slides/presentation) pomocí předaného rozšíření výstupní cesty pro určení požadovaného exportního formátu. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Převádí [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Převádí [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Převádí [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Převádí [Presentation](../../com.aspose.slides/presentation) do PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Převádí [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Převádí [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Převádí [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Převádí [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Převádí [Presentation](../../com.aspose.slides/presentation) do SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Převádí vstupní prezentaci do formátu TIFF s vlastními možnostmi. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Převádí [Presentation](../../com.aspose.slides/presentation) pomocí předaného rozšíření výstupní cesty pro určení požadovaného exportního formátu.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta ke vstupní prezentaci |
| outPath | java.lang.String | Výstupní cesta |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta ke vstupní prezentaci |
| outPath | java.lang.String | Výstupní cesta |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta ke vstupní prezentaci |
| outPath | java.lang.String | Výstupní cesta |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Možnosti výstupního PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do PDF.

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


Převádí [Presentation](../../com.aspose.slides/presentation) do PDF.

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


Převádí [Presentation](../../com.aspose.slides/presentation) do SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta ke vstupní prezentaci |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presPath | java.lang.String | Cesta ke vstupní prezentaci |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, který vrací SVG výstupní cestu pro každou snímek v prezentaci |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do SVG.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, který vrací SVG výstupní cestu pro každou snímek v prezentaci |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Převádí [Presentation](../../com.aspose.slides/presentation) do SVG.

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


Převádí [Presentation](../../com.aspose.slides/presentation) do SVG.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback, který vrací SVG výstupní cestu pro každou snímek v prezentaci |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Možnosti exportu SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outputFileName | java.lang.String | Výstupní jméno souboru. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost každého generovaného obrázku. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.jpeg", kde N je číslo snímku.

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |
| scale | float | Faktor měřítka aplikovaný na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Vstupní prezentace |
| outputFileName | java.lang.String | Výstupní jméno souboru. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost každého generovaného obrázku. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu PNG. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.png", kde N je číslo snímku.

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |
| scale | float | Faktor měřítka aplikovaný na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Převádí vstupní prezentaci na sadu obrázků ve formátu TIFF. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.tiff", výsledek bude uložen jako sada souborů "myPath/myFilename\_N.tiff", kde N je číslo snímku.

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Převádí vstupní prezentaci do formátu TIFF s vlastními možnostmi. Pokud je výstupní jméno souboru zadáno jako "myPath/myFilename.tiff" a multipage je false, výsledek bude uložen jako sada souborů "myPath/myFilename\_N.tiff", kde N je číslo snímku. Jinak, pokud je multipage true, výsledek bude více-stránkový dokument "myPath/myFilename.tiff".

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
| outputFileName | java.lang.String | Výstupní jméno souboru. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Možnosti ukládání TIFF. |
| multipage | boolean | Určuje, zda má být vytvářený dokument TIFF více-stránkový. |