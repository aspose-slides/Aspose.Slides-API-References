---
title: Compress
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekelompok metode yang dimaksudkan untuk mengompres .
type: docs
url: /id/com.aspose.slides/compress/
---
**Warisan:**
java.lang.Object
```
public class Compress
```

Mewakili sekelompok metode yang dimaksudkan untuk mengompres [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Mengurangi ukuran presentasi dengan menerapkan semua langkah kompresi yang tersedia:

 *  Menghapus master slide yang tidak terpakai \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Menghapus layout slide yang tidak terpakai \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Menyimpan hanya glyph yang benar-benar digunakan dalam font yang disematkan \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Mengurangi resolusi gambar menjadi 150 DPI dan menghapus area yang dipotong dari gambar \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus master slide yang tidak terpakai. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus layout slide yang tidak terpakai. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus karakter yang tidak terpakai dari font yang disematkan. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Mengurangi resolusi gambar dalam presentasi dan menghapus area yang dipotong, mirip dengan fitur "Compress Pictures" di PowerPoint yang diterapkan pada semua gambar. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Mengurangi ukuran presentasi dengan menerapkan semua langkah kompresi yang tersedia:

 *  Menghapus master slide yang tidak terpakai \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Menghapus layout slide yang tidak terpakai \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Menyimpan hanya glyph yang benar-benar digunakan dalam font yang disematkan \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Mengurangi resolusi gambar menjadi 150 DPI dan menghapus area yang dipotong dari gambar \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Presentasi yang akan dikompres. |

--------------------

Untuk menyesuaikan kompresi, misalnya untuk menggunakan resolusi gambar yang berbeda atau melewati suatu langkah, panggil metode-metode yang tercantum di atas secara individual alih-alih yang ini. Area yang dipotong dari gambar dihapus secara permanen dan tidak dapat dipulihkan di PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus master slide yang tidak terpakai.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi. |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus layout slide yang tidak terpakai.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi. |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus karakter yang tidak terpakai dari font yang disematkan.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi. |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Mengurangi resolusi gambar dalam presentasi dan menghapus area yang dipotong, mirip dengan fitur "Compress Pictures" di PowerPoint yang diterapkan pada semua gambar. Gambar pada slide, layout slide, dan master slide diproses, termasuk gambar di dalam grup shape dan isian gambar pada shape.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentasi yang akan diproses. |
| resolution | int | Resolusi target relatif terhadap ukuran saat masing-masing gambar ditampilkan. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) membiarkan gambar tidak berubah.

Gambar yang sudah berada pada atau di bawah resolusi target dibiarkan tidak berubah; gambar tidak pernah ditingkatkan skalanya.

Tidak diproses: latar belakang slide, isian sel tabel, diagram, SmartArt, gambar GIF (untuk mempertahankan animasi), gambar SVG dan metafile (EMF/WMF).

Area yang dipotong dihapus secara permanen dan tidak dapat dipulihkan di PowerPoint. |