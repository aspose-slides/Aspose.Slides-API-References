---
title: IColumnCollection
second_title: Referensi API Java untuk Aspose.Slides di Android
description: Mewakili koleksi kolom dalam tabel.
type: docs
url: /id/com.aspose.slides/icolumncollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Mewakili koleksi kolom dalam sebuah tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan kolom pada indeks yang ditentukan. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Membuat salinan baris templat yang ditentukan dan menyisipkannya di bagian bawah tabel. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Membuat salinan kolom templat yang ditentukan dan menyisipkannya pada posisi yang ditentukan dalam tabel. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Menghapus kolom pada posisi yang ditentukan dari sebuah tabel. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Mengembalikan kolom pada indeks yang ditentukan. Hanya-baca [IColumn](../../com.aspose.slides/icolumn).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
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
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
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
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Menghapus kolom pada posisi yang ditentukan dari sebuah tabel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| firstColumnIndex | int | Indeks kolom yang akan dihapus. |
| withAttachedRows | boolean | True untuk menghapus juga semua kolom yang terlampir. |