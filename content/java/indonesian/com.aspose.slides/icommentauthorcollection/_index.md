---
title: ICommentAuthorCollection
second_title: Referensi API Aspose.Slides untuk Java
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
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Add new author at the end of a collection. |
| [toArray()](#toArray--) | Creates and returns an array with all authors. |
| [findByName(String name)](#findByName-java.lang.String-) | Find author in a collection by name. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Find author in a collection by name and initials. |
| [removeAt(int index)](#removeAt-int-) | Removes the author at the specified index of the collection. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Removes the first occurrence of the specified author in a collection. |
| [clear()](#clear--) | Removes all authors from a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```


Gets the element at the specified index. Baca-saja [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
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

**Mengembalikan:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Objek [ICommentAuthor](../../com.aspose.slides/icommentauthor) baru.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```


Membuat dan mengembalikan array dengan semua penulis.

**Mengembalikan:**
com.aspose.slides.ICommentAuthor[] - Array dari [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```


Mencari penulis dalam koleksi berdasarkan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang akan dicari. |

**Mengembalikan:**
com.aspose.slides.ICommentAuthor[] - Penulis atau null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Mencari penulis dalam koleksi berdasarkan nama dan inisial.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang akan dicari. |
| initials | java.lang.String | Inisial penulis yang akan dicari. |

**Mengembalikan:**
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