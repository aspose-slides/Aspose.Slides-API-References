---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi titik untuk titik pemisahan pada diagram bar-of-pie atau pie-of-pie dengan pemisahan khusus.
type: docs
url: /id/com.aspose.slides/piesplitcustompointcollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Mewakili koleksi titik untuk titik pemisahan pada diagram bar-of-pie atau pie-of-pie dengan pemisahan khusus.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan titik data bagan untuk indeks yang ditentukan. |
| [add(int dataPointIndex)](#add-int-) | Menambahkan titik data berdasarkan indeksnya dalam koleksi titik seri induk. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | Menambahkan titik data ke koleksi. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | Menghapus item dari koleksi. |
| [remove(int dataPointIndex)](#remove-int-) | Menghapus item dari koleksi berdasarkan indeksnya dalam koleksi titik seri induk. |
| [clear()](#clear--) | Menghapus semua item dari [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke dalam Array, mulai pada indeks Array tertentu. |
| [size()](#size--) | Mengembalikan atau mengatur jumlah titik data bagan. |
| [isReadOnly()](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya-baca. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Mengembalikan titik data bagan untuk indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks. |

**Mengembalikan:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Titik data bagan.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

Menambahkan titik data berdasarkan indeksnya dalam koleksi titik seri induk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPointIndex | int | Indeks titik data dalam koleksi titik seri induk. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

Menambahkan titik data ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Titik data yang akan ditambahkan. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

Menghapus item dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Titik data yang akan dihapus. |

**Mengembalikan:**
boolean - true jika item berhasil dihapus; otherwise, false. Metode ini juga mengembalikan false jika item tidak ditemukan dalam System.Collections.Generic.List\{T\}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

Menghapus item dari koleksi berdasarkan indeksnya dalam koleksi titik seri induk.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dataPointIndex | int | Indeks titik data dalam koleksi titik seri induk. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua item dari [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

Menentukan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) berisi nilai tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Objek yang akan dicari dalam [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Mengembalikan:**
boolean - true jika item ditemukan dalam [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Menyalin elemen [IGenericCollection](../../com.aspose.slides/igenericcollection) ke dalam Array, mulai pada indeks Array tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | Array satu dimensi yang menjadi tujuan elemen yang disalin dari [IGenericCollection](../../com.aspose.slides/igenericcollection). Array harus memiliki pengindeksan berbasis nol. |
| arrayIndex | int | Indeks berbasis nol dalam array tempat penyalinan dimulai. |

### size() {#size--}
```
public final int size()
```

Mengembalikan atau mengatur jumlah titik data bagan. int hanya-baca.

**Mengembalikan:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya-baca. boolean hanya-baca.

**Mengembalikan:**
boolean - true jika [IGenericCollection](../../com.aspose.slides/igenericcollection) hanya-baca; otherwise, false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). boolean hanya-baca.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Object hanya-baca.

**Mengembalikan:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator untuk seluruh koleksi.