---
title: IMotionPath
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili jalur gerakan.
type: docs
url: /id/com.aspose.slides/imotionpath/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Mewakili jalur gerakan.
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
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Menambahkan perintah baru ke jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe perintah untuk perilaku efek gerakan animasi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array titik android.graphics.PointF[] |
| ptsType | int | Tipe titik dalam jalur gerakan animasi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Menunjukkan apakah akan menggunakan koordinat relatif atau tidak boolean |

**Mengembalikan:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Perintah dari jalur [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mengembalikan jumlah jalur dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Menyisipkan perintah baru ke jalur

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks untuk penyisipan perintah int |
| type | int | Tipe perintah untuk perilaku efek gerakan animasi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Array titik android.graphics.PointF[] |
| ptsType | int | Tipe titik dalam jalur gerakan animasi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Menunjukkan apakah akan menggunakan koordinat relatif atau tidak boolean |
### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua perintah dari koleksi.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Menghapus perintah yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Jalur gerakan untuk dihapus [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus perintah pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks untuk menghapus perintah int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Mengembalikan perintah pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Perintah pada indeks yang ditentukan [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)