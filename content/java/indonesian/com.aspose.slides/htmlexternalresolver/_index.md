---
title: HtmlExternalResolver
second_title: Referensi API Aspose.Slides untuk Java
description: Objek callback yang digunakan oleh rutin impor HTML untuk memperoleh objek yang dirujuk seperti gambar.
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

Objek callback yang digunakan oleh rutin impor HTML untuk memperoleh objek yang dirujuk seperti gambar.

--------------------

Menggunakan resolver ini dapat menyebabkan kerentanan ketika file HTML yang disediakan klien membuat perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menentukan HtmlExternalResolver sama sekali (hanya objek yang disematkan yang akan dibaca) atau membuat subclass yang memeriksa apakah uri yang ditentukan valid.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Menyelesaikan URI absolut dari URI dasar dan relatif. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Memetakan URI ke objek yang berisi sumber daya sebenarnya. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Menyelesaikan URI absolut dari URI dasar dan relatif.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseUri | java.lang.String | URI dasar dari objek yang menautkan |
| relativeUri | java.lang.String | URI relatif ke objek yang ditautkan. |

**Mengembalikan:**
java.lang.String - URI absolut atau null jika URI relatif tidak dapat diselesaikan.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Memetakan URI ke objek yang berisi sumber daya sebenarnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolut ke objek. |

**Mengembalikan:**
java.io.InputStream - Objek InputStream atau null jika sumber daya tidak dapat di-stream.