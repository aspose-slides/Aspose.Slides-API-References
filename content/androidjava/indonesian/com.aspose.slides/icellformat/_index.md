---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili format sel tabel.
type: docs
url: /id/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Mewakili format sel tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek properti pengisian sel. |
| [getBorderLeft()](#getBorderLeft--) | Mengembalikan objek properti garis batas kiri. |
| [getBorderTop()](#getBorderTop--) | Mengembalikan objek properti garis batas atas. |
| [getBorderRight()](#getBorderRight--) | Mengembalikan objek properti garis batas kanan. |
| [getBorderBottom()](#getBorderBottom--) | Mengembalikan objek properti garis batas bawah. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Mengembalikan objek properti garis diagonal kiri-atas ke kanan-bawah. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Mengembalikan objek properti garis diagonal kiri-bawah ke kanan-atas. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi warna isian. |
| [setTransparency(float value)](#setTransparency-float-) | Mendapatkan atau mengatur transparansi warna isian. |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan sel tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Mengembalikan objek properti pengisian sel. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Mengembalikan objek properti garis batas kiri. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Mengembalikan objek properti garis batas atas. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Mengembalikan objek properti garis batas kanan. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Mengembalikan objek properti garis batas bawah. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Mengembalikan objek properti garis diagonal kiri-atas ke kanan-bawah. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Mengembalikan objek properti garis diagonal kiri-bawah ke kanan-atas. Hanya-baca [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Mendapatkan atau mengatur transparansi warna isian. Baca/tulis  float .

**Mengembalikan:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Mendapatkan atau mengatur transparansi warna isian. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan sel tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

**Mengembalikan:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).