---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Options that control how a presentation is saved.
type: docs
url: /tr/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Bir sunumun nasıl kaydedileceğini kontrol eden seçenekler.
## Metotlar

| Method | Description |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. |
| [getProgressCallback()](#getProgressCallback--) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. |
| [getGradientStyle()](#getGradientStyle--) | Gradyanın görsel stilini döndürür veya ayarlar. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Gradyanın görsel stilini döndürür veya ayarlar. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Sunumu kaydederken JavaScript çağrısı içeren hiper bağlantıların atlanıp atlanmayacağını belirtir. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Sunumu kaydederken JavaScript çağrısı içeren hiper bağlantıların atlanıp atlanmayacağını belirtir. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunur/Yazılabilir [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Döndürür:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okunur/Yazılabilir [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```


Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder. Bakınız [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Döndürür:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```


Yüzde olarak kaydetme ilerleme güncellemeleri için bir geri arama nesnesini temsil eder. Bakınız [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunur/Yazılabilir String.

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


**Döndürür:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür veya ayarlar. Okunur/Yazılabilir String.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```


Gradyanın görsel stilini döndürür veya ayarlar. Okunur/Yazılabilir [GradientStyle](../../com.aspose.slides/gradientstyle).

**Döndürür:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```


Gradyanın görsel stilini döndürür veya ayarlar. Okunur/Yazılabilir [GradientStyle](../../com.aspose.slides/gradientstyle).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```


Sunumu kaydederken JavaScript çağrısı içeren hiper bağlantıların atlanıp atlanmayacağını belirtir. Okunur/Yazılabilir boolean. Varsayılan değer false.

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

Bu özellik true olarak ayarlandığında, JavaScript çağrısı içeren hiper bağlantılar kaydederken yok sayılır.

Bu özellik false olarak ayarlandığında, tüm hiper bağlantılar kaydedilir.

**Döndürür:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```


Sunumu kaydederken JavaScript çağrısı içeren hiper bağlantıların atlanıp atlanmayacağını belirtir. Okunur/Yazılabilir boolean. Varsayılan değer false.

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

Bu özellik true olarak ayarlandığında, JavaScript çağrısı içeren hiper bağlantılar kaydederken yok sayılır.

Bu özellik false olarak ayarlandığında, tüm hiper bağlantılar kaydedilir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |