---
title: ColorReplace
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Penggantian Warna.
type: docs
url: /id/com.aspose.slides/colorreplace/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Mewakili efek Color Replacement. Semua warna efek diubah menjadi warna tetap. Nilai alpha tidak terpengaruh.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor()](#getColor--) | Mengembalikan format warna yang akan menggantikan warna setiap piksel. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Color Replacement yang efektif dengan pewarisan yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [ColorReplace](../../com.aspose.slides/colorreplace) yang ditentukan sama dengan [ColorReplace](../../com.aspose.slides/colorreplace) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Mengembalikan format warna yang akan menggantikan warna setiap piksel. Hanya-baca [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Mendapatkan data efek Color Replacement yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - sebuah [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya-baca long.

**Mengembalikan:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [ColorReplace](../../com.aspose.slides/colorreplace) yang ditentukan sama dengan [ColorReplace](../../com.aspose.slides/colorreplace) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [ColorReplace](../../com.aspose.slides/colorreplace) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek-objek sama; sebaliknya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Sebuah kode hash untuk objek saat ini.