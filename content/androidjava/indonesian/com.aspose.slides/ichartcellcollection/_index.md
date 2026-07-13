---
title: IChartCellCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi sel dengan data.
type: docs
url: /id/com.aspose.slides/ichartcellcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Mewakili koleksi sel dengan data.
## Metode

| Method | Description |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Mengembalikan alamat kumpulan sel dalam buku kerja. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | String konkatenasi dari semua nilai string sel. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sebuah sel (IChartDataCell) berdasarkan indeks. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Menambahkan sel baru ke koleksi. |
| [add(Object value)](#add-java.lang.Object-) | Membuat [IChartDataCell](../../com.aspose.slides/ichartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sel dari koleksi berdasarkan indeks. |
| [getCount()](#getCount--) | Mendapatkan jumlah sel dalam koleksi. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

Mengembalikan alamat kumpulan sel dalam buku kerja.

**Mengembalikan:**
java.lang.String - Alamat kumpulan sel dalam buku kerja String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

String konkatenasi dari semua nilai string sel.

**Mengembalikan:**
java.lang.String - String hasil String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

Mengembalikan sebuah sel (IChartDataCell) berdasarkan indeks.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks dari sebuah sel. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Sel dengan data.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Menambahkan sel baru ke koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel baru yang akan ditambahkan. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Membuat [IChartDataCell](../../com.aspose.slides/ichartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Nilai.

--------------------

Metode ini menambahkan worksheet dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) untuk menambah atau mengedit nilai Cell, pastikan bahwa Anda tidak menggunakan worksheet ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus sel dari koleksi berdasarkan indeks.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks dari sel yang akan dihapus. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah sel dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int