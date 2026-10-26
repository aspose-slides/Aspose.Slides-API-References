---
title: ISectionZoomFrame
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili objek Section Zoom dalam sebuah slide.
type: docs
url: /id/com.aspose.slides/isectionzoomframe/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Mewakili objek Section Zoom dalam sebuah slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Mendapatkan atau mengatur objek section yang terhubung dengan objek Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Mendapatkan atau mengatur objek section yang terhubung dengan objek Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```

Mendapatkan atau mengatur objek section yang terhubung dengan objek Section Zoom. Baca/tulis [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```

Mendapatkan atau mengatur objek section yang terhubung dengan objek Section Zoom. Baca/tulis [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |