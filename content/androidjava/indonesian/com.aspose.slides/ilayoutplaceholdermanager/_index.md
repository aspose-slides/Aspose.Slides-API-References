---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili manajer yang memungkinkan Anda menambahkan placeholder ke slide tata letak.
type: docs
url: /id/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Mewakili manajer yang memungkinkan Anda menambahkan placeholder ke slide tata letak.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media atau teks. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media atau teks dalam arah vertikal. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung tabel. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung objek media. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar daring. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media atau teks.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Content.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media atau teks dalam arah vertikal.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Content (Vertical).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Text.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Text (Vertical).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Picture.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Chart.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung tabel.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Table.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram SmartArt.

--------------------

> ```
> The following example shows how to add the SmartArt placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung objek media.

--------------------

> ```
> The following example shows how to add the Media placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar daring.

--------------------

> ```
> The following example shows how to add the Online Image placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat X dari bentuk placeholder baru. |
| y | float | Koordinat Y dari bentuk placeholder baru. |
| width | float | Lebar dari bentuk placeholder baru. |
| height | float | Tinggi dari bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Online Image.