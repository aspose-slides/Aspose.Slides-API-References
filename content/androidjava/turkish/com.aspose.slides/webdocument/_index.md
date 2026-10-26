---
title: WebDocument
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Sunumu web formatında kaydetmek için bir geçiş formunu temsil eder.
type: docs
url: /tr/com.aspose.slides/webdocument/
---
**Miras:**
java.lang.Object
```
public class WebDocument
```

Belgeyi web formatına kaydetmek için bir geçiş formunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [save()](#save--) | Belge çıktısını kaydeder. |
| [getInput()](#getInput--) | Belgenin giriş öğelerinin (şablonların) koleksiyonunu döndürür. |
| [getOutput()](#getOutput--) | Belgenin çıktı öğelerinin koleksiyonunu döndürür. |
| [getGlobal()](#getGlobal--) | Belgenin global depolamasını döndürür. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) yapıcı.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Belge için ayarlanan seçenekler. |

### save() {#save--}
```
public final void save()
```


Belge çıktısını kaydeder.

### getInput() {#getInput--}
```
public final Input getInput()
```


Belgenin giriş öğelerinin (şablonların) koleksiyonunu döndürür. Yalnızca okuma [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Döndürür:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Belgenin çıktı öğelerinin koleksiyonunu döndürür. Yalnızca okuma [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // şablonlardan kullanılmak üzere "slideMargin" özelliğini ekle
> 
>   // ... belgenin diğer seçeneklerini ayarla ve ardından belgeyi kaydet
>   document.save();
> ```

**Döndürür:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Belgenin global depolamasını döndürür. Yalnızca okuma [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // şablonlardan kullanılmak üzere "slideMargin" özelliğini ekle
> 
>   // ... belgenin diğer seçeneklerini ayarla ve ardından belgeyi kaydet
>   document.save();
> ```

**Döndürür:**
[Storage](../../com.aspose.slides/storage)