---
title: IMasterSlide
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili slide master dalam sebuah presentasi.
type: docs
url: /id/com.aspose.slides/imasterslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Mewakili slide master dalam sebuah presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan pengelola HeaderFooter dari slide master. |
| [getTitleStyle()](#getTitleStyle--) | Mengembalikan gaya teks judul. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Membuat slide master baru berdasarkan slide saat ini, menerapkan tema eksternal padanya, dan menerapkan slide master yang dibuat ke semua slide yang bergantung. |
| [getBodyStyle()](#getBodyStyle--) | Mengembalikan gaya teks isi. |
| [getOtherStyle()](#getOtherStyle--) | Mengembalikan gaya teks lainnya. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan koleksi slide tata letak anak untuk slide master ini. |
| [getPreserve()](#getPreserve--) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada slide master ini. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array berisi semua slide yang bergantung pada slide master ini. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk slide master. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan pengelola HeaderFooter dari slide master. Baca-saja [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Mengembalikan:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Mengembalikan gaya teks judul. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Membuat slide master baru berdasarkan slide saat ini, menerapkan tema eksternal padanya, dan menerapkan slide master yang dibuat ke semua slide yang bergantung.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file tema eksternal (.thmx). |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide baru dengan tema.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Mengembalikan gaya teks isi. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Mengembalikan gaya teks lainnya. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Mengembalikan koleksi slide tata letak anak untuk slide master ini. Baca-saja [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambahkan/menyisipkan/menghapus/menyalin slide tata letak dengan menggunakan properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Mengembalikan:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis; untuk benar-benar menghapus master yang tidak terpakai panggil [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis; untuk benar-benar menghapus master yang tidak terpakai panggil [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada slide master ini. Baca-saja boolean.

**Mengembalikan:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Mengembalikan array berisi semua slide yang bergantung pada slide master ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide), yang bergantung pada slide master ini
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar untuk slide master. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Menambahkan panduan gambar vertikal baru ke kanan tengah slide
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)