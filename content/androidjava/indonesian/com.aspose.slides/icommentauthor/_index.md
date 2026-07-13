---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili penulis komentar.
type: docs
url: /id/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Mewakili penulis komentar.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getName()](#getName--) | Mengembalikan atau mengatur nama penulis. |
| [setName(String value)](#setName-java.lang.String-) | Mengembalikan atau mengatur nama penulis. |
| [getInitials()](#getInitials--) | Mengembalikan atau mengatur inisial penulis. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Mengembalikan atau mengatur inisial penulis. |
| [getComments()](#getComments--) | Mengembalikan koleksi komentar yang dibuat oleh penulis ini. |
| [remove()](#remove--) | Menghapus penulis dari koleksi induk. |
### getName() {#getName--}
```
public abstract String getName()
```


Mengembalikan atau mengatur nama penulis. Baca/tulis String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Mengembalikan atau mengatur nama penulis. Baca/tulis String.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Mengembalikan atau mengatur inisial penulis. Baca/tulis String.

**Returns:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Mengembalikan atau mengatur inisial penulis. Baca/tulis String.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Mengembalikan koleksi komentar yang dibuat oleh penulis ini. Baca-saja [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Returns:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Menghapus penulis dari koleksi induk.