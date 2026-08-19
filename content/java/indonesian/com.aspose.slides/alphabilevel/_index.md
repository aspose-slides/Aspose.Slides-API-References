---
title: AlphaBiLevel
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili efek Alpha Bi-Level.
type: docs
url: /id/com.aspose.slides/alphabilevel/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Mewakili efek Alpha Bi-Level. Nilai Alpha (Opacity) yang lebih kecil dari ambang batas diubah menjadi 0 (sepenuhnya transparan) dan nilai alpha yang lebih besar atau sama dengan ambang batas diubah menjadi 100% (sepenuhnya opak).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getThreshold()](#getThreshold--) | Mengembalikan ambang batas efek. |
| [setThreshold(float value)](#setThreshold-float-) | Mengembalikan ambang batas efek. |
| [getEffective()](#getEffective--) | Mengambil data efek Alpha Bi-Level yang efektif dengan pewarisan yang diterapkan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [AlphaBiLevel](../../com.aspose.slides/alphabilevel) yang ditentukan sama dengan [AlphaBiLevel](../../com.aspose.slides/alphabilevel) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Mengembalikan ambang batas efek. Baca/tulis float.

**Mengembalikan:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Mengembalikan ambang batas efek. Baca/tulis float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Mengambil data efek Alpha Bi-Level yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [AlphaBiLevel](../../com.aspose.slides/alphabilevel) yang ditentukan sama dengan [AlphaBiLevel](../../com.aspose.slides/alphabilevel) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; jika tidak, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.