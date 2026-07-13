---
title: MotionPath
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili jalur gerakan.
type: docs
url: /id/com.aspose.slides/motionpath/
---
**Warisan:**
java.lang.Object

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Mewakili jalur gerakan.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Menambahkan perintah baru ke jalur |
| [getCount()](#getCount--) | Mengembalikan jumlah jalur dalam koleksi. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Menyisipkan perintah baru ke jalur |
| [clear()](#clear--) | Menghapus semua perintah dari koleksi. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Menghapus perintah yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus perintah pada indeks yang ditentukan. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan perintah pada indeks yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Menambahkan perintah baru ke jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array titik |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean koordinat relatif |

**Mengembalikan:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```

Mengembalikan jumlah jalur dalam koleksi. Int baca-saja.

**Mengembalikan:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

Menyisipkan perintah baru ke jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis-nol tempat item harus disisipkan. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array titik |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean koordinat relatif |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua perintah dari koleksi.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

Menghapus perintah yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Jalur gerakan yang akan dihapus. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus perintah pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks perintah yang harus dihapus. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

Mengembalikan perintah pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - java.util.Iterator untuk seluruh koleksi.