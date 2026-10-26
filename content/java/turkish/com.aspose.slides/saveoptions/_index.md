---
title: SaveOptions
second_title: Aspose.Slides için Java API Referansı
description: Sunumun nasıl kaydedileceğini kontrol eden seçeneklere sahip soyut sınıf.
type: docs
url: /tr/com.aspose.slides/saveoptions/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Sunumun nasıl kaydedileceğini kontrol eden seçeneklere sahip soyut sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğini veya iptal edilip edilmeyeceğini belirleyen bir nesneyi alır veya ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğini veya iptal edilip edilmeyeceğini belirleyen bir nesneyi alır veya ayarlar. |
| [getProgressCallback()](#getProgressCallback--) | Kaydetme ilerleme güncellemelerini yüzde olarak temsil eden bir geri çağırma nesnesi. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Kaydetme ilerleme güncellemelerini yüzde olarak temsil eden bir geri çağırma nesnesi. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini alır veya ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini alır veya ayarlar. |
| [getGradientStyle()](#getGradientStyle--) | Gradyanın görsel stilini alır veya ayarlar. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Gradyanın görsel stilini alır veya ayarlar. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğini veya iptal edilip edilmeyeceğini belirleyen bir nesneyi alır veya ayarlar. Okuma/Yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Dönüş:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğini veya iptal edilip edilmeyeceğini belirleyen bir nesneyi alır veya ayarlar. Okuma/Yazma [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```

Kaydetme ilerleme güncellemelerini yüzde olarak temsil eden bir geri çağırma nesnesi. Bkz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Dönüş:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```

Kaydetme ilerleme güncellemelerini yüzde olarak temsil eden bir geri çağırma nesnesi. Bkz [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Kaynak yazı tipi bulunamadığında kullanılan yazı tipini alır veya ayarlar. Okuma-Yazma String.

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


**Dönüş:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Kaynak yazı tipi bulunamadığında kullanılan yazı tipini alır veya ayarlar. Okuma-Yazma String.

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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```

Gradyanın görsel stilini alır veya ayarlar. Okuma/Yazma [GradientStyle](../../com.aspose.slides/gradientstyle).

**Dönüş:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```

Gradyanın görsel stilini alır veya ayarlar. Okuma/Yazma [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```

Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Okuma/Yazma boolean. Varsayılan değer false.

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

Bu özellik true olarak ayarlandığında, JavaScript çağrıları içeren köprüler kaydedilirken yok sayılır.

Bu özellik false olarak ayarlandığında, tüm köprüler kaydedilir.

**Dönüş:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```

Sunumu kaydederken JavaScript çağrıları içeren köprülerin atlanıp atlanmayacağını belirtir. Okuma/Yazma boolean. Varsayılan değer false.

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

Bu özellik true olarak ayarlandığında, JavaScript çağrıları içeren köprüler kaydedilirken yok sayılır.

Bu özellik false olarak ayarlandığında, tüm köprüler kaydedilir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |