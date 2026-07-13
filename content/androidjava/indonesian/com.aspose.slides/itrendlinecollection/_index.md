---
title: ITrendlineCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi TrendlineEx
type: docs
url: /id/com.aspose.slides/itrendlinecollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ITrendlineCollection extends System.Collections.Generic.IGenericEnumerable<ITrendline>
```

Mewakili koleksi TrendlineEx
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getCount()](#getCount--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [add(int trendlineType)](#add-int-) | Menambahkan Trendline baru di akhir koleksi dan mengembalikannya. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Menghapus nilai yang ditentukan. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITrendline get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [ITrendline](../../com.aspose.slides/itrendline).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ITrendline](../../com.aspose.slides/itrendline)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### add(int trendlineType) {#add-int-}
```
public abstract ITrendline add(int trendlineType)
```


Menambahkan Trendline baru di akhir koleksi dan mengembalikannya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| trendlineType | int | jenis Trendline [TrendlineType](../../com.aspose.slides/trendlinetype) |

**Mengembalikan:**
[ITrendline](../../com.aspose.slides/itrendline) - Trendline Baru [ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public abstract void remove(ITrendline value)
```


Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) | Trendline yang akan dihapus [ITrendline](../../com.aspose.slides/itrendline) |