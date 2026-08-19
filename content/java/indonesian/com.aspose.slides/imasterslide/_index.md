---
title: IMasterSlide
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili master slide dalam sebuah presentasi.
type: docs
url: /id/com.aspose.slides/imasterslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Mewakili master slide dalam sebuah presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan pengelola HeaderFooter dari master slide. |
| [getTitleStyle()](#getTitleStyle--) | Mengembalikan gaya teks judul. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Membuat master slide baru berdasarkan yang saat ini, menerapkan tema eksternal padanya dan menerapkan master slide yang dibuat ke semua slide yang bergantung. |
| [getBodyStyle()](#getBodyStyle--) | Mengembalikan gaya teks badan. |
| [getOtherStyle()](#getOtherStyle--) | Mengembalikan gaya teks lain. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan koleksi layout slide anak untuk master slide ini. |
| [getPreserve()](#getPreserve--) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Menentukan apakah master yang bersangkutan dihapus ketika semua slide yang mengikuti master tersebut dihapus. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada master slide ini. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array dengan semua slide yang bergantung pada master slide ini. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk master slide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan pengelola HeaderFooter dari master slide. Baca-saja [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

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


Membuat master slide baru berdasarkan yang saat ini, menerapkan tema eksternal padanya dan menerapkan master slide yang dibuat ke semua slide yang bergantung.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fname | java.lang.String | Jalur ke file tema eksternal (.thmx). |

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - MasterSlide baru yang memiliki tema.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Mengembalikan gaya teks badan. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Mengembalikan gaya teks lain. Baca-saja [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Mengembalikan koleksi layout slide anak untuk master slide ini. Baca-saja [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambah/menyisipkan/menghapus/mengkloning layout slide dengan menggunakan properti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Mengembalikan true jika ada setidaknya satu slide yang bergantung pada master slide ini. Baca-saja boolean.

**Mengembalikan:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Mengembalikan array dengan semua slide yang bergantung pada master slide ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array dari [ISlide](../../com.aspose.slides/islide), yang bergantung pada master slide ini
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar untuk master slide. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Adding the new vertical drawing guide to the right of the slide center
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)