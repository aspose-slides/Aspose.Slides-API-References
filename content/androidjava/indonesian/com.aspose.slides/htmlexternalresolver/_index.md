---
title: HtmlExternalResolver
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Objek callback yang digunakan oleh rutinitas impor HTML untuk memperoleh objek yang direferensikan seperti gambar.
type: docs
url: /id/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

Objek callback yang digunakan oleh rutinitas impor HTML untuk memperoleh objek yang direferensikan seperti gambar.

--------------------

Menggunakan resolver ini dapat menimbulkan kerentanan ketika file HTML yang diberikan klien menyebabkan perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menyebutkan HtmlExternalResolver sama sekali (hanya objek yang tersemat yang akan dibaca) atau membuat subclass yang memeriksa apakah uri yang ditentukan valid.
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Methods

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Menyelesaikan URI absolut dari URI dasar dan URI relatif. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Memetakan URI ke sebuah objek yang berisi sumber daya sebenarnya. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Menyelesaikan URI absolut dari URI dasar dan URI relatif.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | URI dasar dari objek yang menautkan |
| relativeUri | java.lang.String | URI relatif ke objek yang ditautkan. |

**Returns:**
java.lang.String - URI absolut atau null jika URI relatif tidak dapat diselesaikan.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Memetakan URI ke sebuah objek yang berisi sumber daya sebenarnya.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolut ke objek. |

**Returns:**
java.io.InputStream - Sebuah objek InputStream atau null jika sumber daya tidak dapat dialirkan.