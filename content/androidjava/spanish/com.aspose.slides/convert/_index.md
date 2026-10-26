---
title: Convert
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa un grupo de métodos destinados a convertir.
type: docs
url: /es/com.aspose.slides/convert/
---
**Herencia:**
java.lang.Object
```
public class Convert
```

Representa un conjunto de métodos destinados a convertir [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [Convert()](#Convert--) |  |
## Métodos

| Method | Descripción |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Convierte [Presentation](../../com.aspose.slides/presentation) usando la extensión de ruta de salida pasada para determinar el formato de exportación requerido. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Convierte [Presentation](../../com.aspose.slides/presentation) a PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Convierte [Presentation](../../com.aspose.slides/presentation) a PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Convierte [Presentation](../../com.aspose.slides/presentation) a PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Convierte [Presentation](../../com.aspose.slides/presentation) a PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Convierte [Presentation](../../com.aspose.slides/presentation) a SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Convierte [Presentation](../../com.aspose.slides/presentation) a SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Convierte [Presentation](../../com.aspose.slides/presentation) a SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Convierte [Presentation](../../com.aspose.slides/presentation) a SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Convierte [Presentation](../../com.aspose.slides/presentation) a SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Convierte la presentación de entrada a un conjunto de imágenes en formato TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Convierte la presentación de entrada al formato TIFF con opciones personalizadas. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) usando la extensión de ruta de salida pasada para determinar el formato de exportación requerido.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | java.lang.String | Ruta de la presentación de entrada |
| outPath | java.lang.String | Ruta de salida |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | java.lang.String | Ruta de la presentación de entrada |
| outPath | java.lang.String | Ruta de salida |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | java.lang.String | Ruta de la presentación de entrada |
| outPath | java.lang.String | Ruta de salida |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opciones de PDF de salida |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentación de entrada |
| outPath | java.lang.String | Ruta de salida |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a PDF.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentación de entrada |
| outPath | java.lang.String | Ruta de salida |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opciones de PDF de salida |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | java.lang.String | Ruta de la presentación de entrada |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| presPath | java.lang.String | Ruta de la presentación de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que devuelve la ruta de salida SVG para cada diapositiva en la presentación |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a SVG.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentación de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que devuelve la ruta de salida SVG para cada diapositiva en la presentación |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a SVG.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentación de entrada |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de exportación SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Convierte [Presentation](../../com.aspose.slides/presentation) a SVG.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentación de entrada |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback que devuelve la ruta de salida SVG para cada diapositiva en la presentación |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de exportación SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.jpeg", donde N es el número de la diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.jpeg", donde N es el número de la diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada |
| outputFileName | java.lang.String | El nombre del archivo de salida. |
| imageSize | [Size](../../com.aspose.slides.android/size) | El tamaño de cada imagen generada. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato JPEG. Si el nombre del archivo de salida se indica como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.jpeg", donde N es el número de la diapositiva.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |
| scale | float | El factor de escala aplicado a las imágenes de salida respecto al tamaño original de la diapositiva. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Las opciones de renderizado. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. Si el nombre del archivo de salida se indica como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.png", donde N es el número de la diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. Si el nombre del archivo de salida se indica como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.png", donde N es el número de la diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada |
| outputFileName | java.lang.String | El nombre del archivo de salida. |
| imageSize | [Size](../../com.aspose.slides.android/size) | El tamaño de cada imagen generada. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato PNG. Si el nombre del archivo de salida se indica como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.png", donde N es el número de la diapositiva.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |
| scale | float | El factor de escala aplicado a las imágenes de salida respecto al tamaño original de la diapositiva. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Las opciones de renderizado. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Convierte la presentación de entrada a un conjunto de imágenes en formato TIFF. Si el nombre del archivo de salida se indica como "myPath/myFilename.tiff", el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.tiff", donde N es el número de la diapositiva.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Convierte la presentación de entrada al formato TIFF con opciones personalizadas. Si el nombre del archivo de salida se indica como "myPath/myFilename.tiff" y multipage es false, el resultado se guardará como un conjunto de archivos "myPath/myFilename\_N.tiff", donde N es el número de la diapositiva. De lo contrario, si multipage es true, el resultado será un documento multipágina "myPath/myFilename.tiff".

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | La presentación de entrada. |
| outputFileName | java.lang.String | El nombre del archivo de salida. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Las opciones de guardado TIFF. |
| multipage | boolean | Especifica si el documento TIFF generado debe ser multipágina. |