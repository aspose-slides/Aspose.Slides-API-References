---
title: IRowCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi baris tabel.
type: docs
url: /id/com.aspose.slides/irowcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Mewakili koleksi baris tabel.
## Metode

| Method | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Menghapus baris pada posisi yang ditentukan dari tabel. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
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
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
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
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Menghapus baris pada posisi yang ditentukan dari tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstRowIndex | int | Indeks baris yang akan dihapus. |
| withAttachedRows | boolean | True untuk menghapus juga semua baris yang terlampir. |