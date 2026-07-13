---
title: ChartCellCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi sel dengan data.
type: docs
url: /id/com.aspose.slides/chartcellcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

Mewakili koleksi sel dengan data.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Mengembalikan alamat dari sekumpulan sel dalam workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | String penggabungan dari semua nilai string sel. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sel (IChartDataCell) berdasarkan indeks. |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | Menambahkan sel baru ke koleksi. |
| [add(Object value)](#add-java.lang.Object-) | Membuat [ChartDataCell](../../com.aspose.slides/chartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sel dari koleksi berdasarkan indeks. |
| [getCount()](#getCount--) | Mendapatkan jumlah sel dalam koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

Mengembalikan alamat dari sekumpulan sel dalam workbook.

**Mengembalikan:**
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

String penggabungan dari semua nilai string sel.

**Mengembalikan:**
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

Mengembalikan sel (IChartDataCell) berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks sebuah sel. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Sel dengan data.
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

Menambahkan sel baru ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel baru untuk ditambahkan. |

### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

Membuat [ChartDataCell](../../com.aspose.slides/chartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object | Nilainya.

--------------------

Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) untuk menambah atau mengedit nilai Sel, pastikan bahwa Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus sel dari koleksi berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks sebuah sel untuk dihapus. |
### getCount() {#getCount--}
```
public final int getCount()
```

Mendapatkan jumlah sel dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - An java.util.Iterator for the entire collection.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject