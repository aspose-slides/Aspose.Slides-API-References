---
title: ITable
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili tabel pada slide.
type: docs
url: /id/com.aspose.slides/itable/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface ITable extends IGraphicalObject, IBulkTextFormattable
```

Mewakili tabel pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Mengembalikan cell pada indeks kolom dan baris yang ditentukan. |
| [getRows()](#getRows--) | Mengembalikan koleksi baris. |
| [getColumns()](#getColumns--) | Mengembalikan koleksi kolom. |
| [getTableFormat()](#getTableFormat--) | Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini. |
| [getStylePreset()](#getStylePreset--) | Mendapatkan atau mengatur gaya tabel bawaan. |
| [setStylePreset(int value)](#setStylePreset-int-) | Mendapatkan atau mengatur gaya tabel bawaan. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah tabel memiliki urutan baca kanan ke kiri. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Menentukan apakah tabel memiliki urutan baca kanan ke kiri. |
| [getFirstRow()](#getFirstRow--) | Menentukan apakah baris pertama tabel harus digambar dengan pemformatan khusus. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Menentukan apakah baris pertama tabel harus digambar dengan pemformatan khusus. |
| [getFirstCol()](#getFirstCol--) | Menentukan apakah kolom pertama tabel harus digambar dengan pemformatan khusus. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Menentukan apakah kolom pertama tabel harus digambar dengan pemformatan khusus. |
| [getLastRow()](#getLastRow--) | Menentukan apakah baris terakhir tabel harus digambar dengan pemformatan khusus. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Menentukan apakah baris terakhir tabel harus digambar dengan pemformatan khusus. |
| [getLastCol()](#getLastCol--) | Menentukan apakah kolom terakhir tabel harus digambar dengan pemformatan khusus. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Menentukan apakah kolom terakhir tabel harus digambar dengan pemformatan khusus. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Menentukan apakah baris genap harus digambar dengan pemformatan yang berbeda. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Menentukan apakah baris genap harus digambar dengan pemformatan yang berbeda. |
| [getVerticalBanding()](#getVerticalBanding--) | Menentukan apakah kolom genap harus digambar dengan pemformatan yang berbeda. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Menentukan apakah kolom genap harus digambar dengan pemformatan yang berbeda. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Menggabungkan sel tetangga. |
### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public abstract ICell get_Item(int columnIndex, int rowIndex)
```

Mengembalikan cell pada indeks kolom dan baris yang ditentukan. Hanya-baca [ICell](../../com.aspose.slides/icell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell)
### getRows() {#getRows--}
```
public abstract IRowCollection getRows()
```

Mengembalikan koleksi baris. Hanya-baca [IRowCollection](../../com.aspose.slides/irowcollection).

**Mengembalikan:**
[IRowCollection](../../com.aspose.slides/irowcollection)
### getColumns() {#getColumns--}
```
public abstract IColumnCollection getColumns()
```

Mengembalikan koleksi kolom. Hanya-baca [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Mengembalikan:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)
### getTableFormat() {#getTableFormat--}
```
public abstract ITableFormat getTableFormat()
```

Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini. Hanya-baca [ITableFormat](../../com.aspose.slides/itableformat).

**Mengembalikan:**
[ITableFormat](../../com.aspose.slides/itableformat)
### getStylePreset() {#getStylePreset--}
```
public abstract int getStylePreset()
```

Mendapatkan atau mengatur gaya tabel bawaan. Baca/tulis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Mengembalikan:**
int
### setStylePreset(int value) {#setStylePreset-int-}
```
public abstract void setStylePreset(int value)
```

Mendapatkan atau mengatur gaya tabel bawaan. Baca/tulis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

Menentukan apakah tabel memiliki urutan baca kanan ke kiri. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public abstract void setRightToLeft(boolean value)
```

Menentukan apakah tabel memiliki urutan baca kanan ke kiri. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public abstract boolean getFirstRow()
```

Menentukan apakah baris pertama tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public abstract void setFirstRow(boolean value)
```

Menentukan apakah baris pertama tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public abstract boolean getFirstCol()
```

Menentukan apakah kolom pertama tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public abstract void setFirstCol(boolean value)
```

Menentukan apakah kolom pertama tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public abstract boolean getLastRow()
```

Menentukan apakah baris terakhir tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLastRow(boolean value) {#setLastRow-boolean-}
```
public abstract void setLastRow(boolean value)
```

Menentukan apakah baris terakhir tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public abstract boolean getLastCol()
```

Menentukan apakah kolom terakhir tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLastCol(boolean value) {#setLastCol-boolean-}
```
public abstract void setLastCol(boolean value)
```

Menentukan apakah kolom terakhir tabel harus digambar dengan pemformatan khusus. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public abstract boolean getHorizontalBanding()
```

Menentukan apakah baris genap harus digambar dengan pemformatan yang berbeda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public abstract void setHorizontalBanding(boolean value)
```

Menentukan apakah baris genap harus digambar dengan pemformatan yang berbeda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public abstract boolean getVerticalBanding()
```

Menentukan apakah kolom genap harus digambar dengan pemformatan yang berbeda. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public abstract void setVerticalBanding(boolean value)
```

Menentukan apakah kolom genap harus digambar dengan pemformatan yang berbeda. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public abstract ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Menggabungkan sel tetangga.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Cell to merge. |
| allowSplitting | boolean | True to allow cells splitting. |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell) - Merged cell.