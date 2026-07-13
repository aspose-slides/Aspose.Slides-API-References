---
title: CommentAuthorCollection
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili koleksi penulis komentar.
type: docs
url: /id/com.aspose.slides/commentauthorcollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
```
public final class CommentAuthorCollection extends DomObject<Presentation> implements ICommentAuthorCollection
```

Mewakili koleksi penulis komentar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | Menambahkan penulis baru di akhir koleksi. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua penulis. |
| [findByName(String name)](#findByName-java.lang.String-) | Menemukan penulis dalam koleksi berdasarkan nama. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | Menemukan penulis dalam koleksi berdasarkan nama dan inisial. |
| [removeAt(int index)](#removeAt-int-) | Menghapus penulis pada indeks yang ditentukan dalam koleksi. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | Menghapus kemunculan pertama penulis yang ditentukan dalam koleksi. |
| [clear()](#clear--) | Menghapus semua penulis dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ICommentAuthor get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Baca-saja [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public final ICommentAuthor addAuthor(String name, String initials)
```


Menambahkan penulis baru di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis baru. |
| initials | java.lang.String | Inisial penulis baru. |

**Mengembalikan:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - Baru [ICommentAuthor](../../com.aspose.slides/icommentauthor) object.
### toArray() {#toArray--}
```
public final ICommentAuthor[] toArray()
```


Membuat dan mengembalikan array dengan semua penulis.

**Mengembalikan:**
com.aspose.slides.ICommentAuthor[] - Array dari [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public final ICommentAuthor[] findByName(String name)
```


Menemukan penulis dalam koleksi berdasarkan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang akan dicari. |

**Mengembalikan:**
com.aspose.slides.ICommentAuthor[] - Penulis atau null.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public final ICommentAuthor[] findByNameAndInitials(String name, String initials)
```


Menemukan penulis dalam koleksi berdasarkan nama dan inisial.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama penulis yang akan dicari. |
| initials | java.lang.String | Inisial penulis yang akan dicari. |

**Mengembalikan:**
com.aspose.slides.ICommentAuthor[] - Penulis atau null.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus penulis pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public final void remove(ICommentAuthor author)
```


Menghapus kemunculan pertama penulis yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Penulis yang akan dihapus dari koleksi. |
### clear() {#clear--}
```
public final void clear()
```


Menghapus semua penulis dari koleksi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICommentAuthor> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICommentAuthor> - Sebuah java.util.Iterator untuk seluruh koleksi.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai pada array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman terhadap thread). Baca-saja boolean.

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Baca-saja Object.

**Mengembalikan:**
java.lang.Object