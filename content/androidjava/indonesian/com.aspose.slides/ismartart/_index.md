---
title: ISmartArt
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili diagram SmartArt.
type: docs
url: /id/com.aspose.slides/ismartart/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Mewakili diagram SmartArt.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Mengembalikan koleksi semua node dalam objek SmartArt. |
| [getNodes()](#getNodes--) | Mengembalikan koleksi node akar dalam objek SmartArt. |
| [getLayout()](#getLayout--) | Mengembalikan atau mengatur tata letak objek SmartArt. |
| [setLayout(int value)](#setLayout-int-) | Mengembalikan atau mengatur tata letak objek SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | Mengembalikan atau mengatur gaya cepat objek SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Mengembalikan atau mengatur gaya cepat objek SmartArt. |
| [getColorStyle()](#getColorStyle--) | Mengembalikan atau mengatur gaya warna objek SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | Mengembalikan atau mengatur gaya warna objek SmartArt. |
| [isReversed()](#isReversed--) | Mengembalikan atau mengatur keadaan diagram SmartArt terkait (kiri-ke-kanan) LTR atau (kanan-ke-kiri) RTL, bila diagram mendukung pembalikan. |
| [setReversed(boolean value)](#setReversed-boolean-) | Mengembalikan atau mengatur keadaan diagram SmartArt terkait (kiri-ke-kanan) LTR atau (kanan-ke-kiri) RTL, bila diagram mendukung pembalikan. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


Mengembalikan koleksi semua node dalam objek SmartArt. Baca-saja [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Mengembalikan:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


Mengembalikan koleksi node akar dalam objek SmartArt. Baca-saja [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Mengembalikan:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Mengembalikan atau mengatur tata letak objek SmartArt. Baca/tulis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Mengembalikan:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


Mengembalikan atau mengatur tata letak objek SmartArt. Baca/tulis [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


Mengembalikan atau mengatur gaya cepat objek SmartArt. Baca/tulis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Mengembalikan:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


Mengembalikan atau mengatur gaya cepat objek SmartArt. Baca/tulis [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


Mengembalikan atau mengatur gaya warna objek SmartArt. Baca/tulis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Mengembalikan:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


Mengembalikan atau mengatur gaya warna objek SmartArt. Baca/tulis [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


Mengembalikan atau mengatur keadaan diagram SmartArt terkait (kiri-ke-kanan) LTR atau (kanan-ke-kiri) RTL, bila diagram mendukung pembalikan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


Mengembalikan atau mengatur keadaan diagram SmartArt terkait (kiri-ke-kanan) LTR atau (kanan-ke-kiri) RTL, bila diagram mendukung pembalikan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |