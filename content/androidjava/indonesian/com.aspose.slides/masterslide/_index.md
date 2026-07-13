---
title: MasterSlide
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili slide master dalam presentasi.
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

Mewakili slide master dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari master slide. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Membuat master slide baru berdasarkan yang saat ini, menerapkan tema eksternal padanya dan menerapkan master slide yang dibuat ke semua slide yang bergantung. |
| [getTitleStyle()](#getTitleStyle--) | Mengembalikan gaya teks judul. |
| [getBodyStyle()](#getBodyStyle--) | Mengembalikan gaya teks badan. |
| [getOtherStyle()](#getOtherStyle--) | Mengembalikan gaya teks lainnya. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan koleksi slide tata letak anak untuk master slide ini. |
| [getPreserve()](#getPreserve--) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array dengan semua slide yang bergantung pada master slide ini. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada master slide ini. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan manajer tema. |
| [getName()](#getName--) | Mengembalikan atau mengatur nama master slide. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama master slide. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk master slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan manajer HeaderFooter dari master slide. Hanya-baca [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Mengembalikan:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Membuat master slide baru berdasarkan yang saat ini, menerapkan tema eksternal padanya dan menerapkan master slide yang dibuat ke semua slide yang bergantung.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file tema eksternal (.thmx). |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide bertema baru.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```


Mengembalikan gaya teks judul. Hanya-baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```


Mengembalikan gaya teks badan. Hanya-baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```


Mengembalikan gaya teks lainnya. Hanya-baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```


Mengembalikan koleksi slide tata letak anak untuk master slide ini. Hanya-baca [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambah/menyisipkan/menghapus/menyalin slide tata letak dengan menggunakan properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Mengembalikan:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```


Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis; untuk benar-benar menghapus master yang tidak terpakai panggil [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Baca/tulis boolean .

**Mengembalikan:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```


Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. Catatan: Aspose.Slides tidak akan pernah menghapus master yang tidak terpakai secara otomatis; untuk benar-benar menghapus master yang tidak terpakai panggil [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Mengembalikan array dengan semua slide yang bergantung pada master slide ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array dari [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Mengembalikan true jika terdapat setidaknya satu slide yang bergantung pada master slide ini. Hanya-baca boolean .

**Mengembalikan:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Mengembalikan manajer tema. Hanya-baca [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Mengembalikan:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```


Mengembalikan atau mengatur nama master slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Mengembalikan atau mengatur nama master slide. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean .

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar untuk master slide. Hanya-baca [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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