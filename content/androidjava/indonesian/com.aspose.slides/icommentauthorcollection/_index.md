---
title: ICommentAuthorCollection
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili koleksi penulis komentar.
type: docs
url: /id/com.aspose.slides/icommentauthorcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

Mewakili koleksi penulis komentar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Menambahkan penulis baru di akhir koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua penulis. |
| [findByName(String name)](#findByName-java.lang.String-) | Mencari penulis dalam koleksi berdasarkan nama. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Mencari penulis dalam koleksi berdasarkan nama dan inisial. |
| [removeAt(int index)](#removeAt-int-) | Menghapus penulis pada indeks yang ditentukan dalam koleksi. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Menghapus kemunculan pertama penulis yang ditentukan dalam koleksi. |
| [clear()](#clear--) | Menghapus semua penulis dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Return:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```


Menambahkan penulis baru di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis baru. |
| initials | java.lang.String | Inisial penulis baru. |

**Return:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Objek [ICommentAuthor](../../com.aspose.slides/icommentauthor) baru.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Membuat dan mengembalikan array dengan semua penulis.

**Return:**
com.aspose.slides.ICommentAuthor[] - Array dari [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Mencari penulis dalam koleksi berdasarkan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang dicari. |

**Return:**
com.aspose.slides.ICommentAuthor[] - Penulis atau null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Mencari penulis dalam koleksi berdasarkan nama dan inisial.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang dicari. |
| initials | java.lang.String | Inisial penulis yang dicari. |

**Return:**
com.aspose.slides.ICommentAuthor[] - Penulis atau null.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus penulis pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```


Menghapus kemunculan pertama penulis yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Penulis yang akan dihapus dari koleksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua penulis dari koleksi.