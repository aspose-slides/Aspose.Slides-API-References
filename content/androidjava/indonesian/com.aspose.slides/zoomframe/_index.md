---
title: ZoomFrame
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili objek Slide Zoom dalam sebuah slide.
type: docs
url: /id/com.aspose.slides/zoomframe/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Mewakili objek Slide Zoom dalam sebuah slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. Baca/tulis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Contoh berikut menunjukkan cara mengubah slide target dan membuat gambar baru untuk objek Slide Zoom:
>  
  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```


Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. Baca/tulis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Contoh berikut menunjukkan cara mengubah slide target dan membuat gambar baru untuk objek Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |