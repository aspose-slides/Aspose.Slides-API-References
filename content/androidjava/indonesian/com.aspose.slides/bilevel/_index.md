---
title: BiLevel
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili efek hitam/putih Bi-Level.
type: docs
url: /id/com.aspose.slides/bilevel/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Mewakili efek Bi-Level (hitam/putih). Warna masukan yang luminansinya kurang dari nilai ambang yang ditentukan diubah menjadi hitam. Warna masukan yang luminansinya lebih besar atau sama dengan nilai yang ditentukan diatur menjadi putih. Nilai efek alfa tidak terpengaruh oleh efek ini.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEffective()](#getEffective--) | Mendapatkan data efek Bi-Level yang efektif dengan pewarisan yang diterapkan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [BiLevel](../../com.aspose.slides/bilevel) yang ditentukan sama dengan [BiLevel](../../com.aspose.slides/bilevel) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Mendapatkan data efek Bi-Level yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Sebuah [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [BiLevel](../../com.aspose.slides/bilevel) yang ditentukan sama dengan [BiLevel](../../com.aspose.slides/bilevel) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) yang akan dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; sebaliknya, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Kode hash untuk objek saat ini.