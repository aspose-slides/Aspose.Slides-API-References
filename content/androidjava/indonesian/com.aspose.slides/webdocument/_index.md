---
title: WebDocument
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili bentuk transisi presentasi untuk disimpan dalam format web.
type: docs
url: /id/com.aspose.slides/webdocument/
---
**Warisan:**
java.lang.Object
```
public class WebDocument
```

Mewakili bentuk transisi presentasi untuk disimpan dalam format web.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) konstruktor. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [save()](#save--) | Menyimpan keluaran dokumen. |
| [getInput()](#getInput--) | Mengembalikan koleksi elemen input (template) dokumen. |
| [getOutput()](#getOutput--) | Mengembalikan koleksi elemen output dokumen. |
| [getGlobal()](#getGlobal--) | Mengembalikan penyimpanan global dokumen. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) konstruktor.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Opsi yang ditetapkan untuk dokumen. |

### save() {#save--}
```
public final void save()
```

Menyimpan keluaran dokumen.

### getInput() {#getInput--}
```
public final Input getInput()
```

Mengembalikan koleksi elemen input (template) dokumen. Baca-saja [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Mengembalikan:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```

Mengembalikan koleksi elemen output dokumen. Baca-saja [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // letakkan properti "slideMargin" untuk digunakan dari templat
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... atur opsi lain dari dokumen dan kemudian simpan dokumen
>   document.save();
> ```


**Mengembalikan:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

Mengembalikan penyimpanan global dokumen. Baca-saja [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // letakkan properti "slideMargin" untuk digunakan dari templat
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... atur opsi lain dari dokumen dan kemudian simpan dokumen
>   document.save();
> ```

**Mengembalikan:**
[Storage](../../com.aspose.slides/storage)