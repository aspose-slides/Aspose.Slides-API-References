---
title: CommonSlideViewProperties
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili properti tampilan slide umum.
type: docs
url: /id/com.aspose.slides/commonslideviewproperties/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

Mewakili properti tampilan slide umum.

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // Membuat objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Mengatur Properti Tampilan Presentasi
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // Nilai zoom dalam persentase untuk tampilan slide
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // Nilai zoom dalam persentase untuk tampilan catatan
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getScale()](#getScale--) | Menetapkan rasio skala tampilan dalam persentase. |
| [setScale(int value)](#setScale-int-) | Menetapkan rasio skala tampilan dalam persentase. |
| [getVariableScale()](#getVariableScale--) | Menetapkan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Menetapkan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan menggambar. |
### getScale() {#getScale--}
```
public final int getScale()
```

Menetapkan rasio skala tampilan dalam persentase. Read/write int.

**Mengembalikan:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

Menetapkan rasio skala tampilan dalam persentase. Read/write int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

Menetapkan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. Read/write boolean.

**Mengembalikan:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

Menetapkan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. Read/write boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Mengembalikan koleksi panduan menggambar. Read-only [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Menambahkan panduan gambar vertikal baru di sebelah kanan tengah slide
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // Menambahkan panduan gambar horizontal baru di bawah tengah slide
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)