---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: Callback interface used to resolve external resources during Html Svg documents import.
type: docs
url: /id/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

Antarmuka callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Html, Svg.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
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
public abstract InputStream getEntity(String absoluteUri)
```

Memetakan URI ke objek yang berisi sumber daya sebenarnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI absolut ke objek. |

**Mengembalikan:**
java.io.InputStream - Objek InputStream atau null jika sumber daya tidak dapat di-stream.