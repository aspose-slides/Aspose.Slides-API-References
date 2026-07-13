---
title: VbaModuleCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan modul Proyek VBA.
type: docs
url: /id/com.aspose.slides/vbamodulecollection/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Mewakili kumpulan modul Proyek VBA.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Menghapus kemunculan pertama objek tertentu dari koleksi. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Menambahkan modul kosong baru ke Proyek VBA. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman dari thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan root sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca int.

**Mengembalikan:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```

Menghapus kemunculan pertama objek tertentu dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Modul yang akan dihapus dari koleksi. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

Menambahkan modul kosong baru ke Proyek VBA.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama modul |

**Mengembalikan:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Modul yang ditambahkan.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Sebuah java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array tujuan. |
| index | int | Indeks awal pada array tujuan. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman dari thread). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan root sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object