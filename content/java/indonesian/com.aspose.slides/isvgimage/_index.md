---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
url: /id/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Mewakili gambar SVG.
## Metode

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | Mengembalikan konten SVG. |
| [getSvgData()](#getSvgData--) | Mengembalikan data SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | Mengembalikan antarmuka callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen SVG. |
| [getBaseUri()](#getBaseUri--) | Mengembalikan URI dasar dari SVG yang ditentukan. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Menyimpan gambar SVG sebagai file EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


Mengembalikan konten SVG. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


Mengembalikan data SVG. Hanya-baca byte[].

**Mengembalikan:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


Mengembalikan antarmuka callback yang digunakan untuk menyelesaikan sumber daya eksternal selama impor dokumen SVG. Hanya-baca [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**Mengembalikan:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


Mengembalikan URI dasar dari SVG yang ditentukan. Digunakan untuk menyelesaikan tautan relatif. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


Menyimpan gambar SVG sebagai file EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
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
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran target |