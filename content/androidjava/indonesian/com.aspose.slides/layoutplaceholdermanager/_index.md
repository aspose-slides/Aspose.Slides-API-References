---
title: LayoutPlaceholderManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili manajer yang memungkinkan Anda menambahkan placeholder ke slide tata letak.
type: docs
url: /id/com.aspose.slides/layoutplaceholdermanager/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Mewakili manajer yang memungkinkan Anda menambahkan placeholder ke slide tata letak.
## Metode

| Method | Description |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung bagan. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung tabel. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram SmartArt. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung objek media. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar daring. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Konten.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal.

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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Konten (Vertikal).
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Text ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Teks.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Text (Vertikal) ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Teks (Vertikal).
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Picture ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Gambar.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung bagan.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Chart ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Bagan.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung tabel.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Table ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Tabel.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram SmartArt.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder SmartArt ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder SmartArt.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung objek media.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Media ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Media.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung gambar daring.

--------------------

> ```
> Berikut contoh menunjukkan cara menambahkan bentuk placeholder Online Image ke slide tata letak.
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
| width | float | Lebar bentuk placeholder baru. |
| height | float | Tinggi bentuk placeholder baru. |

**Mengembalikan:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Dibuat [IAutoShape](../../com.aspose.slides/iautoshape) dengan placeholder Gambar Daring.