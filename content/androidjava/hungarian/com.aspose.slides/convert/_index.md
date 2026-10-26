---
title: Convert
second_title: Aspose.Slides for Android Java API referencia
description: Csoportot képvisel a konvertálásra szánt módszerekből.
type: docs
url: /hu/com.aspose.slides/convert/
---
**Öröklés:**  
java.lang.Object  
```
public class Convert
```

A [Presentation](../../com.aspose.slides/presentation) átalakítására szolgáló módszerek csoportját képviseli.

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Convert()](#Convert--) |  |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation)-t a megadott kimeneti útvonal kiterjesztése alapján, hogy meghatározza a szükséges exportformátumot. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Átalakítja a bemeneti bemutatót TIFF formátumú képek sorozatává. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Átalakítja a bemeneti bemutatót egyedi beállításokkal TIFF formátumba. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation)-t a megadott kimeneti útvonal kiterjesztése alapján, hogy meghatározza a szükséges exportformátumot.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti bemutató útvonala |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti bemutató útvonala |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti bemutató útvonala |
| outPath | java.lang.String | Kimeneti útvonal |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Kimeneti PDF beállítások |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti bemutató |
| outPath | java.lang.String | Kimeneti útvonal |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) PDF formátumba.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti bemutató |
| outPath | java.lang.String | Kimeneti útvonal |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Kimeneti PDF beállítások |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti bemutató útvonala |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presPath | java.lang.String | A bemeneti bemutató útvonala |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely a bemutató minden diájához SVG kimeneti útvonalat ad vissza |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti bemutató |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely a bemutató minden diájához SVG kimeneti útvonalat ad vissza |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti bemutató |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG exportálási beállítások |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Átalakítja a(z) [Presentation](../../com.aspose.slides/presentation) SVG formátumba.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Bemeneti bemutató |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Visszahívás, amely a bemutató minden diájához SVG kimeneti útvonalat ad vissza |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG exportálási beállítások |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlokként lesz mentve, ahol N a dia száma.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```


Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlokként lesz mentve, ahol N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Az egyes előállított képek mérete. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formában van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlokként lesz mentve, ahol N a dia száma.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| scale | float | Az eredeti dia méretéhez viszonyítva a kimeneti képekre alkalmazott méretezési tényező. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | A renderelési beállítások. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formában van megadva, az eredmény "myPath/myFilename_N.png" fájlokként lesz mentve, ahol N a dia száma.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```


Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formában van megadva, az eredmény "myPath/myFilename_N.png" fájlokként lesz mentve, ahol N a dia száma.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Az egyes előállított képek mérete. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Átalakítja a bemeneti bemutatót PNG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.png" formában van megadva, az eredmény "myPath/myFilename_N.png" fájlokként lesz mentve, ahol N a dia száma.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| scale | float | Az eredeti dia méretéhez viszonyítva a kimeneti képekre alkalmazott méretezési tényező. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | A renderelési beállítások. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Átalakítja a bemeneti bemutatót TIFF formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.tiff" formában van megadva, az eredmény "myPath/myFilename_N.tiff" fájlokként lesz mentve, ahol N a dia száma.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Átalakítja a bemeneti bemutatót egyedi beállításokkal TIFF formátumba. Ha a kimeneti fájlnév "myPath/myFilename.tiff" és a multipage értéke false, az eredmény "myPath/myFilename_N.tiff" fájlokként lesz mentve, ahol N a dia száma. Amennyiben a multipage értéke true, az eredmény egy több oldalas "myPath/myFilename.tiff" dokumentum lesz.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | A bemeneti bemutató. |
| outputFileName | java.lang.String | A kimeneti fájlnév. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | A TIFF mentési beállítások. |
| multipage | boolean | Megadja, hogy a generált TIFF dokumentum több oldalas legyen-e. |