---
title: MasterSlide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili slide master dalam sebuah presentasi.
type: docs
url: /id/com.aspose.slides/masterslide/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Mewakili slide master dalam sebuah presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide master. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Membuat slide master baru berdasarkan slide saat ini, menerapkan tema eksternal padanya, dan menerapkan slide master yang dibuat ke semua slide yang bergantung. |
| [getTitleStyle()](#getTitleStyle--) | Mengembalikan gaya teks judul. |
| [getBodyStyle()](#getBodyStyle--) | Mengembalikan gaya teks isi. |
| [getOtherStyle()](#getOtherStyle--) | Mengembalikan gaya teks lain. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan koleksi slide tata letak anak untuk slide master ini. |
| [getPreserve()](#getPreserve--) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array dengan semua slide yang bergantung pada slide master ini. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada slide master ini. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan manajer tema. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama slide master. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama slide master. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk slide master. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter dari slide master. Baca-saja [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Mengembalikan:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Membuat slide master baru berdasarkan slide saat ini, menerapkan tema eksternal padanya, dan menerapkan slide master yang dibuat ke semua slide yang bergantung.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file tema eksternal (.thmx). |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide baru dengan tema.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Mengembalikan gaya teks judul. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Mengembalikan gaya teks isi. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Mengembalikan gaya teks lain. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Mengembalikan koleksi slide tata letak anak untuk slide master ini. Baca-saja [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambahkan/menyisipkan/menghapus/menyalin slide tata letak dengan menggunakan properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Mengembalikan:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai sendiri, untuk benar-benar menghapus master yang tidak terpakai panggil [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Baca-tulis boolean .

**Mengembalikan:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai sendiri, untuk benar-benar menghapus master yang tidak terpakai panggil [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Baca-tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Mengembalikan array dengan semua slide yang bergantung pada slide master ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada slide master ini. Baca-saja boolean .

**Mengembalikan:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Mengembalikan manajer tema. Baca-saja [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Mengembalikan:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Mengembalikan atau mengatur nama slide master. Baca-tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Mengembalikan atau mengatur nama slide master. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. Untuk slide master itu sendiri properti ini selalu mengembalikan false. Baca-tulis boolean .

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. Untuk slide master itu sendiri properti ini selalu mengembalikan false. Baca-tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Mengembalikan koleksi panduan gambar untuk slide master. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
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