---
title: AlphaFloor
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Alpha Floor.
type: docs
url: /id/com.aspose.slides/alphafloor/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Mewakili efek Alpha Floor. Nilai Alpha (opasitas) kurang dari 100% diubah menjadi nol. Dengan kata lain, apa pun yang sebagian transparan menjadi sepenuhnya transparan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEffective()](#getEffective--) | Mendapatkan data efek Alpha Floor yang efektif dengan pewarisan yang diterapkan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [AlphaFloor](../../com.aspose.slides/alphafloor) yang ditentukan sama dengan [AlphaFloor](../../com.aspose.slides/alphafloor) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Mendapatkan data efek Alpha Floor yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Sebuah [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah [AlphaFloor](../../com.aspose.slides/alphafloor) yang ditentukan sama dengan [AlphaFloor](../../com.aspose.slides/alphafloor) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) yang akan dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; selain itu, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.