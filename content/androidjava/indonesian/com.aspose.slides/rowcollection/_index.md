---
title: RowCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi baris tabel.
type: docs
url: /id/com.aspose.slides/rowcollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Mewakili kumpulan baris tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah baris yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan baris pada indeks yang ditentukan. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Menghapus baris pada posisi yang ditentukan dari tabel. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mendapatkan jumlah baris yang sebenarnya terkandung dalam koleksi. **Baca-saja int.**

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Mengembalikan baris pada indeks yang ditentukan. **Baca-saja [Row](../../com.aspose.slides/row).**

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Baris yang digunakan sebagai templat. |
| withAttachedRows | boolean | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

**Mengembalikan:**
com.aspose.slides.IRow[] - Baris yang ditambahkan.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks baris baru. |
| templ | [IRow](../../com.aspose.slides/irow) | Baris yang digunakan sebagai templat. |
| withAttachedRows | boolean | True untuk menyalin juga semua baris yang terlampir pada baris templat. |

**Mengembalikan:**
com.aspose.slides.IRow[] - Baris yang disisipkan.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Menghapus baris pada posisi yang ditentukan dari tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstRowIndex | int | Indeks baris yang akan dihapus. |
| withAttachedRows | boolean | True untuk menghapus juga semua baris yang terlampir. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai di array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). **Baca-saja boolean.**

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. **Baca-saja Object.**

**Mengembalikan:**
java.lang.Object