---
title: IXpsOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format XPS.
type: docs
url: /id/com.aspose.slides/ixpsoptions/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

Menyediakan opsi yang mengontrol bagaimana presentasi disimpan dalam format XPS.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True untuk menggambar bingkai hitam di sekitar setiap slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Default adalah **true**.

**Mengembalikan:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True untuk mengonversi semua metafile yang digunakan dalam presentasi menjadi gambar PNG. Baca/tulis boolean.

--------------------

Default adalah **true**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Default adalah **false**.

**Mengembalikan:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True untuk menggambar bingkai hitam di sekitar setiap slide. Baca/tulis boolean.

--------------------

Default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**.

**Mengembalikan:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Menentukan apakah dokumen yang dihasilkan harus menyertakan slide tersembunyi atau tidak. Default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |