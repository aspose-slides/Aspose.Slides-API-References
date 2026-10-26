---
title: HSL
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek Hue/Saturation/Luminance.
type: docs
url: /id/com.aspose.slides/hsl/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

Semua Antarmuka yang Diimplementasikan:
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Mewakili efek Hue/Saturation/Luminance. hue, saturasi, dan luminansi masing-masing dapat disesuaikan relatif terhadap nilai saat ini.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEffective()](#getEffective--) | Mendapatkan data efek Hue/Saturation/Luminance yang efektif dengan pewarisan yang diterapkan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [HSL](../../com.aspose.slides/hsl) yang ditentukan sama dengan [HSL](../../com.aspose.slides/hsl) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Mendapatkan data efek Hue/Saturation/Luminance yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Sebuah [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [HSL](../../com.aspose.slides/hsl) yang ditentukan sama dengan [HSL](../../com.aspose.slides/hsl) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [HSL](../../com.aspose.slides/hsl) yang akan dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; sebaliknya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.