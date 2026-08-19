---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /id/com.aspose.slides/icomment/
---```
public interface IComment
```

Mewakili komentar pada slide.
## Metode

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Mengembalikan atau mengatur teks biasa dari komentar slide. |
| [setText(String value)](#setText-java.lang.String-) | Mengembalikan atau mengatur teks biasa dari komentar slide. |
| [getCreatedTime()](#getCreatedTime--) | Mengembalikan atau mengatur waktu pembuatan komentar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Mengembalikan atau mengatur waktu pembuatan komentar. |
| [getSlide()](#getSlide--) | Mengembalikan atau mengatur slide induk komentar. |
| [getAuthor()](#getAuthor--) | Mengembalikan penulis komentar. |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi komentar pada slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Mengembalikan atau mengatur posisi komentar pada slide. |
| [remove()](#remove--) | Menghapus komentar dan semua balasannya dari koleksi induk. |
| [getParentComment()](#getParentComment--) | Mengambil atau mengatur komentar induk. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Mengambil atau mengatur komentar induk. |
### getText() {#getText--}
```
public abstract String getText()
```


Mengembalikan atau mengatur teks biasa komentar slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Mengembalikan atau mengatur teks biasa komentar slide. Baca/tulis String.

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

Waktu komentar adalah parameter opsional.

**Mengembalikan:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


Mengembalikan atau mengatur waktu pembuatan komentar. Menetapkan properti ini ke java.util.Date(Long.MIN_VALUE) berarti tidak ada waktu komentar yang diatur. Baca/tulis java.util.Date.

--------------------

Waktu komentar adalah parameter opsional.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```


Mengembalikan atau mengatur slide induk komentar. Hanya-baca [ISlide](../../com.aspose.slides/islide).

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
public abstract Point2D.Float getPosition()
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis java.awt.geom.Point2D.Float.

**Mengembalikan:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis java.awt.geom.Point2D.Float.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
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