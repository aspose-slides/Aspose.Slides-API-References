---
title: AlphaBiLevel
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek Alpha Bi-Level.
type: docs
url: /id/com.aspose.slides/alphabilevel/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Mewakili efek Alpha Bi-Level. Nilai Alpha (Opacity) yang kurang dari ambang batas diubah menjadi 0 (sepenuhnya transparan) dan nilai alpha yang lebih besar atau sama dengan ambang batas diubah menjadi 100% (sepenuhnya opak).
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getThreshold()](#getThreshold--) | Mengembalikan ambang batas efek. |
| [setThreshold(float value)](#setThreshold-float-) | Mengembalikan ambang batas efek. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Alpha Bi-Level yang efektif dengan pewarisan diterapkan. |
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


Mendapatkan data efek Alpha Bi-Level yang efektif dengan pewarisan diterapkan.

**Mengembalikan:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah [AlphaBiLevel](../../com.aspose.slides/alphabilevel) yang ditentukan sama dengan [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaBiLevel](../../com.aspose.slides/alphabilevel) untuk dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; sebaliknya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.