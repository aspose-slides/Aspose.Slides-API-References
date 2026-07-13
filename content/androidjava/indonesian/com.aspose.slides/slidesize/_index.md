---
title: SlideSize
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili ukuran dan orientasi slide.
type: docs
url: /id/com.aspose.slides/slidesize/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Mewakili ukuran dan orientasi slide.
## Metode

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Mengambil dimensi slide dalam satuan point. |
| [getType()](#getType--) | Mengambil tipe ukuran slide. |
| [getOrientation()](#getOrientation--) | Mengambil atau mengatur orientasi slide. |
| [setOrientation(int value)](#setOrientation-int-) | Mengambil atau mengatur orientasi slide. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Mengatur ukuran slide berdasarkan tipe dan menskala konten yang ada. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Mengatur dimensi slide secara eksplisit dan menskala konten yang ada. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Mengambil dimensi slide dalam satuan point.

--------------------

Menetapkan nilai baru mengatur ulang properti \#getType.getType menjadi [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Mengembalikan:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Mengambil tipe ukuran slide.

--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) menyesuaikan \#getSize.getSize menurut dimensi yang telah ditentukan, sambil mempertahankan \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Mengembalikan:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Mengambil atau mengatur orientasi slide.

--------------------

Mengubah nilai ini menukar lebar dan tinggi slide.

**Mengembalikan:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Mengambil atau mengatur orientasi slide.

--------------------

Mengubah nilai ini menukar lebar dan tinggi slide.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Mengatur ukuran slide berdasarkan tipe dan menskala konten yang ada.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Tipe ukuran slide yang telah ditentukan untuk diterapkan. |
| scaleType | int | Mode penskalaan konten yang akan digunakan.

--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) menyesuaikan \#getSize.getSize berdasarkan tipe yang dipilih, sambil mempertahankan \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Mengatur dimensi slide secara eksplisit dan menskala konten yang ada.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Lebar slide baru, dalam satuan point. |
| height | float | Tinggi slide baru, dalam satuan point. |
| scaleType | int | Mode penskalaan konten yang akan digunakan.

--------------------

Ini mengatur ulang properti \#getType.getType menjadi [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |