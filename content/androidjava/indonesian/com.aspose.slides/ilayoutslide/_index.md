---
title: ILayoutSlide
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili slide tata letak.
type: docs
url: /id/com.aspose.slides/ilayoutslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Mewakili slide tata letak.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan HeaderFooter manager dari slide tata letak. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Mengembalikan placeholder manager dari slide tata letak. |
| [getMasterSlide()](#getMasterSlide--) | Mengembalikan atau mengatur master slide untuk tata letak. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Mengembalikan atau mengatur master slide untuk tata letak. |
| [getLayoutType()](#getLayoutType--) | Mengembalikan tipe tata letak dari slide tata letak ini. |
| [hasDependingSlides()](#hasDependingSlides--) | Mengembalikan true jika ada setidaknya satu slide yang bergantung pada slide tata letak ini. |
| [getDependingSlides()](#getDependingSlides--) | Mengembalikan array dengan semua slide yang bergantung pada slide tata letak ini. |
| [remove()](#remove--) | Menghapus tata letak dari presentasi. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar untuk slide tata letak. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan HeaderFooter manager dari slide tata letak. Baca-saja [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Mengembalikan:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Mengembalikan placeholder manager dari slide tata letak. Baca-saja [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Mengembalikan:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Mengembalikan atau mengatur master slide untuk tata letak. Baca/tulis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Mengembalikan:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Mengembalikan atau mengatur master slide untuk tata letak. Baca/tulis [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Mengembalikan tipe tata letak dari slide tata letak ini. Baca-saja [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Mengembalikan:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Mengembalikan true jika ada setidaknya satu slide yang bergantung pada slide tata letak ini. Baca-saja boolean.

**Mengembalikan:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Mengembalikan array dengan semua slide yang bergantung pada slide tata letak ini.

**Mengembalikan:**
com.aspose.slides.ISlide[] - Array dengan semua slide yang bergantung pada slide tata letak ini
### remove() {#remove--}
```
public abstract void remove()
```


Menghapus tata letak dari presentasi.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar untuk slide tata letak. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Menambahkan panduan gambar vertikal baru ke kiri pusat slide
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)