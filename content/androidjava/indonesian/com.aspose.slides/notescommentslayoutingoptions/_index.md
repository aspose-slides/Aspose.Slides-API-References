---
title: NotesCommentsLayoutingOptions
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menyediakan opsi yang mengontrol tampilan tata letak catatan dan komentar dalam dokumen yang diekspor.
type: docs
url: /id/com.aspose.slides/notescommentslayoutingoptions/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Menyediakan opsi yang mengontrol tampilan tata letak catatan dan komentar dalam dokumen yang diekspor.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Konstruktor default. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Mendapatkan atau mengatur visibilitas komentar yang tidak memiliki penulis. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Mendapatkan atau mengatur visibilitas komentar yang tidak memiliki penulis. |
| [getNotesPosition()](#getNotesPosition--) | Mendapatkan atau mengatur posisi catatan pada halaman. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Mendapatkan atau mengatur posisi catatan pada halaman. |
| [getCommentsPosition()](#getCommentsPosition--) | Mendapatkan atau mengatur posisi komentar pada halaman. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Mendapatkan atau mengatur posisi komentar pada halaman. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Mendapatkan atau mengatur warna area komentar (Hanya berlaku jika komentar ditampilkan di kanan). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Mendapatkan atau mengatur warna area komentar (Hanya berlaku jika komentar ditampilkan di kanan). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Mendapatkan atau mengatur lebar area output komentar dalam piksel (Hanya berlaku jika komentar ditampilkan di kanan). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Mendapatkan atau mengatur lebar area output komentar dalam piksel (Hanya berlaku jika komentar ditampilkan di kanan). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```


Konstruktor default.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```


Mendapatkan atau mengatur visibilitas komentar yang tidak memiliki penulis. Jika true maka komentar akan ditampilkan. (Hanya berlaku jika komentar ditampilkan).

--------------------

Nilai default adalah **false**.

**Mengembalikan:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```


Mendapatkan atau mengatur visibilitas komentar yang tidak memiliki penulis. Jika true maka komentar akan ditampilkan. (Hanya berlaku jika komentar ditampilkan).

--------------------

Nilai default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```


Mendapatkan atau mengatur posisi catatan pada halaman.

--------------------

Nilai default adalah **NotesPositions.None**.

**Mengembalikan:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```


Mendapatkan atau mengatur posisi catatan pada halaman.

--------------------

Nilai default adalah **NotesPositions.None**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```


Mendapatkan atau mengatur posisi komentar pada halaman.

--------------------

Nilai default adalah **CommentsPositions.None**.

**Mengembalikan:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```


Mendapatkan atau mengatur posisi komentar pada halaman.

--------------------

Nilai default adalah **CommentsPositions.None**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```


Mendapatkan atau mengatur warna area komentar (Hanya berlaku jika komentar ditampilkan di kanan).

--------------------

Nilai default adalah **SkyBlue**.

**Mengembalikan:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```


Mendapatkan atau mengatur warna area komentar (Hanya berlaku jika komentar ditampilkan di kanan).

--------------------

Nilai default adalah **SkyBlue**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```


Mendapatkan atau mengatur lebar area output komentar dalam piksel (Hanya berlaku jika komentar ditampilkan di kanan).

--------------------

Nilai minimal dan default adalah **150**.

**Mengembalikan:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```


Mendapatkan atau mengatur lebar area output komentar dalam piksel (Hanya berlaku jika komentar ditampilkan di kanan).

--------------------

Nilai minimal dan default adalah **150**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |