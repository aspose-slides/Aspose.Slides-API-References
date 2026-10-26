---
title: ColumnCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi kolom dalam sebuah tabel.
type: docs
url: /id/com.aspose.slides/columncollection/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Mewakili kumpulan kolom dalam sebuah tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mengembalikan jumlah kolom dalam sebuah koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan kolom pada indeks yang ditentukan. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Menghapus kolom pada posisi yang ditentukan dari tabel. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```

Mengembalikan jumlah kolom dalam sebuah koleksi. Hanya-baca int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Mengembalikan kolom pada indeks yang ditentukan. Hanya-baca [Column](../../com.aspose.slides/column).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom yang digunakan sebagai templat. |
| withAttachedColumns | boolean | True untuk menyalin juga semua kolom yang terlampir pada baris templat. |

**Mengembalikan:**
com.aspose.slides.IColumn[] - Kolom yang ditambahkan.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kolom baru. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Kolom yang digunakan sebagai templat. |
| withAttachedColumns | boolean | True untuk menyalin juga semua kolom yang terlampir pada kolom templat. |

**Mengembalikan:**
com.aspose.slides.IColumn[] - Kolom yang disisipkan.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Menghapus kolom pada posisi yang ditentukan dari tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstColumnIndex | int | Indeks kolom yang akan dihapus. |
| withAttachedRows | boolean | True untuk menghapus juga semua kolom yang terlampir. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator untuk seluruh koleksi.
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

Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (thread-safe). Hanya-baca boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Mengembalikan akar sinkronisasi. Hanya-baca Object.

**Mengembalikan:**
java.lang.Object