---
title: ExternalResourceResolver
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas callback yang digunakan untuk menyelesaikan sumber daya eksternal saat mengimpor dokumen Html dan Svg.
type: docs
url: /id/com.aspose.slides/externalresourceresolver/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Kelas callback yang digunakan untuk menyelesaikan sumber daya eksternal saat mengimpor dokumen Html, Svg.

--------------------

Menggunakan resolver ini dapat menyebabkan kerentanan ketika file HTML atau SVG yang diberikan klien membuat perangkat lunak server memperoleh file lokal atau jaringan. Gunakan dengan hati-hati. Disarankan untuk tidak menyebutkan ExternalResourceResolver sama sekali (hanya objek tersemat yang akan dibaca) atau membuat subclass yang memeriksa apakah uri yang ditentukan valid.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Menyelesaikan URI absolut dari URI dasar dan URI relatif. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Memetakan sebuah URI ke objek yang berisi sumber daya sebenarnya. |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Menyelesaikan URI absolut dari URI dasar dan URI relatif.

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

Memetakan sebuah URI ke objek yang berisi sumber daya sebenarnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolut ke objek. |

**Mengembalikan:**
java.io.InputStream - sebuah objek InputStream atau null jika sumber daya tidak dapat diputar.