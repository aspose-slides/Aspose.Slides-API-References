---
title: SectionZoomFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek Section Zoom dalam slide.
type: docs
url: /id/com.aspose.slides/sectionzoomframe/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Mewakili objek Section Zoom dalam slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Mendapatkan atau mengatur objek section yang ditautkan oleh objek Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Mendapatkan atau mengatur objek section yang ditautkan oleh objek Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```

Mendapatkan atau mengatur objek section yang ditautkan oleh objek Section Zoom. Baca/tulis [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Contoh berikut menunjukkan perubahan bagian target dan membuat gambar baru untuk objek section zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```

Mendapatkan atau mengatur objek section yang ditautkan oleh objek Section Zoom. Baca/tulis [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Contoh berikut menunjukkan perubahan bagian target dan membuat gambar baru untuk objek section zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |