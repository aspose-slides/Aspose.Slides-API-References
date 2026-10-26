---
title: Compress
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sekelompok metode yang ditujukan untuk mengompres .
type: docs
url: /id/com.aspose.slides/compress/
---
**Keturunan:**
java.lang.Object
```
public class Compress
```

Mewakili sekelompok metode yang ditujukan untuk mengkompres [Presentation](../../com.aspose.slides/presentation).

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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus master slide yang tidak digunakan. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus layout slide yang tidak digunakan. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus karakter yang tidak digunakan dari font yang tertanam. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus master slide yang tidak digunakan.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus layout slide yang tidak digunakan.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Melakukan kompresi [Presentation](../../com.aspose.slides/presentation) dengan menghapus karakter yang tidak digunakan dari font yang tertanam.

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
| pres | [Presentation](../../com.aspose.slides/presentation) | Instansi presentasi |