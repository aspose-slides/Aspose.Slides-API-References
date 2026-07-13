---
title: IChartSeriesCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi
type: docs
url: /id/com.aspose.slides/ichartseriescollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Mewakili koleksi [IChartSeries](../../com.aspose.slides/ichartseries)
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [add(int type)](#add-int-) | Membuat seri chart baru dan menambahkannya ke koleksi. |
| [insert(int index, int type)](#insert-int-int-) | Membuat seri chart baru dan menyisipkannya ke koleksi. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Membuat seri chart baru dari [IChartDataCell](../../com.aspose.slides/ichartdatacell) dan menambahkannya ke koleksi. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Membuat seri chart baru dari [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) dan menambahkannya ke koleksi. |
| [add(String name, int type)](#add-java.lang.String-int-) | Membuat seri chart baru dari nilai dan menambahkannya ke koleksi. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Mencari [IChartSeries](../../com.aspose.slides/ichartseries) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Koleksi |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan |
| [clear()](#clear--) | Menghapus semua elemen (termasuk gaya chart) dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Elemen pada indeks yang ditentukan.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Membuat seri chart baru dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | int | Tipe seri |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri chart baru.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Membuat seri chart baru dan menyisipkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks untuk penyisipan |
| type | int | Tipe chart [ChartType](../../com.aspose.slides/charttype) |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri chart baru [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Membuat seri chart baru dari [IChartDataCell](../../com.aspose.slides/ichartdatacell) dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel yang berisi nama seri. |
| type | int | Tipe yang menetapkan tipe seri

--------------------

Jika seri chart dibuat dari sel yang sama sudah ada dalam koleksi maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya. |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri chart yang ditambahkan atau seri yang sudah ada dalam koleksi.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Membuat seri chart baru dari [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Sel yang berisi nama seri. |
| type | int | Tipe yang menetapkan tipe seri

--------------------

Jika seri chart dibuat dari sel yang sama sudah ada dalam koleksi maka metode tidak menambahkan apa-apa dan mengembalikan indeksnya. |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri chart yang ditambahkan atau seri yang sudah ada dalam koleksi.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Membuat seri chart baru dari nilai dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama seri. |
| type | int | Tipe yang menetapkan tipe seri |

**Mengembalikan:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Seri chart yang ditambahkan.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Mencari [IChartSeries](../../com.aspose.slides/ichartseries) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Koleksi

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Nilai seri chart. |

**Mengembalikan:**
int - Indeks berbasis nol dari kemunculan pertama nilai dalam seluruh CollectionBase, jika ditemukan; jika tidak, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Nilainya. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks |
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen (termasuk gaya chart) dari koleksi.