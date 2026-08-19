---
title: SvgImage
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili gambar SVG.
type: docs
url: /id/com.aspose.slides/svgimage/
---
**Warisan:**
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
| [SvgImage(byte[] data)](#SvgImage-byte---) | Creates new SvgImage object. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | Creates new SvgImage object. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Creates new SvgImage object. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSvgData()](#getSvgData--) | Returns SVG data. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Return callback interface used to resolve external resources during Svg documents import. |
| [getBaseUri()](#getBaseUri--) | Returns base URI of the specified Svg. |
| [getSvgContent()](#getSvgContent--) | Returns SVG content. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Saves the SVG image as an EMF file. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | java.lang.String | Konten SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| data | byte[] | Data SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek panggilan balik yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari SVG yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| svgContent | java.lang.String | Konten SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek panggilan balik yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari SVG yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```


Membuat objek SvgImage baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Aliran SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Objek panggilan balik yang digunakan untuk mengambil objek eksternal. Jika parameter ini null semua objek eksternal akan diabaikan. |
| baseUri | java.lang.String | URI dasar dari SVG yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```


Mengembalikan data SVG. Hanya baca byte[].

**Mengembalikan:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```


Mengembalikan antarmuka panggilan balik yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen Svg. Hanya baca [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Mengembalikan:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```


Mengembalikan URI dasar dari SVG yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. Hanya baca String.

**Mengembalikan:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```


Mengembalikan konten SVG. Hanya baca String.

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
>  // Membuat gambar SVG baru
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Menyimpan gambar SVG sebagai metafile
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Membuat gambar SVG baru
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Menyimpan gambar SVG sebagai metafile
>      svgImage.writeAsEmf(byteStream);
>      // Menambahkan metafile ke koleksi gambar
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |