---
title: XpsOptions
second_title: Aspose.Slides untuk Referensi API Java
description: Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format XPS.
type: docs
url: /id/com.aspose.slides/xpsoptions/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

Menyediakan opsi yang mengontrol cara presentasi disimpan dalam format XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // Menyimpan presentasi ke dokumen XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // Membuat instance objek Presentation yang mewakili file presentasi
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // Membuat instance kelas TiffOptions
>      XpsOptions options = new XpsOptions();
>      // Simpan MetaFiles sebagai PNG
>      options.setSaveMetafilesAsPng(true);
>      // Menyimpan presentasi ke dokumen XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | Konstruktor default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


Konstruktor default.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Nilai default adalah **false**.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Nilai default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Boolean baca/tulis.

--------------------

Nilai default adalah **true**.

**Mengembalikan:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Boolean baca/tulis.

--------------------

Nilai default adalah **true**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True untuk menggambar bingkai hitam di sekitar setiap slide. Boolean baca/tulis.

--------------------

Nilai default adalah **false**.

**Mengembalikan:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True untuk menggambar bingkai hitam di sekitar setiap slide. Boolean baca/tulis.

--------------------

Nilai default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |