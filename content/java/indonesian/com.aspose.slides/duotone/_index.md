---
title: Duotone
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili efek Duotone.
type: docs
url: /id/com.aspose.slides/duotone/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Mewakili efek Duotone. Untuk setiap piksel, menggabungkan Color1 dan Color2 melalui interpolasi linier untuk menentukan warna baru bagi piksel tersebut.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor1()](#getColor1--) | Mengembalikan format warna target untuk piksel gelap. |
| [getColor2()](#getColor2--) | Mengembalikan format warna target untuk piksel terang. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Duotone yang efektif dengan pewarisan diterapkan. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [Duotone](../../com.aspose.slides/duotone) yang ditentukan sama dengan [Duotone](../../com.aspose.slides/duotone) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

Mengembalikan format warna target untuk piksel gelap. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

Mengembalikan format warna target untuk piksel terang. Baca-saja [IColorFormat](../../com.aspose.slides/icolorformat).

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

Mendapatkan data efek Duotone yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [Duotone](../../com.aspose.slides/duotone) yang ditentukan sama dengan [Duotone](../../com.aspose.slides/duotone) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) yang akan dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; lainnya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.