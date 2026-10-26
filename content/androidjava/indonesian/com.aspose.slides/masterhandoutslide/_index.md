---
title: MasterHandoutSlide
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili slide master untuk handout.
type: docs
url: /id/com.aspose.slides/masterhandoutslide/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diterapkan:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Mewakili slide master untuk handout.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah bentuk pada slide master harus ditampilkan pada slide atau tidak. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide handout master. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan manajer tema. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk slide handout master. |
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
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan manajer HeaderFooter dari slide handout master. Baca-saja [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Mengembalikan:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```


Mengembalikan manajer tema. Baca-saja [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Mengembalikan:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar untuk slide handout master. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Menambahkan panduan gambar horizontal baru di atas pusat slide
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)