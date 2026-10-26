---
title: LayoutSlide
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili slide tata letak.
type: docs
url: /id/com.aspose.slides/layoutslide/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Mewakili slide tata letak.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide tata letak. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Mengembalikan manajer placeholder dari slide tata letak. |
| [getMasterSlide()](#getMasterSlide--) | Mengembalikan atau mengatur master slide untuk tata letak. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Mengembalikan atau mengatur master slide untuk tata letak. |
| [remove()](#remove--) | Menghapus tata letak dari presentasi. |
| [getThemeManager()](#getThemeManager--) | Mengembalikan manajer tema yang menggantikan. |
| [getLayoutType()](#getLayoutType--) | Mengembalikan tipe tata letak dari slide tata letak ini. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array dengan semua slide yang bergantung pada slide tata letak ini. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada slide tata letak ini. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan menggambar untuk slide tata letak. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter dari slide tata letak. Baca-saja [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Mengembalikan:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Mengembalikan manajer placeholder dari slide tata letak. Baca-saja [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Mengembalikan:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Mengembalikan atau mengatur master slide untuk tata letak. Baca/tulis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Mengembalikan atau mengatur master slide untuk tata letak. Baca/tulis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Menghapus tata letak dari presentasi.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Mengembalikan manajer tema yang menggantikan. Baca-saja [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Mengembalikan:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Mengembalikan tipe tata letak dari slide tata letak ini. Baca-saja [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Mengembalikan:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Mengembalikan array dengan semua slide yang bergantung pada slide tata letak ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Mengembalikan true jika ada setidaknya satu slide yang bergantung pada slide tata letak ini. Baca-saja boolean .

**Mengembalikan:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Baca/tulis boolean .

**Mengembalikan:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Menentukan apakah shape pada master slide harus ditampilkan pada slide atau tidak. Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Mengembalikan koleksi panduan menggambar untuk slide tata letak. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Menambahkan panduan gambar vertikal baru ke kiri tengah slide
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)