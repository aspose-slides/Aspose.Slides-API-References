---
title: Convert
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 変換を目的としたメソッドのグループを表します。
type: docs
url: /ja/com.aspose.slides/convert/
---
**継承:**
java.lang.Object
```
public class Convert
```

[Presentation](../../com.aspose.slides/presentation) を変換することを目的としたメソッドのグループを表します。

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Convert()](#Convert--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) を、渡された出力パス拡張子を使用して必要なエクスポート形式を決定しながら変換します。 |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) を PDF に変換します。 |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) を PDF に変換します。 |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) を PDF に変換します。 |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) を PDF に変換します。 |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) を SVG に変換します。 |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) を SVG に変換します。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) を SVG に変換します。 |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) を SVG に変換します。 |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) を SVG に変換します。 |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。 |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。 |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 入力プレゼンテーションを JPEG 形式の画像セットに変換します。 |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。 |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。 |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | 入力プレゼンテーションを PNG 形式の画像セットに変換します。 |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | 入力プレゼンテーションを TIFF 形式の画像セットに変換します。 |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | 入力プレゼンテーションをカスタムオプションで TIFF 形式に変換します。 |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) を、渡された出力パス拡張子を使用して必要なエクスポート形式を決定しながら変換します。

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | java.lang.String | 入力プレゼンテーションのパス |
| outPath | java.lang.String | 出力パス |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) を PDF に変換します。

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | java.lang.String | 入力プレゼンテーションのパス |
| outPath | java.lang.String | 出力パス |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) を PDF に変換します。

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | java.lang.String | 入力プレゼンテーションのパス |
| outPath | java.lang.String | 出力パス |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 出力 PDF オプション |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) を PDF に変換します。

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| outPath | java.lang.String | 出力パス |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) を PDF に変換します。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| outPath | java.lang.String | 出力パス |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | 出力 PDF オプション |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

[Presentation](../../com.aspose.slides/presentation) を SVG に変換します。

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | java.lang.String | 入力プレゼンテーションのパス |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) を SVG に変換します。

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presPath | java.lang.String | 入力プレゼンテーションのパス |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | プレゼンテーション内の各スライドの SVG 出力パスを返すコールバック |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) を SVG に変換します。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | プレゼンテーション内の各スライドの SVG 出力パスを返すコールバック |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) を SVG に変換します。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG エクスポートオプション |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) を SVG に変換します。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | プレゼンテーション内の各スライドの SVG 出力パスを返すコールバック |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG エクスポートオプション |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

入力プレゼンテーションを JPEG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます（N はスライド番号）。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |

### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

入力プレゼンテーションを JPEG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます（N はスライド番号）。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| outputFileName | java.lang.String | 出力ファイル名。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 生成される各画像のサイズ。 |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

入力プレゼンテーションを JPEG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.jpeg" の場合、結果は "myPath/myFilename_N.jpeg" という名前のファイルセットとして保存されます（N はスライド番号）。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |
| scale | float | 元のスライドサイズに対する出力画像の拡大縮小率。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

入力プレゼンテーションを PNG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存されます（N はスライド番号）。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |

### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

入力プレゼンテーションを PNG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存されます（N はスライド番号）。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション |
| outputFileName | java.lang.String | 出力ファイル名。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 生成される各画像のサイズ。 |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

入力プレゼンテーションを PNG 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.png" の場合、結果は "myPath/myFilename_N.png" という名前のファイルセットとして保存されます（N はスライド番号）。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |
| scale | float | 元のスライドサイズに対する出力画像の拡大縮小率。 |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

入力プレゼンテーションを TIFF 形式の画像セットに変換します。出力ファイル名が "myPath/myFilename.tiff" の場合、結果は "myPath/myFilename_N.tiff" という名前のファイルセットとして保存されます（N はスライド番号）。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

入力プレゼンテーションをカスタムオプションで TIFF 形式に変換します。出力ファイル名が "myPath/myFilename.tiff" で multipage が false の場合、結果は "myPath/myFilename_N.tiff" という名前のファイルセットとして保存されます（N はスライド番号）。multipage が true の場合、結果はマルチページの "myPath/myFilename.tiff" ドキュメントとなります。

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
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | 入力プレゼンテーション。 |
| outputFileName | java.lang.String | 出力ファイル名。 |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF 保存オプション。 |
| multipage | boolean | 生成される TIFF ドキュメントをマルチページにするかどうかを指定します。 |