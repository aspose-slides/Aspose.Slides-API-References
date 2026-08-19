---
title: IRow
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili baris dalam tabel.
type: docs
url: /id/com.aspose.slides/irow/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Mewakili baris dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeight()](#getHeight--) | Mengembalikan tinggi baris. |
| [getMinimalHeight()](#getMinimalHeight--) | Mengembalikan atau mengatur tinggi minimal yang mungkin dari baris. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Mengembalikan atau mengatur tinggi minimal yang mungkin dari baris. |
| [getRowFormat()](#getRowFormat--) | Mengembalikan objek RowFormat yang berisi properti pemformatan untuk baris ini. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Mengembalikan tinggi baris. Hanya baca double.

**Mengembalikan:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```


Mengembalikan atau mengatur tinggi minimal yang mungkin dari baris. Baca/tulis double.

**Mengembalikan:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```


Mengembalikan atau mengatur tinggi minimal yang mungkin dari baris. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```


Mengembalikan objek RowFormat yang berisi properti pemformatan untuk baris ini. Hanya baca [IRowFormat](../../com.aspose.slides/irowformat).

**Mengembalikan:**
[IRowFormat](../../com.aspose.slides/irowformat)