---
title: Blur
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili efek Blur yang diterapkan pada seluruh bentuk termasuk isinya.
type: docs
url: /id/com.aspose.slides/blur/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Mewakili efek Blur yang diterapkan pada seluruh bentuk, termasuk isinya. Semua saluran warna, termasuk alfa, terpengaruh.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRadius()](#getRadius--) | Mengembalikan atau mengatur radius blur. |
| [setRadius(double value)](#setRadius-double-) | Mengembalikan atau mengatur radius blur. |
| [getGrow()](#getGrow--) | Menentukan apakah batas objek harus diperluas sebagai akibat dari pemburaman. |
| [setGrow(boolean value)](#setGrow-boolean-) | Menentukan apakah batas objek harus diperluas sebagai akibat dari pemburaman. |
| [getEffective()](#getEffective--) | Mendapatkan data efek Blur yang efektif dengan pewarisan yang diterapkan. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah [Blur](../../com.aspose.slides/blur) yang ditentukan sama dengan [Blur](../../com.aspose.slides/blur) saat ini. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Mengembalikan atau mengatur radius blur. Baca/tulis double.

**Mengembalikan:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Mengembalikan atau mengatur radius blur. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Menentukan apakah batas objek harus diperluas sebagai akibat dari pemburaman. True menunjukkan batas diperluas sementara false menunjukkan tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Menentukan apakah batas objek harus diperluas sebagai akibat dari pemburaman. True menunjukkan batas diperluas sementara false menunjukkan tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Mendapatkan data efek Blur yang efektif dengan pewarisan yang diterapkan.

**Mengembalikan:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Sebuah [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah [Blur](../../com.aspose.slides/blur) yang ditentukan sama dengan [Blur](../../com.aspose.slides/blur) saat ini.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) yang akan dibandingkan. |

**Mengembalikan:**
boolean - true jika objek sama; lainnya, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu.

**Mengembalikan:**
int - Sebuah kode hash untuk objek saat ini.