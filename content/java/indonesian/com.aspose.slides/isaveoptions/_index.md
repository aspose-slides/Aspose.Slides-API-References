---
title: ISaveOptions
second_title: Aspose.Slides for Java API Reference
description: Opsi yang mengontrol cara presentasi disimpan.
type: docs
url: /id/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Opsi yang mengontrol cara presentasi disimpan.
## Methods

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Mengembalikan atau menetapkan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Mengembalikan atau menetapkan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [getProgressCallback()](#getProgressCallback--) | Mewakili objek panggilan balik untuk pembaruan kemajuan penyimpanan dalam persentase. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Mewakili objek panggilan balik untuk pembaruan kemajuan penyimpanan dalam persentase. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Mengembalikan atau menetapkan font yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Mengembalikan atau menetapkan font yang digunakan bila font sumber tidak ditemukan. |
| [getGradientStyle()](#getGradientStyle--) | Mengembalikan atau menetapkan gaya visual gradasi. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Mengembalikan atau menetapkan gaya visual gradasi. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Mengembalikan atau menetapkan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Mengembalikan:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Mengembalikan atau menetapkan objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


Mewakili objek panggilan balik untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Mengembalikan:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


Mewakili objek panggilan balik untuk pembaruan kemajuan penyimpanan dalam persentase. Lihat [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Mengembalikan atau menetapkan font yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

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
public abstract void setDefaultRegularFont(String value)
```


Mengembalikan atau menetapkan font yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


Mengembalikan atau menetapkan gaya visual gradasi. Baca/tulis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Mengembalikan:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


Mengembalikan atau menetapkan gaya visual gradasi. Baca/tulis [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca/tulis boolean. Nilai default adalah false.

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

--------------------

Ketika properti ini diatur ke true, hyperlink dengan panggilan JavaScript akan diabaikan saat menyimpan.

Ketika properti ini diatur ke false, semua hyperlink akan disimpan.

**Mengembalikan:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


Menentukan apakah akan melewatkan hyperlink dengan panggilan JavaScript saat menyimpan presentasi. Baca/tulis boolean. Nilai default adalah false.

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

--------------------

Ketika properti ini diatur ke true, hyperlink dengan panggilan JavaScript akan diabaikan saat menyimpan.

Ketika properti ini diatur ke false, semua hyperlink akan disimpan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |