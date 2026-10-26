---
title: IChartCellCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi sel dengan data.
type: docs
url: /id/com.aspose.slides/ichartcellcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

Mewakili koleksi sel dengan data.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | Mengembalikan alamat kumpulan sel dalam buku kerja. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | String konkatenasi dari semua nilai string sel. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sebuah sel (IChartDataCell) berdasarkan indeks. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Menambahkan sel baru ke koleksi. |
| [add(Object value)](#add-java.lang.Object-) | Membuat [IChartDataCell](../../com.aspose.slides/ichartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sebuah sel dari koleksi berdasarkan indeks. |
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks sel. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Sel dengan data.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

Menambahkan sel baru ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel baru yang ditambahkan. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

Membuat [IChartDataCell](../../com.aspose.slides/ichartdatacell) dari nilai yang ditentukan dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object | Nilainya. |

Metode ini menambahkan lembar kerja dengan nama AUTO\_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) untuk menambah atau menyunting nilai Sel, pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus sebuah sel dari koleksi berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks sel yang akan dihapus. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Mendapatkan jumlah sel dalam koleksi. Baca-saja int.

**Mengembalikan:**
int