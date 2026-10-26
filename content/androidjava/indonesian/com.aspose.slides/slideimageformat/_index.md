---
title: SlideImageFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan format di mana gambar slide akan disimpan untuk ekspor presentasi ke HTML.
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

Menentukan format dimana gambar slide akan disimpan untuk ekspor presentasi ke HTML.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Slide harus dikonversi ke format SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Slide harus dikonversi ke gambar raster. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Slide harus dikonversi ke format SVG.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opsi untuk ekspor SVG. |

**Mengembalikan:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - Objek [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Slide harus dikonversi ke gambar raster.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scale | float | Faktor yang digunakan untuk memperbesar gambar output. |
| imageFormat | int | Format gambar yang dihasilkan (mis., PNG, JPEG). |

**Mengembalikan:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -  