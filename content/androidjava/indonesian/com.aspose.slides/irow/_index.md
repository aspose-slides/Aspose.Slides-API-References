---
title: IRow
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah baris dalam tabel.
type: docs
url: /id/com.aspose.slides/irow/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Mewakili sebuah baris dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeight()](#getHeight--) | Mengembalikan tinggi sebuah baris. |
| [getMinimalHeight()](#getMinimalHeight--) | Mengembalikan atau mengatur tinggi minimal yang mungkin dari sebuah baris. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Mengembalikan atau mengatur tinggi minimal yang mungkin dari sebuah baris. |
| [getRowFormat()](#getRowFormat--) | Mengembalikan objek RowFormat yang berisi properti pemformatan untuk baris ini. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Mengembalikan tinggi baris. Baca-saja double.

**Mengembalikan:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Mengembalikan atau mengatur tinggi minimal yang mungkin dari sebuah baris. Baca/tulis double.

**Mengembalikan:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Mengembalikan atau mengatur tinggi minimal yang mungkin dari sebuah baris. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Mengembalikan objek RowFormat yang berisi properti pemformatan untuk baris ini. Baca-saja [IRowFormat](../../com.aspose.slides/irowformat).

**Mengembalikan:**
[IRowFormat](../../com.aspose.slides/irowformat)