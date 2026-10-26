---
title: SlideSize
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili ukuran dan orientasi slide.
type: docs
url: /id/com.aspose.slides/slidesize/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Mewakili ukuran dan orientasi slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSize()](#getSize--) | Mendapatkan dimensi slide dalam poin. |
| [getType()](#getType--) | Mendapatkan tipe ukuran slide. |
| [getOrientation()](#getOrientation--) | Mendapatkan atau mengatur orientasi slide. |
| [setOrientation(int value)](#setOrientation-int-) | Mendapatkan atau mengatur orientasi slide. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Mengatur dimensi slide secara eksplisit dan menskalakan konten yang ada. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Mendapatkan dimensi slide dalam poin.

--------------------

Menetapkan nilai baru akan mengatur ulang properti #getType.getType menjadi [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Mengembalikan:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

Mendapatkan tipe ukuran slide.

--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) akan menyesuaikan #getSize.getSize sesuai dengan dimensi yang telah ditentukan, sambil mempertahankan #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) yang saat ini.

**Mengembalikan:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Mendapatkan atau mengatur orientasi slide.

--------------------

Mengubah nilai ini akan menukar lebar dan tinggi slide.

**Mengembalikan:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Mendapatkan atau mengatur orientasi slide.

--------------------

Mengubah nilai ini akan menukar lebar dan tinggi slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Ukuran slide yang telah ditentukan untuk diterapkan. |
| scaleType | int | Mode penskalaan konten yang akan digunakan. |
--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) akan menyesuaikan #getSize.getSize berdasarkan tipe yang dipilih, sambil mempertahankan #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Mengatur dimensi slide secara eksplisit dan menskalakan konten yang ada.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | float | Lebar slide baru, dalam poin. |
| height | float | Tinggi slide baru, dalam poin. |
| scaleType | int | Mode penskalaan konten yang akan digunakan. |
--------------------

Ini mengatur ulang properti #getType.getType menjadi [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).