---
title: Convert
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekumpulan metode yang dimaksudkan untuk mengonversi .
type: docs
url: /id/com.aspose.slides/convert/
---
**Pewarisan:**
java.lang.Object
```
public class Convert
```

Mewakili sekelompok metode yang dimaksudkan untuk mengonversi [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## Konstruktor

| Constructor | Description |
| --- | --- |
| [Convert()](#Convert--) |  |
## Metode

| Method | Description |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) menggunakan ekstensi jalur keluaran yang diberikan untuk menentukan format ekspor yang diperlukan. |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF. |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF. |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF. |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF. |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG. |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG. |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG. |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG. |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat JPEG. |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat JPEG. |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat JPEG. |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat PNG. |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat PNG. |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat PNG. |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | Mengonversi presentasi masukan ke sekumpulan gambar berformat TIFF. |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | Mengonversi presentasi masukan ke format TIFF dengan opsi khusus. |
### Convert() {#Convert--}
```
public Convert()
```


### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) menggunakan ekstensi jalur keluaran yang diberikan untuk menentukan format ekspor yang diperlukan.

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | java.lang.String | Jalur presentasi masukan |
| outPath | java.lang.String | Jalur keluaran |

### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF.

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | java.lang.String | Jalur presentasi masukan |
| outPath | java.lang.String | Jalur keluaran |

### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF.

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | java.lang.String | Jalur presentasi masukan |
| outPath | java.lang.String | Jalur keluaran |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opsi PDF keluaran |

### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| outPath | java.lang.String | Jalur keluaran |

### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke PDF.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| outPath | java.lang.String | Jalur keluaran |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | Opsi PDF keluaran |

### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | java.lang.String | Jalur presentasi masukan |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG.

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presPath | java.lang.String | Jalur presentasi masukan |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback yang mengembalikan jalur keluaran SVG untuk setiap slide dalam presentasi |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG.

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback yang mengembalikan jalur keluaran SVG untuk setiap slide dalam presentasi |

### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opsi ekspor SVG |

### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```


Mengonversi [Presentation](../../com.aspose.slides/presentation) ke SVG.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | Callback yang mengembalikan jalur keluaran SVG untuk setiap slide dalam presentasi |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opsi ekspor SVG |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| outputFileName | java.lang.String | Nama file keluaran. |
| imageSize | java.awt.Dimension | Ukuran setiap gambar yang dihasilkan. |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat JPEG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.jpeg", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.jpeg", di mana N adalah nomor slide.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |
| scale | float | Faktor skala yang diterapkan pada gambar keluaran relatif terhadap ukuran slide asli. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan |
| outputFileName | java.lang.String | Nama file keluaran. |
| imageSize | java.awt.Dimension | Ukuran setiap gambar yang dihasilkan. |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat PNG. Jika nama file keluaran diberikan sebagai "myPath/myFilename.png", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.png", di mana N adalah nomor slide.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |
| scale | float | Faktor skala yang diterapkan pada gambar keluaran relatif terhadap ukuran slide asli. |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```


Mengonversi presentasi masukan menjadi sekumpulan gambar berformat TIFF. Jika nama file keluaran diberikan sebagai "myPath/myFilename.tiff", hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```


Mengonversi presentasi masukan ke format TIFF dengan opsi khusus. Jika nama file keluaran diberikan sebagai "myPath/myFilename.tiff" dan multipage bernilai false, hasilnya akan disimpan sebagai sekumpulan berkas "myPath/myFilename_N.tiff", di mana N adalah nomor slide. Jika multipage bernilai true, hasilnya akan menjadi dokumen multi-halaman "myPath/myFilename.tiff".

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi masukan. |
| outputFileName | java.lang.String | Nama file keluaran. |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opsi penyimpanan TIFF. |
| multipage | boolean | Menentukan apakah dokumen TIFF yang dihasilkan harus multi-halaman. |