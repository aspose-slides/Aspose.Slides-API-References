---
title: MasterNotesSlide
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili slide master untuk catatan.
type: docs
url: /id/com.aspose.slides/masternotesslide/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Mewakili slide master untuk catatan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide catatan master. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan manajer tema. |
| [getNotesStyle()](#getNotesStyle--) | Mengembalikan gaya teks catatan. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk slide catatan master. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. Untuk slide master itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. Untuk slide master itu sendiri properti ini selalu mengembalikan false. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter dari slide catatan master. Hanya-baca [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Mengembalikan:**
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Mengembalikan manajer tema. Hanya-baca [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

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

Mengembalikan koleksi panduan gambar untuk slide catatan master. Hanya-baca [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Menambahkan panduan gambar horizontal baru di bawah pusat slide
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)