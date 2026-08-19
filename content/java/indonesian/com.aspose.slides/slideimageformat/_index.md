---
title: SlideImageFormat
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan format di mana gambar slide akan disimpan untuk presentasi pada ekspor HTML.
type: docs
url: /id/com.aspose.slides/slideimageformat/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Menentukan format di mana gambar slide akan disimpan untuk presentasi pada ekspor HTML.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slides should converted to a SVG format. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slides should be converted to a raster image. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Slides should converted to a SVG format.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Options for SVG export. |

**Mengembalikan:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Objek [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Slides should be converted to a raster image.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scale | float | The factor by which to scale the output image. |
| imageFormat | int | The format of the resulting image (e.g., PNG, JPEG). |

**Mengembalikan:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -