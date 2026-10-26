---
title: ICommonSlideViewProperties
second_title: Referensi API Java untuk Aspose.Slides for Android
description: Mewakili properti tampilan slide umum.
type: docs
url: /id/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

Mewakili properti tampilan slide umum.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getScale()](#getScale--) | Menentukan rasio skala tampilan dalam persentase. |
| [setScale(int value)](#setScale-int-) | Menentukan rasio skala tampilan dalam persentase. |
| [getVariableScale()](#getVariableScale--) | Menentukan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | Menentukan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. |
| [getDrawingGuides()](#getDrawingGuides--) | Mengembalikan koleksi panduan gambar. |
### getScale() {#getScale--}
```
public abstract int getScale()
```


Menentukan rasio skala tampilan dalam persentase. Baca/tulis int.

**Returns:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Menentukan rasio skala tampilan dalam persentase. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


Menentukan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. Baca/tulis boolean.

**Returns:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


Menentukan bahwa konten tampilan harus secara otomatis menyesuaikan skala untuk paling cocok dengan ukuran jendela saat ini. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Mengembalikan koleksi panduan gambar. Baca-saja [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // Menambahkan panduan gambar vertikal baru ke kanan tengah slide
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
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