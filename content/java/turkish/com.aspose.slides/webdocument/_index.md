---
title: WebDocument
second_title: Aspose.Slides for Java API Referansı
description: Sunumun web formatında kaydedilmesi için bir geçiş formunu temsil eder.
type: docs
url: /tr/com.aspose.slides/webdocument/
---
**Kalıtım:**
java.lang.Object
```
public class WebDocument
```

Sunumun web formatında kaydedilmesi için bir geçiş formunu temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) yapıcı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [save()](#save--) | Belge çıktısını kaydeder. |
| [getInput()](#getInput--) | Belgenin giriş öğelerinin (şablonlar) koleksiyonunu döndürür. |
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


Belgenin giriş öğelerinin (şablonlar) koleksiyonunu döndürür. Salt okunur [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Döndürür:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Belgenin çıktı öğelerinin koleksiyonunu döndürür. Salt okunur [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // "slideMargin" özelliğini şablonlardan kullanmak için ekleyin
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... belgenin diğer seçeneklerini ayarlayın ve ardından belgeyi kaydedin
>   document.save();
> ```


**Döndürür:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Belgenin global depolamasını döndürür. Salt okunur [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // "slideMargin" özelliğini şablonlarda kullanmak için ekleyin
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... belgenin diğer seçeneklerini ayarlayın ve ardından belgeyi kaydedin
>   document.save();
> ```

**Döndürür:**
[Storage](../../com.aspose.slides/storage)