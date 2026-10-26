---
title: ChartSeriesCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi dari
type: docs
url: /id/com.aspose.slides/chartseriescollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

Mewakili koleksi dari [ChartSeries](../../com.aspose.slides/chartseries)
## Metode

| Method | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [size()](#size--) | Mengembalikan jumlah objek dalam koleksi. |
| [add(int type)](#add-int-) | Membuat seri diagram baru dan menambahkannya ke koleksi. |
| [insert(int index, int type)](#insert-int-int-) | Membuat seri diagram baru dan menyisipkannya ke dalam koleksi. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Membuat seri diagram baru dari [ChartDataCell](../../com.aspose.slides/chartdatacell) dan menambahkannya ke koleksi. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Membuat seri diagram baru dari [ChartCellCollection](../../com.aspose.slides/chartcellcollection) dan menambahkannya ke koleksi. |
| [add(String name, int type)](#add-java.lang.String-int-) | Membuat seri diagram baru dari nilai dan menambahkannya ke koleksi. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Mencari [ChartSeries](../../com.aspose.slides/chartseries) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Koleksi. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus kontrol ActiveX yang disimpan pada posisi tertentu dari koleksi. |
| [clear()](#clear--) | Menghapus semua kontrol dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin seluruh koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan root sinkronisasi. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Elemen pada indeks yang ditentukan.
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah objek dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

Membuat seri diagram baru dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe seri |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri diagram baru.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

Membuat seri diagram baru dan menyisipkannya ke dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Membuat seri diagram baru dari [ChartDataCell](../../com.aspose.slides/chartdatacell) dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel yang berisi nama seri. |
| type | int | Tipe menetapkan tipe seri

--------------------

Jika seri diagram dibuat dari sel yang sama sudah ada dalam koleksi maka metode tidak menambahkan apa pun dan mengembalikan indeksnya. |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri diagram yang ditambahkan atau seri yang sudah ada dalam koleksi.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Membuat seri diagram baru dari [ChartCellCollection](../../com.aspose.slides/chartcellcollection) dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Sel-sel yang berisi nama seri. |
| type | int | Tipe menetapkan tipe seri

--------------------

Jika seri diagram dibuat dari sel yang sama sudah ada dalam koleksi maka metode tidak menambahkan apa pun dan mengembalikan indeksnya. |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri diagram yang ditambahkan atau seri yang sudah ada dalam koleksi.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

Membuat seri diagram baru dari nilai dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama seri. |
| type | int | Tipe menetapkan tipe seri |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri diagram yang ditambahkan.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

Mencari [ChartSeries](../../com.aspose.slides/chartseries) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Nilai seri diagram. |

**Mengembalikan:**
int - Indeks berbasis nol dari kemunculan pertama nilai dalam seluruh CollectionBase, jika ditemukan; jika tidak, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Nilainya. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus kontrol ActiveX yang disimpan pada posisi tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kontrol yang akan dihapus. |
### clear() {#clear--}
```
public final void clear()
```

Menghapus semua kontrol dari koleksi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin seluruh koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target |
| index | int | Indeks dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan root sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object