---
title: IZoomFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek Slide Zoom dalam sebuah slide.
type: docs
url: /id/com.aspose.slides/izoomframe/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Mewakili objek Slide Zoom dalam sebuah slide.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. |

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. Baca/tulis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Mendapatkan atau mengatur objek slide yang ditautkan oleh objek Slide Zoom. Baca/tulis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Contoh berikut menunjukkan perubahan slide target dan membuat gambar baru untuk objek Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |