---
title: IMasterHandoutSlide
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili slide master untuk handout.
type: docs
url: /id/com.aspose.slides/imasterhandoutslide/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterHandoutSlide extends IBaseSlide, IMasterThemeable
```

Mewakili slide master untuk handout.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari slide master handout. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan menggambar untuk slide master handout. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```


Mengembalikan manajer HeaderFooter dari slide master handout. Hanya-baca [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Mengembalikan:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan menggambar untuk slide master handout. Hanya-baca [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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