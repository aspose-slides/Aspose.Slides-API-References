---
title: ColorChange
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek Perubahan Warna.
type: docs
url: /id/com.aspose.slides/colorchange/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Mewakili efek Color Change. Instance FromColor diganti dengan instance ToColor.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFromColor()](#getFromColor--) | Warna yang akan digantikan. |
| [getToColor()](#getToColor--) | Warna yang akan menggantikan. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Color Change yang efektif dengan pewarisan diterapkan. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [ColorChange](../../com.aspose.slides/colorchange) yang ditentukan sama dengan [ColorChange](../../com.aspose.slides/colorchange) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Warna yang akan digantikan. Hanya baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Warna yang akan menggantikan. Hanya baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Mendapatkan data efek Color Change yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Sebuah [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya baca long.

**Mengembalikan:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [ColorChange](../../com.aspose.slides/colorchange) yang ditentukan sama dengan [ColorChange](../../com.aspose.slides/colorchange) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; jika tidak, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Sebuah kode hash untuk objek saat ini.