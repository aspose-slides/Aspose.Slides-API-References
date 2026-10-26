---
title: Convert
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a group of methods intended to convert .
type: docs
url: /com.aspose.slides/convert/
---
**Inheritance:**
java.lang.Object
```
public class Convert
```

Represents a group of methods intended to convert [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Convert()](#Convert--) |  |
## Methods

| Method | Description |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Converts [Presentation](../../com.aspose.slides/presentation) using the passed output path extension to determine the required export format. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Converts [Presentation](../../com.aspose.slides/presentation) to PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Converts [Presentation](../../com.aspose.slides/presentation) to PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Converts [Presentation](../../com.aspose.slides/presentation) to PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Converts [Presentation](../../com.aspose.slides/presentation) to PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Converts [Presentation](../../com.aspose.slides/presentation) to SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Converts [Presentation](../../com.aspose.slides/presentation) to SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Converts [Presentation](../../com.aspose.slides/presentation) to SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Converts [Presentation](../../com.aspose.slides/presentation) to SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Converts [Presentation](../../com.aspose.slides/presentation) to SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Converts the input presentation to a set of JPEG format images. |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converts the input presentation to a set of JPEG format images. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converts the input presentation to a set of JPEG format images. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Converts the input presentation to a set of PNG format images. |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | Converts the input presentation to a set of PNG format images. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Converts the input presentation to a set of PNG format images. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Converts the input presentation to a set of TIFF format images. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Converts the input presentation to TIFF format with custom options. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) using the passed output path extension to determine the required export format.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) to PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Converts [Presentation](../../com.aspose.slides/presentation) to PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| outPath | java.lang.String | Output path |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Output PDF options |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) to PDF.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| outPath | java.lang.String | Output path |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Converts [Presentation](../../com.aspose.slides/presentation) to PDF.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| outPath | java.lang.String | Output path |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Output PDF options |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) to SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) to SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presPath | java.lang.String | Path of the input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Converts [Presentation](../../com.aspose.slides/presentation) to SVG.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Converts [Presentation](../../com.aspose.slides/presentation) to SVG.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG export options |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Converts [Presentation](../../com.aspose.slides/presentation) to SVG.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Input presentation |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG export options |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename\_N.jpeg" files, where N is a slide number.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```


Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename\_N.jpeg" files, where N is a slide number.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation |
| outputFileName | java.lang.String | The output file name. |
| imageSize | [Size](../../com.aspose.slides.android/size) | The size of each generated image. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Converts the input presentation to a set of JPEG format images. If the output file name is given as "myPath/myFilename.jpeg", the result will be saved as a set of "myPath/myFilename\_N.jpeg" files, where N is a slide number.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | The rendering options. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename\_N.png" files, where N is a slide number.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```


Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename\_N.png" files, where N is a slide number.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation |
| outputFileName | java.lang.String | The output file name. |
| imageSize | [Size](../../com.aspose.slides.android/size) | The size of each generated image. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Converts the input presentation to a set of PNG format images. If the output file name is given as "myPath/myFilename.png", the result will be saved as a set of "myPath/myFilename\_N.png" files, where N is a slide number.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| scale | float | The scaling factor applied to the output images relative to the original slide size. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | The rendering options. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Converts the input presentation to a set of TIFF format images. If the output file name is given as "myPath/myFilename.tiff", the result will be saved as a set of "myPath/myFilename\_N.tiff" files, where N is a slide number.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Converts the input presentation to TIFF format with custom options. If the output file name is given as "myPath/myFilename.tiff" and multipage is false, the result will be saved as a set of "myPath/myFilename\_N.tiff" files, where N is a slide number. Otherwise, if multipage is true, the result will be a multi-page "myPath/myFilename.tiff" document.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The input presentation. |
| outputFileName | java.lang.String | The output file name. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | The TIFF saving options. |
| multipage | boolean | Specifies whether the generated TIFF document should be a multi-page. |

