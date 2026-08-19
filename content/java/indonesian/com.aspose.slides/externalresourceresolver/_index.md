---
title: ExternalResourceResolver
second_title: Referensi API Aspose.Slides untuk Java
description: Kelas callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Html dan Svg.
type: docs
url: /id/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Kelas Callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Html, Svg.

--------------------

Menggunakan resolver ini dapat menimbulkan kerentanan ketika file HTML atau SVG yang diberikan klien menyebabkan perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menyebutkan ExternalResourceResolver sama sekali (hanya objek yang disematkan yang akan dibaca) atau membuat subclass yang memeriksa apakah uri yang ditentukan valid.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


Resolves the absolute URI from the base and relative URIs.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| baseUri | java.lang.String | URI dasar dari objek yang menautkan |
| relativeUri | java.lang.String | URI relatif ke objek yang ditautkan. |

**Mengembalikan:**
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


Maps a URI to an object containing the actual resource.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolut ke objek. |

**Mengembalikan:**
java.io.InputStream - Objek InputStream atau null jika sumber daya tidak dapat di-stream.