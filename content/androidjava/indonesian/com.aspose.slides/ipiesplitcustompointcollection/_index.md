---
title: IPieSplitCustomPointCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili kumpulan titik yang akan digambar pada pai atau batang kedua pada bagan bar-of-pie atau pie-of-pie dengan pemisahan khusus.
type: docs
url: /id/com.aspose.slides/ipiesplitcustompointcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Mewakili kumpulan titik yang akan digambar pada pai atau batang kedua pada bagan bar-of-pie atau pie-of-pie dengan pemisahan khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan titik data bagan berdasarkan indeks. |
| [add(int dataPointIndex)](#add-int-) | Menambahkan titik data berdasarkan indeksnya dalam koleksi titik seri induk. |
| [remove(int dataPointIndex)](#remove-int-) | Menghapus item dari koleksi berdasarkan indeksnya dalam koleksi titik seri induk. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Mengembalikan titik data bagan berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks dari titik data. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data bagan.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Menambahkan titik data berdasarkan indeksnya dalam koleksi titik seri induk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPointIndex | int | Indeks titik data dalam koleksi titik seri induk. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Menghapus item dari koleksi berdasarkan indeksnya dalam koleksi titik seri induk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPointIndex | int | Indeks titik data dalam koleksi titik seri induk.. |