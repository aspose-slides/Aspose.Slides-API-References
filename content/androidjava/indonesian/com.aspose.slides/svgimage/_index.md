---
title: SvgImage
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili gambar SVG.
type: docs
url: /id/com.aspose.slides/svgimage/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

Mewakili gambar SVG.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | Membuat objek SvgImage baru. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Membuat objek SvgImage baru. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Membuat objek SvgImage baru. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat objek SvgImage baru. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat objek SvgImage baru. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Membuat objek SvgImage baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSvgData()](#getSvgData--) | Mengembalikan data SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Mengembalikan antarmuka callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Svg. |
| [getBaseUri()](#getBaseUri--) | Mengembalikan URI dasar dari Svg yang ditentukan. |
| [getSvgContent()](#getSvgContent--) | Mengembalikan konten SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Menyimpan gambar SVG sebagai file EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data Svg. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | java.lang.String | Konten Svg. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran Svg. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | java.lang.String | Konten Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek callback yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Mengembalikan data SVG. Hanya-baca byte[].

**Mengembalikan:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Mengembalikan antarmuka callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Svg. Hanya-baca [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Mengembalikan:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Mengembalikan URI dasar dari Svg yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Mengembalikan konten SVG. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```


Menyimpan gambar SVG sebagai file EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |