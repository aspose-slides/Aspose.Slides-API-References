---
title: Convert
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表一組旨在轉換 的方法。
type: docs
url: /zh-hant/com.aspose.slides/convert/
---
**繼承:**  
java.lang.Object  
```
public class Convert
```

表示一組旨在轉換 [Presentation](../../com.aspose.slides/presentation) 的方法。

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## 建構函式

| 建構式 | 說明 |
| --- | --- |
| [Convert()](#Convert--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | 使用傳入的輸出路徑副檔名來確定所需的匯出格式，轉換 [Presentation](../../com.aspose.slides/presentation)。 |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。 |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。 |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。 |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。 |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。 |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。 |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | 將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。 |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | 將輸入簡報轉換為一組 JPEG 格式影像。 |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 將輸入簡報轉換為一組 JPEG 格式影像。 |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 將輸入簡報轉換為一組 JPEG 格式影像。 |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | 將輸入簡報轉換為一組 PNG 格式影像。 |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 將輸入簡報轉換為一組 PNG 格式影像。 |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 將輸入簡報轉換為一組 PNG 格式影像。 |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | 將輸入簡報轉換為一組 TIFF 格式影像。 |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | 使用自訂選項將輸入簡報轉換為 TIFF 格式。 |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

使用傳入的輸出路徑副檔名來確定所需的匯出格式，轉換 [Presentation](../../com.aspose.slides/presentation)。

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presPath | java.lang.String | 輸入簡報的路徑 |
| outPath | java.lang.String | 輸出路徑 |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presPath | java.lang.String | 輸入簡報的路徑 |
| outPath | java.lang.String | 輸出路徑 |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presPath | java.lang.String | 輸入簡報的路徑 |
| outPath | java.lang.String | 輸出路徑 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 輸出 PDF 的選項 |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| outPath | java.lang.String | 輸出路徑 |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 PDF。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| outPath | java.lang.String | 輸出路徑 |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 輸出 PDF 的選項 |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presPath | java.lang.String | 輸入簡報的路徑 |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presPath | java.lang.String | 輸入簡報的路徑 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 回呼，用於為簡報中的每一張投影片返回 SVG 輸出路徑 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 回呼，用於為簡報中的每一張投影片返回 SVG 輸出路徑 |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 匯出選項 |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

將 [Presentation](../../com.aspose.slides/presentation) 轉換為 SVG。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | 回呼，用於為簡報中的每一張投影片返回 SVG 輸出路徑 |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 匯出選項 |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

將輸入簡報轉換為一組 JPEG 格式影像。如果輸出檔名為「myPath/myFilename.jpeg」，結果將保存為「myPath/myFilename\_N.jpeg」系列檔案，其中 N 為投影片編號。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

將輸入簡報轉換為一組 JPEG 格式影像。如果輸出檔名為「myPath/myFilename.jpeg」，結果將保存為「myPath/myFilename\_N.jpeg」系列檔案，其中 N 為投影片編號。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| outputFileName | java.lang.String | 輸出檔名。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 每個產生影像的大小。 |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

將輸入簡報轉換為一組 JPEG 格式影像。如果輸出檔名為「myPath/myFilename.jpeg」，結果將保存為「myPath/myFilename\_N.jpeg」系列檔案，其中 N 為投影片編號。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |
| scale | float | 與原始投影片大小相比的縮放比例。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

將輸入簡報轉換為一組 PNG 格式影像。如果輸出檔名為「myPath/myFilename.png」，結果將保存為「myPath/myFilename\_N.png」系列檔案，其中 N 為投影片編號。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

將輸入簡報轉換為一組 PNG 格式影像。如果輸出檔名為「myPath/myFilename.png」，結果將保存為「myPath/myFilename\_N.png」系列檔案，其中 N 為投影片編號。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報 |
| outputFileName | java.lang.String | 輸出檔名。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 每個產生影像的大小。 |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

將輸入簡報轉換為一組 PNG 格式影像。如果輸出檔名為「myPath/myFilename.png」，結果將保存為「myPath/myFilename\_N.png」系列檔案，其中 N 為投影片編號。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |
| scale | float | 與原始投影片大小相比的縮放比例。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | 轉譯選項。 |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

將輸入簡報轉換為一組 TIFF 格式影像。如果輸出檔名為「myPath/myFilename.tiff」，結果將保存為「myPath/myFilename\_N.tiff」系列檔案，其中 N 為投影片編號。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

使用自訂選項將輸入簡報轉換為 TIFF 格式。如果輸出檔名為「myPath/myFilename.tiff」且 multipage 為 false，結果將保存為「myPath/myFilename\_N.tiff」系列檔案，其中 N 為投影片編號。若 multipage 為 true，則結果為單一多頁的「myPath/myFilename.tiff」文件。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 輸入簡報。 |
| outputFileName | java.lang.String | 輸出檔名。 |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF 儲存選項。 |
| multipage | boolean | 指定產生的 TIFF 文件是否為多頁。 |