---
title: IBlur
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili efek Blur yang diterapkan pada seluruh bentuk termasuk isinya.
type: docs
url: /id/com.aspose.slides/iblur/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Mewakili efek Blur yang diterapkan pada seluruh bentuk, termasuk isi-nya. Semua saluran warna, termasuk alpha, terpengaruh.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getRadius()](#getRadius--) | Mengembalikan atau mengatur radius blur. |
| [setRadius(double value)](#setRadius-double-) | Mengembalikan atau mengatur radius blur. |
| [getGrow()](#getGrow--) | Menentukan apakah batas objek harus diperluas sebagai hasil dari blur. |
| [setGrow(boolean value)](#setGrow-boolean-) | Menentukan apakah batas objek harus diperluas sebagai hasil dari blur. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Mengembalikan atau mengatur radius blur. Baca/tulis double.

**Mengembalikan:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Mengembalikan atau mengatur radius blur. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Menentukan apakah batas objek harus diperluas sebagai hasil dari blur. True menandakan batas diperluas sementara false menandakan tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```


Menentukan apakah batas objek harus diperluas sebagai hasil dari blur. True menandakan batas diperluas sementara false menandakan tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |