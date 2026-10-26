---
title: IColumn
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili kolom dalam tabel.
type: docs
url: /id/com.aspose.slides/icolumn/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Mewakili kolom dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mengembalikan atau mengatur lebar kolom. |
| [setWidth(double value)](#setWidth-double-) | Mengembalikan atau mengatur lebar kolom. |
| [getColumnFormat()](#getColumnFormat--) | Mengembalikan objek ColumnFormat yang berisi properti pemformatan untuk kolom ini. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Mengembalikan atau mengatur lebar kolom. Baca/tulis double.

**Mengembalikan:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Mengembalikan atau mengatur lebar kolom. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Mengembalikan objek ColumnFormat yang berisi properti pemformatan untuk kolom ini. Baca-saja [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Mengembalikan:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)