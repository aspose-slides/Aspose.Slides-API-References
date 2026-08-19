---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Mewakili ukuran dan orientasi slide.
type: docs
url: /id/com.aspose.slides/islidesize/
---```
public interface ISlideSize
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
public abstract Dimension2D getSize()
```

Mendapatkan dimensi slide dalam poin.

--------------------

Menetapkan nilai baru mengatur kembali properti \#getType.getType ke [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Mengembalikan:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

Mendapatkan tipe ukuran slide.

--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) menyesuaikan \#getSize.getSize menurut dimensi yang telah ditentukan, sambil mempertahankan \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) saat ini.

**Mengembalikan:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Mendapatkan atau mengatur orientasi slide.

--------------------

Mengubah nilai ini menukar lebar dan tinggi slide.

**Mengembalikan:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Mendapatkan atau mengatur orientasi slide.

--------------------

Mengubah nilai ini menukar lebar dan tinggi slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Ukuran slide yang telah ditentukan untuk diterapkan. |
| scaleType | int | Mode penskalaan konten yang digunakan. |

--------------------

Menetapkan nilai apa pun selain [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) menyesuaikan \#getSize.getSize berdasarkan tipe yang dipilih, sambil mempertahankan \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Mengatur dimensi slide secara eksplisit dan menskalakan konten yang ada.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | float | Lebar slide baru, dalam poin. |
| height | float | Tinggi slide baru, dalam poin. |
| scaleType | int | Mode penskalaan konten yang digunakan. |

--------------------

Ini mengatur kembali properti \#getType.getType ke [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dan mengatur {\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |