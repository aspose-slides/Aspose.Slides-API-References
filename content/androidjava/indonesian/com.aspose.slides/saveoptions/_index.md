---
title: SaveOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Kelas abstrak dengan opsi yang mengontrol cara presentasi disimpan.
type: docs
url: /id/com.aspose.slides/saveoptions/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Kelas abstrak dengan opsi yang mengontrol cara presentasi disimpan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [getProgressCallback()](#getProgressCallback--) | Mewakili objek callback untuk pembaruan progres penyimpanan dalam persentase. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Mewakili objek callback untuk pembaruan progres penyimpanan dalam persentase. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. |
| [getGradientStyle()](#getGradientStyle--) | Mengembalikan atau mengatur gaya visual gradien. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Mengembalikan atau mengatur gaya visual gradien. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Mengembalikan:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Mengembalikan atau mengatur sebuah objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

Mewakili objek callback untuk pembaruan progres penyimpanan dalam persentase. Lihat [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Mengembalikan:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

Mewakili objek callback untuk pembaruan progres penyimpanan dalam persentase. Lihat [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Mengembalikan atau mengatur font yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

Mengembalikan atau mengatur gaya visual gradien. Baca/tulis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Mengembalikan:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

Mengembalikan atau mengatur gaya visual gradien. Baca/tulis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca/tulis boolean. Nilai default adalah false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ketika properti ini diatur ke true, hyperlink dengan panggilan JavaScript akan diabaikan saat menyimpan.

Ketika properti ini diatur ke false, semua hyperlink akan disimpan.

**Mengembalikan:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

Menentukan apakah akan melewatkan hyperlink dengan pemanggilan JavaScript saat menyimpan presentasi. Baca/tulis boolean. Nilai default adalah false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Ketika properti ini diatur ke true, hyperlink dengan panggilan JavaScript akan diabaikan saat menyimpan.

Ketika properti ini diatur ke false, semua hyperlink akan disimpan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |