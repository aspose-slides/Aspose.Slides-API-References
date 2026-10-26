---
title: ZoomObject
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili objek Zoom dalam slide.
type: docs
url: /id/com.aspose.slides/zoomobject/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public class ZoomObject extends GraphicalObject implements IZoomObject
```

Mewakili objek Zoom dalam slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImageType()](#getImageType--) | Mendapatkan atau mengatur tipe gambar dari objek zoom. |
| [setImageType(int value)](#setImageType-int-) | Mendapatkan atau mengatur tipe gambar dari objek zoom. |
| [getReturnToParent()](#getReturnToParent--) | Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. |
| [getShowBackground()](#getShowBackground--) | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. |
| [getZoomImage()](#getZoomImage--) | Mendapatkan atau mengatur gambar untuk objek zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Mendapatkan atau mengatur gambar untuk objek zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. |
### getImageType() {#getImageType--}
```
public final int getImageType()
```

Mendapatkan atau mengatur tipe gambar dari objek zoom. Baca/tulis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Nilai default: Preview

--------------------

> ```
> Contoh berikut menunjukkan mengubah Image Type menjadi nilai Preview. 
>  Dalam kasus ini gambar saat ini dari objek Zoom berubah menjadi gambar slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Menentukan apakah objek Zoom menggunakan pratinjau slide atau gambar sampul.

**Mengembalikan:**
int
### setImageType(int value) {#setImageType-int-}
```
public final void setImageType(int value)
```

Mendapatkan atau mengatur tipe gambar dari objek zoom. Baca/tulis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Nilai default: Preview

--------------------

> ```
> Contoh berikut menunjukkan mengubah Image Type menjadi nilai Preview. 
>  Dalam kasus ini gambar saat ini dari objek Zoom berubah menjadi gambar slide:
>  
  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>          zoomFrame.setImageType(ZoomImageType.Preview);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Menentukan apakah objek Zoom menggunakan pratinjau slide atau gambar sampul.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getReturnToParent() {#getReturnToParent--}
```
public final boolean getReturnToParent()
```

Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. Baca/tulis boolean. Nilai default: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Nilai true properti ini menentukan perilaku navigasi kembali ke induk dalam tayangan slide.

**Mengembalikan:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public final void setReturnToParent(boolean value)
```

Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. Baca/tulis boolean. Nilai default: false

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setReturnToParent(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Nilai true properti ini menentukan perilaku navigasi kembali ke induk dalam tayangan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public final boolean getShowBackground()
```

Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca/tulis boolean. Nilai default: true

--------------------

> ```
> contoh ini menunjukkan menghapus latar belakang gambar dari objek Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean
### setShowBackground(boolean value) {#setShowBackground-boolean-}
```
public final void setShowBackground(boolean value)
```

Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca/tulis boolean. Nilai default: true

--------------------

> ```
> contoh ini menunjukkan menghapus latar belakang gambar dari objek Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setShowBackground(false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getZoomImage() {#getZoomImage--}
```
public final IPPImage getZoomImage()
```

Mendapatkan atau mengatur gambar untuk objek zoom. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> contoh ini menunjukkan mengubah gambar dari objek Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IPPImage](../../com.aspose.slides/ippimage)
### setZoomImage(IPPImage value) {#setZoomImage-com.aspose.slides.IPPImage-}
```
public final void setZoomImage(IPPImage value)
```

Mendapatkan atau mengatur gambar untuk objek zoom. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> contoh ini menunjukkan mengubah gambar dari objek Zoom:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          zoomFrame.setImage(image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |
### getTransitionDuration() {#getTransitionDuration--}
```
public final float getTransitionDuration()
```

Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. Baca/tulis float. Nilai default: 1.0f

--------------------

> ```
> contoh ini menunjukkan mengubah durasi transisi antara Zoom dan slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan waktu yang terkait dengan transisi tersebut.

**Mengembalikan:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public final void setTransitionDuration(float value)
```

Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. Baca/tulis float. Nilai default: 1.0f

--------------------

> ```
> contoh ini menunjukkan mengubah durasi transisi antara Zoom dan slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan waktu yang terkait dengan transisi tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |