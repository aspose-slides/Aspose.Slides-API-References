---
title: ChartCategoryCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi
type: docs
url: /id/com.aspose.slides/chartcategorycollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Mewakili koleksi dari [ChartCategory](../../com.aspose.slides/chartcategory)
## Metode

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [getUseCells()](#getUseCells--) | Jika true maka worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Jika true maka worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Mengembalikan jumlah level pengelompokan kategori yang digunakan. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Jika kategori ada dalam koleksi, kembalikan. |
| [add(Object value)](#add-java.lang.Object-) | Membuat [ChartCategory](../../com.aspose.slides/chartcategory) baru dari nilai dan menambahkannya ke koleksi. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Mencari [ChartCategory](../../com.aspose.slides/chartcategory) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang diberikan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [size()](#size--) | Mengembalikan jumlah elemen dalam koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke List disinkronkan (aman untuk thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Mengambil elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Elemen pada indeks yang ditentukan.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Jika true maka worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka worksheet TIDAK digunakan untuk menyimpan nilai (dan kasus ini tidak mendukung kategori multi-level). Boolean baca/tulis.

**Mengembalikan:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Jika true maka worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka worksheet TIDAK digunakan untuk menyimpan nilai (dan kasus ini tidak mendukung kategori multi-level). Boolean baca/tulis.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Mengembalikan jumlah level pengelompokan kategori yang digunakan. Lebih dari satu untuk kategori multi-level. int hanya-baca.

**Mengembalikan:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Jika kategori ada dalam koleksi, kembalikan. Jika tidak, buat kategori diagram baru dari [IChartDataCell](../../com.aspose.slides/ichartdatacell) dan tambahkan ke koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel yang digunakan untuk membuat kategori diagram. |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Kategori yang ditambahkan atau yang sudah ada.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Membuat [ChartCategory](../../com.aspose.slides/chartcategory) baru dari nilai dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | Nilai.

--------------------

Metode ini menambahkan worksheet dengan nama AUTO_DATA dan menambahkan semua nilai di sana. Jika Anda menggunakan [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) untuk menambah atau mengedit nilai sel, pastikan Anda tidak menggunakan worksheet ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680 |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Ditambahkan [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Mencari [ChartCategory](../../com.aspose.slides/chartcategory) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Collection.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategori diagram. |

**Mengembalikan:**
int - Indeks berbasis nol dari kemunculan pertama nilai dalam seluruh CollectionBase, jika ditemukan; jika tidak, -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Nilainya. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang diberikan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks kategori yang akan dihapus. |

### clear() {#clear--}
```
public final void clear()
```

Menghapus semua elemen dari koleksi.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Sebuah java.util.Iterator untuk seluruh koleksi.

### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah elemen dalam koleksi. int hanya-baca.

**Mengembalikan:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke List disinkronkan (aman untuk thread). boolean hanya-baca.

**Mengembalikan:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan objek yang dapat digunakan untuk menyinkronkan akses ke koleksi. Object hanya-baca.

Mengembalikan akar sinkronisasi. Object hanya-baca.

**Mengembalikan:**
java.lang.Object