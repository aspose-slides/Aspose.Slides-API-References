---
title: IZoomObject
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili objek Zoom dalam slide.
type: docs
url: /id/com.aspose.slides/izoomobject/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IZoomObject extends IGraphicalObject
```

Mewakili sebuah objek Zoom dalam slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getImageType()](#getImageType--) | Mendapatkan atau mengatur tipe gambar dari objek Zoom. |
| [setImageType(int value)](#setImageType-int-) | Mendapatkan atau mengatur tipe gambar dari objek Zoom. |
| [getReturnToParent()](#getReturnToParent--) | Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. |
| [setReturnToParent(boolean value)](#setReturnToParent-boolean-) | Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. |
| [getShowBackground()](#getShowBackground--) | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. |
| [setShowBackground(boolean value)](#setShowBackground-boolean-) | Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. |
| [getZoomImage()](#getZoomImage--) | Mendapatkan atau mengatur gambar untuk objek Zoom. |
| [setZoomImage(IPPImage value)](#setZoomImage-com.aspose.slides.IPPImage-) | Mendapatkan atau mengatur gambar untuk objek Zoom. |
| [getTransitionDuration()](#getTransitionDuration--) | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. |
| [setTransitionDuration(float value)](#setTransitionDuration-float-) | Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. |
### getImageType() {#getImageType--}
```
public abstract int getImageType()
```

Mendapatkan atau mengatur tipe gambar dari objek Zoom. Baca/tulis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Nilai default: Preview

--------------------

> ```
> Contoh ini menunjukkan cara mengubah Image Type menjadi nilai Preview. 
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
public abstract void setImageType(int value)
```

Mendapatkan atau mengatur tipe gambar dari objek Zoom. Baca/tulis [ZoomImageType](../../com.aspose.slides/zoomimagetype). Nilai default: Preview

--------------------

> ```
> Contoh ini menunjukkan cara mengubah Image Type menjadi nilai Preview. 
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
public abstract boolean getReturnToParent()
```

Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. Baca/tulis boolean. Nilai default: false

--------------------

> ```
> Contoh:
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

Nilai true dari properti menentukan perilaku navigasi kembali ke induk dalam tayangan slide.

**Mengembalikan:**
boolean
### setReturnToParent(boolean value) {#setReturnToParent-boolean-}
```
public abstract void setReturnToParent(boolean value)
```

Mendapatkan atau mengatur perilaku navigasi dalam tayangan slide. Baca/tulis boolean. Nilai default: false

--------------------

> ```
> Contoh:
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

Nilai true dari properti menentukan perilaku navigasi kembali ke induk dalam tayangan slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowBackground() {#getShowBackground--}
```
public abstract boolean getShowBackground()
```

Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca/tulis boolean. Nilai default: true

--------------------

> ```
> Contoh ini menunjukkan cara menghapus latar belakang gambar dari objek Zoom:
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
public abstract void setShowBackground(boolean value)
```

Mendapatkan atau mengatur nilai yang menentukan apakah Zoom akan menggunakan latar belakang slide tujuan. Baca/tulis boolean. Nilai default: true

--------------------

> ```
> Contoh ini menunjukkan cara menghapus latar belakang gambar dari objek Zoom:
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
public abstract IPPImage getZoomImage()
```

Mendapatkan atau mengatur gambar untuk objek Zoom. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Contoh ini menunjukkan cara mengubah gambar dari objek Zoom:
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
public abstract void setZoomImage(IPPImage value)
```

Mendapatkan atau mengatur gambar untuk objek Zoom. Baca/tulis [IPPImage](../../com.aspose.slides/ippimage).

--------------------

> ```
> Contoh ini menunjukkan cara mengubah gambar dari objek Zoom:
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
public abstract float getTransitionDuration()
```

Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. Baca/tulis float. Nilai default: 1.0f

--------------------

> ```
> Contoh ini menunjukkan cara mengubah durasi transisi antara Zoom dan slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan timing yang terkait dengan transisi tersebut.

**Mengembalikan:**
float
### setTransitionDuration(float value) {#setTransitionDuration-float-}
```
public abstract void setTransitionDuration(float value)
```

Mendapatkan atau mengatur durasi transisi antara Zoom dan slide. Baca/tulis float. Nilai default: 1.0f

--------------------

> ```
> the example demonstrates changing the duration of the transition between Zoom and slide:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>       zoomFrame.setTransitionDuration(2.5f);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Jika tidak ditentukan (TransitionDur = 0), akan menggunakan transisi slide tujuan dan timing yang terkait dengan transisi tersebut.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |