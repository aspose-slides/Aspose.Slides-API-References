---
title: MasterNotesSlide
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili master slide untuk catatan.
type: docs
url: /id/com.aspose.slides/masternotesslide/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Mewakili master slide untuk catatan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan pengelola HeaderFooter dari master notes slide. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan pengelola tema. |
| [getNotesStyle()](#getNotesStyle--) | Mengembalikan gaya teks catatan. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan menggambar untuk master notes slide. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Menentukan apakah bentuk pada master slide harus ditampilkan pada slide atau tidak. Untuk master slide itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan pengelola HeaderFooter dari master notes slide. Hanya-baca [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Mengembalikan:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Mengembalikan pengelola tema. Hanya-baca [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Mengembalikan:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```


Mengembalikan gaya teks catatan. Hanya-baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan menggambar untuk master notes slide. Hanya-baca [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Menambahkan panduan menggambar horizontal baru di bawah tengah slide
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)