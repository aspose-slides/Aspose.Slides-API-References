---
title: Convert
second_title: Aspose.Slides for Java API 参考
description: 表示一组旨在转换 的方法。
type: docs
url: /zh/com.aspose.slides/convert/
---
**继承：**
java.lang.Object
```
public class Convert
```

表示一组旨在转换 [Presentation](../../com.aspose.slides/presentation) 的方法。

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Convert()](#Convert--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | 使用传入的输出路径扩展名来确定所需的导出格式，将 [Presentation](../../com.aspose.slides/presentation) 转换为。 |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。 |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。 |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。 |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。 |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。 |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。 |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | 将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。 |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | 将输入演示文稿转换为一组 JPEG 格式的图像。 |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | 将输入演示文稿转换为一组 JPEG 格式的图像。 |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 将输入演示文稿转换为一组 JPEG 格式的图像。 |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | 将输入演示文稿转换为一组 PNG 格式的图像。 |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | 将输入演示文稿转换为一组 PNG 格式的图像。 |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 将输入演示文稿转换为一组 PNG 格式的图像。 |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | 将输入演示文稿转换为一组 TIFF 格式的图像。 |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | 使用自定义选项将输入演示文稿转换为 TIFF 格式。 |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

使用传入的输出路径扩展名来确定所需的导出格式，将 [Presentation](../../com.aspose.slides/presentation) 转换为。

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | java.lang.String | 输入演示文稿的路径 |
| outPath | java.lang.String | 输出路径 |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | java.lang.String | 输入演示文稿的路径 |
| outPath | java.lang.String | 输出路径 |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | java.lang.String | 输入演示文稿的路径 |
| outPath | java.lang.String | 输出路径 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 输出 PDF 选项 |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| outPath | java.lang.String | 输出路径 |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 PDF。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| outPath | java.lang.String | 输出路径 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 输出 PDF 选项 |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | java.lang.String | 输入演示文稿的路径 |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presPath | java.lang.String | 输入演示文稿的路径 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 为演示文稿中每张幻灯片返回 SVG 输出路径的回调 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 为演示文稿中每张幻灯片返回 SVG 输出路径的回调 |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 导出选项 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

将 [Presentation](../../com.aspose.slides/presentation) 转换为 SVG。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 为演示文稿中每张幻灯片返回 SVG 输出路径的回调 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 导出选项 |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 “myPath/myFilename.jpeg”，结果将保存为一组 “myPath/myFilename\_N.jpeg” 文件，其中 N 为幻灯片编号。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 “myPath/myFilename.jpeg”，结果将保存为一组 “myPath/myFilename\_N.jpeg” 文件，其中 N 为幻灯片编号。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| outputFileName | java.lang.String | 输出文件名。 |
| imageSize | java.awt.Dimension | 每个生成图像的大小。 |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

将输入演示文稿转换为一组 JPEG 格式的图像。如果输出文件名为 “myPath/myFilename.jpeg”，结果将保存为一组 “myPath/myFilename\_N.jpeg” 文件，其中 N 为幻灯片编号。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |
| scale | float | 相对于原始幻灯片大小的缩放因子。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 “myPath/myFilename.png”，结果将保存为一组 “myPath/myFilename\_N.png” 文件，其中 N 为幻灯片编号。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 “myPath/myFilename.png”，结果将保存为一组 “myPath/myFilename\_N.png” 文件，其中 N 为幻灯片编号。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿 |
| outputFileName | java.lang.String | 输出文件名。 |
| imageSize | java.awt.Dimension | 每个生成图像的大小。 |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

将输入演示文稿转换为一组 PNG 格式的图像。如果输出文件名为 “myPath/myFilename.png”，结果将保存为一组 “myPath/myFilename\_N.png” 文件，其中 N 为幻灯片编号。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |
| scale | float | 相对于原始幻灯片大小的缩放因子。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 渲染选项。 |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

将输入演示文稿转换为一组 TIFF 格式的图像。如果输出文件名为 “myPath/myFilename.tiff”，结果将保存为一组 “myPath/myFilename\_N.tiff” 文件，其中 N 为幻灯片编号。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

使用自定义选项将输入演示文稿转换为 TIFF 格式。如果输出文件名为 “myPath/myFilename.tiff” 且 multipage 为 false，结果将保存为一组 “myPath/myFilename\_N.tiff” 文件，其中 N 为幻灯片编号。否则，如果 multipage 为 true，结果将是一个多页的 “myPath/myFilename.tiff” 文档。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 输入演示文稿。 |
| outputFileName | java.lang.String | 输出文件名。 |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF 保存选项。 |
| multipage | boolean | 指定生成的 TIFF 文档是否为多页。 |