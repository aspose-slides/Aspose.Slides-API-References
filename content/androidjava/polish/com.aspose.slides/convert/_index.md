---
title: Convert
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje grupę metod przeznaczonych do konwertowania.
type: docs
url: /pl/com.aspose.slides/convert/
---
**Dziedziczenie:**
java.lang.Object
```
public class Convert
```

Reprezentuje grupę metod przeznaczonych do konwertowania [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) przy użyciu podanego rozszerzenia ścieżki wyjściowej w celu określenia wymaganego formatu eksportu. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Konwertuje prezentację wejściową na zestaw obrazów w formacie TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Konwertuje prezentację wejściową do formatu TIFF z niestandardowymi opcjami. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) przy użyciu podanego rozszerzenia ścieżki wyjściowej w celu określenia wymaganego formatu eksportu.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | java.lang.String | Ścieżka prezentacji wejściowej |
| outPath | java.lang.String | Ścieżka wyjściowa |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | java.lang.String | Ścieżka prezentacji wejściowej |
| outPath | java.lang.String | Ścieżka wyjściowa |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | java.lang.String | Ścieżka prezentacji wejściowej |
| outPath | java.lang.String | Ścieżka wyjściowa |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opcje wyjściowego PDF |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| outPath | java.lang.String | Ścieżka wyjściowa |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu PDF.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| outPath | java.lang.String | Ścieżka wyjściowa |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opcje wyjściowego PDF |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | java.lang.String | Ścieżka prezentacji wejściowej |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| presPath | java.lang.String | Ścieżka prezentacji wejściowej |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Funkcja zwrotna zwracająca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Funkcja zwrotna zwracająca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje eksportu SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

Konwertuje [Presentation](../../com.aspose.slides/presentation) do formatu SVG.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Funkcja zwrotna zwracająca ścieżkę wyjściową SVG dla każdego slajdu w prezentacji |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opcje eksportu SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar każdego generowanego obrazu. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie JPEG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |
| scale | float | Współczynnik skalowania stosowany do obrazów wyjściowych względem oryginalnego rozmiaru slajdu. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Rozmiar każdego generowanego obrazu. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie PNG. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |
| scale | float | Współczynnik skalowania stosowany do obrazów wyjściowych względem oryginalnego rozmiaru slajdu. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opcje renderowania. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

Konwertuje prezentację wejściową na zestaw obrazów w formacie TIFF. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.tiff", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

Konwertuje prezentację wejściową do formatu TIFF z niestandardowymi opcjami. Jeśli podano nazwę pliku wyjściowego jako "myPath/myFilename.tiff" i parametr multipage ma wartość false, wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. W przeciwnym razie, jeśli multipage ma wartość true, wynik będzie wielostronicowym dokumentem "myPath/myFilename.tiff".

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Prezentacja wejściowa. |
| outputFileName | java.lang.String | Nazwa pliku wyjściowego. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opcje zapisu TIFF. |
| multipage | boolean | Określa, czy generowany dokument TIFF ma być wielostronicowy. |
