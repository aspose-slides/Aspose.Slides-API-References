---
title: Table
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili sebuah tabel pada slide.
type: docs
url: /id/com.aspose.slides/table/
---
**Pewarisan:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**  
[com.aspose.slides.ITable](../../com.aspose.slides/itable)  
```
public final class Table extends GraphicalObject implements ITable
```

Mewakili sebuah tabel pada slide.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int columnIndex, int rowIndex)](#get-Item-int-int-) | Mengembalikan sel pada kolom dan baris yang ditentukan. |
| [getRows()](#getRows--) | Mengembalikan koleksi baris. |
| [getColumns()](#getColumns--) | Mengembalikan koleksi kolom. |
| [getTableFormat()](#getTableFormat--) | Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini. |
| [mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)](#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-) | Menggabungkan sel tetangga. |
| [getStylePreset()](#getStylePreset--) | Mendapatkan atau mengatur gaya tabel bawaan. |
| [setStylePreset(int value)](#setStylePreset-int-) | Mendapatkan atau mengatur gaya tabel bawaan. |
| [getRightToLeft()](#getRightToLeft--) | Menentukan apakah tabel memiliki urutan baca kanan ke kiri. |
| [setRightToLeft(boolean value)](#setRightToLeft-boolean-) | Menentukan apakah tabel memiliki urutan baca kanan ke kiri. |
| [getFirstRow()](#getFirstRow--) | Menentukan apakah baris pertama tabel harus digambar dengan format khusus. |
| [setFirstRow(boolean value)](#setFirstRow-boolean-) | Menentukan apakah baris pertama tabel harus digambar dengan format khusus. |
| [getFirstCol()](#getFirstCol--) | Menentukan apakah kolom pertama tabel harus digambar dengan format khusus. |
| [setFirstCol(boolean value)](#setFirstCol-boolean-) | Menentukan apakah kolom pertama tabel harus digambar dengan format khusus. |
| [getLastRow()](#getLastRow--) | Menentukan apakah baris terakhir tabel harus digambar dengan format khusus. |
| [setLastRow(boolean value)](#setLastRow-boolean-) | Menentukan apakah baris terakhir tabel harus digambar dengan format khusus. |
| [getLastCol()](#getLastCol--) | Menentukan apakah kolom terakhir tabel harus digambar dengan format khusus. |
| [setLastCol(boolean value)](#setLastCol-boolean-) | Menentukan apakah kolom terakhir tabel harus digambar dengan format khusus. |
| [getHorizontalBanding()](#getHorizontalBanding--) | Menentukan apakah baris genap harus digambar dengan format berbeda. |
| [setHorizontalBanding(boolean value)](#setHorizontalBanding-boolean-) | Menentukan apakah baris genap harus digambar dengan format berbeda. |
| [getVerticalBanding()](#getVerticalBanding--) | Menentukan apakah kolom genap harus digambar dengan format berbeda. |
| [setVerticalBanding(boolean value)](#setVerticalBanding-boolean-) | Menentukan apakah kolom genap harus digambar dengan format berbeda. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Menetapkan properti format bagian yang didefinisikan ke semua bagian sel tabel. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Menetapkan properti format paragraf yang didefinisikan ke semua paragraf sel tabel. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Menetapkan properti format bingkai teks yang didefinisikan ke semua bingkai teks sel tabel. |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek TableFormat.FillFormat yang berisi format isian untuk Tabel. |

### get_Item(int columnIndex, int rowIndex) {#get-Item-int-int-}
```
public final ICell get_Item(int columnIndex, int rowIndex)
```

Mengembalikan sel pada kolom dan baris yang ditentukan. Baca-saja [Cell](../../com.aspose.slides/cell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| columnIndex | int |  |
| rowIndex | int |  |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell)

### getRows() {#getRows--}
```
public final IRowCollection getRows()
```

Mengembalikan koleksi baris. Baca-saja [IRowCollection](../../com.aspose.slides/irowcollection).

**Mengembalikan:**
[IRowCollection](../../com.aspose.slides/irowcollection)

### getColumns() {#getColumns--}
```
public final IColumnCollection getColumns()
```

Mengembalikan koleksi kolom. Baca-saja [IColumnCollection](../../com.aspose.slides/icolumncollection).

**Mengembalikan:**
[IColumnCollection](../../com.aspose.slides/icolumncollection)

### getTableFormat() {#getTableFormat--}
```
public final ITableFormat getTableFormat()
```

Mengembalikan objek TableFormat yang berisi properti pemformatan untuk tabel ini. Baca-saja [ITableFormat](../../com.aspose.slides/itableformat).

**Mengembalikan:**
[ITableFormat](../../com.aspose.slides/itableformat)

### mergeCells(ICell cell1, ICell cell2, boolean allowSplitting) {#mergeCells-com.aspose.slides.ICell-com.aspose.slides.ICell-boolean-}
```
public final ICell mergeCells(ICell cell1, ICell cell2, boolean allowSplitting)
```

Menggabungkan sel tetangga.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell1 | [ICell](../../com.aspose.slides/icell) | Sel yang akan digabung. |
| cell2 | [ICell](../../com.aspose.slides/icell) | Sel yang akan digabung. |
| allowSplitting | boolean | True untuk mengizinkan pemisahan sel. |

**Mengembalikan:**
[ICell](../../com.aspose.slides/icell) - Sel yang digabung.

### getStylePreset() {#getStylePreset--}
```
public final int getStylePreset()
```

Mendapatkan atau mengatur gaya tabel bawaan. Baca/tulis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Mengembalikan:**
int

### setStylePreset(int value) {#setStylePreset-int-}
```
public final void setStylePreset(int value)
```

Mendapatkan atau mengatur gaya tabel bawaan. Baca/tulis [TableStylePreset](../../com.aspose.slides/tablestylepreset).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getRightToLeft() {#getRightToLeft--}
```
public final boolean getRightToLeft()
```

Menentukan apakah tabel memiliki urutan baca kanan ke kiri. Baca-tulis  boolean .

**Mengembalikan:**
boolean

### setRightToLeft(boolean value) {#setRightToLeft-boolean-}
```
public final void setRightToLeft(boolean value)
```

Menentukan apakah tabel memiliki urutan baca kanan ke kiri. Baca-tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getFirstRow() {#getFirstRow--}
```
public final boolean getFirstRow()
```

Menentukan apakah baris pertama tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setFirstRow(boolean value) {#setFirstRow-boolean-}
```
public final void setFirstRow(boolean value)
```

Menentukan apakah baris pertama tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getFirstCol() {#getFirstCol--}
```
public final boolean getFirstCol()
```

Menentukan apakah kolom pertama tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setFirstCol(boolean value) {#setFirstCol-boolean-}
```
public final void setFirstCol(boolean value)
```

Menentukan apakah kolom pertama tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLastRow() {#getLastRow--}
```
public final boolean getLastRow()
```

Menentukan apakah baris terakhir tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setLastRow(boolean value) {#setLastRow-boolean-}
```
public final void setLastRow(boolean value)
```

Menentukan apakah baris terakhir tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLastCol() {#getLastCol--}
```
public final boolean getLastCol()
```

Menentukan apakah kolom terakhir tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setLastCol(boolean value) {#setLastCol-boolean-}
```
public final void setLastCol(boolean value)
```

Menentukan apakah kolom terakhir tabel harus digambar dengan format khusus. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHorizontalBanding() {#getHorizontalBanding--}
```
public final boolean getHorizontalBanding()
```

Menentukan apakah baris genap harus digambar dengan format berbeda. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setHorizontalBanding(boolean value) {#setHorizontalBanding-boolean-}
```
public final void setHorizontalBanding(boolean value)
```

Menentukan apakah baris genap harus digambar dengan format berbeda. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBanding() {#getVerticalBanding--}
```
public final boolean getVerticalBanding()
```

Menentukan apakah kolom genap harus digambar dengan format berbeda. Baca/tulis  boolean .

**Mengembalikan:**
boolean

### setVerticalBanding(boolean value) {#setVerticalBanding-boolean-}
```
public final void setVerticalBanding(boolean value)
```

Menentukan apakah kolom genap harus digambar dengan format berbeda. Baca/tulis  boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Menetapkan properti format bagian yang didefinisikan ke semua bagian sel tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objek IPortionFormat dengan properti yang diperlukan sudah diatur. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Menetapkan properti format paragraf yang didefinisikan ke semua paragraf sel tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objek IParagraphFormat dengan properti yang diperlukan sudah diatur. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Menetapkan properti format bingkai teks yang didefinisikan ke semua bingkai teks sel tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objek ITextFrameFormat dengan properti yang diperlukan sudah diatur. |

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

Mengembalikan objek TableFormat.FillFormat yang berisi format isian untuk Tabel. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)