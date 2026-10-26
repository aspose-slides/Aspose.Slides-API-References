---
title: IChartCategoryCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi
type: docs
url: /id/com.aspose.slides/ichartcategorycollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Mewakili koleksi [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [getUseCells()](#getUseCells--) | Jika true maka lembar kerja digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Jika true maka lembar kerja digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Mengembalikan jumlah tingkat pengelompokan kategori yang digunakan. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Jika kategori ada dalam koleksi, mengembalikannya. |
| [add(Object value)](#add-java.lang.Object-) | Membuat [IChartCategory](../../com.aspose.slides/ichartcategory) baru dari nilai dan menambahkannya ke koleksi. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Mencari [IChartCategory](../../com.aspose.slides/ichartcategory) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Menghapus nilai yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang diberikan. |
| [clear()](#clear--) | Menghapus semua elemen dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Elemen pada indeks yang ditentukan.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Jika true maka lembar kerja digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka lembar kerja TIDAK digunakan untuk menyimpan nilai (dan kasus ini tidak mendukung kategori multi-level). Boolean baca/tulis.

**Mengembalikan:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Jika true maka lembar kerja digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka lembar kerja TIDAK digunakan untuk menyimpan nilai (dan kasus ini tidak mendukung kategori multi-level). Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Mengembalikan jumlah tingkat pengelompokan kategori yang digunakan. Lebih dari satu untuk kategori multi-level. Int baca-saja.

**Mengembalikan:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Jika kategori ada dalam koleksi, mengembalikannya. Jika tidak, membuat kategori diagram baru dari [IChartDataCell](../../com.aspose.slides/ichartdatacell) dan menambahkannya ke koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Sel yang digunakan untuk membuat kategori diagram. |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Kategori yang ditambahkan atau sudah ada.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Membuat [IChartCategory](../../com.aspose.slides/ichartcategory) baru dari nilai dan menambahkannya ke koleksi.

--------------------
Metode ini menambahkan lembar kerja dengan nama AUTO_DATA dan menambahkan semua nilai ke sana. Jika Anda menggunakan [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) untuk menambah atau mengedit nilai sel, pastikan Anda tidak menggunakan lembar kerja ini. Jumlah maksimum nilai yang ditambahkan menggunakan metode ini tidak boleh melebihi 16711680 |

**Mengembalikan:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Ditambahkan [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Mencari [IChartCategory](../../com.aspose.slides/ichartcategory) yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama dalam seluruh Collection

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Kategori diagram. |

**Mengembalikan:**
int - Indeks berbasis nol dari kemunculan pertama nilai dalam seluruh CollectionBase, jika ditemukan; jika tidak, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Menghapus nilai yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Nilai. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus elemen pada indeks yang diberikan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kategori yang akan dihapus. |

### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua elemen dari koleksi.