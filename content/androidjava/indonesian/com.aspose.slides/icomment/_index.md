---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili sebuah komentar pada slide.
type: docs
url: /id/com.aspose.slides/icomment/
---```
public interface IComment
```

Mewakili sebuah komentar pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getText()](#getText--) | Mengembalikan atau mengatur teks biasa dari komentar slide. |
| [setText(String value)](#setText-java.lang.String-) | Mengembalikan atau mengatur teks biasa dari komentar slide. |
| [getCreatedTime()](#getCreatedTime--) | Mengembalikan atau mengatur waktu pembuatan komentar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Mengembalikan atau mengatur waktu pembuatan komentar. |
| [getSlide()](#getSlide--) | Mengembalikan atau mengatur slide induk dari komentar. |
| [getAuthor()](#getAuthor--) | Mengembalikan penulis komentar. |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi komentar pada slide. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Mengembalikan atau mengatur posisi komentar pada slide. |
| [remove()](#remove--) | Menghapus komentar dan semua balasannya dari koleksi induk. |
| [getParentComment()](#getParentComment--) | Mengambil atau mengatur komentar induk. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Mengambil atau mengatur komentar induk. |
### getText() {#getText--}
```
public abstract String getText()
```


Mengembalikan atau mengatur teks biasa dari komentar slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Mengembalikan atau mengatur teks biasa dari komentar slide. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```


Mengembalikan atau mengatur waktu pembuatan komentar. Menetapkan properti ini ke java.util.Date(Long.MIN_VALUE) berarti tidak ada waktu komentar yang diatur. Baca/tulis java.util.Date.

--------------------

Waktu komentar merupakan parameter opsional.

**Mengembalikan:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Mengembalikan atau mengatur waktu pembuatan komentar. Menetapkan properti ini ke java.util.Date(Long.MIN_VALUE) berarti tidak ada waktu komentar yang diatur. Baca/tulis java.util.Date.

--------------------

Waktu komentar merupakan parameter opsional.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Mengembalikan atau mengatur slide induk dari komentar. Hanya-baca [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```


Mengembalikan penulis komentar. Hanya-baca [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Mengembalikan:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```


Menghapus komentar dan semua balasannya dari koleksi induk.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```


Mengambil atau mengatur komentar induk. Baca/tulis [IComment](../../com.aspose.slides/icomment).

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```


Mengambil atau mengatur komentar induk. Baca/tulis [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |