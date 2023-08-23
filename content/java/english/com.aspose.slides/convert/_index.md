---
title: Convert
second_title: Aspose.Slides for Java API Reference
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
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
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

