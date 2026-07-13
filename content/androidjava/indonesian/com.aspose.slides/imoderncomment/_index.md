---
title: IModernComment
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili komentar pada slide.
type: docs
url: /id/com.aspose.slides/imoderncomment/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment)
```
public interface IModernComment extends IComment
```

Mewakili komentar pada slide.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShape()](#getShape--) | Mengembalikan shape yang terkait dengan komentar. |
| [getTextSelectionStart()](#getTextSelectionStart--) | Mengembalikan atau mengatur posisi awal seleksi teks dalam text frame jika komentar terkait dengan AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Mengembalikan atau mengatur posisi awal seleksi teks dalam text frame jika komentar terkait dengan AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Mengembalikan atau mengatur panjang seleksi teks dalam text frame jika komentar terkait dengan AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Mengembalikan atau mengatur panjang seleksi teks dalam text frame jika komentar terkait dengan AutoShape. |
| [getStatus()](#getStatus--) | Mengembalikan atau mengatur status komentar. |
| [setStatus(byte value)](#setStatus-byte-) | Mengembalikan atau mengatur status komentar. |
### getShape() {#getShape--}
```
public abstract IShape getShape()
```


Mengembalikan shape yang terkait dengan komentar. Hanya-baca [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public abstract int getTextSelectionStart()
```


Mengembalikan atau mengatur posisi awal seleksi teks dalam text frame jika komentar terkait dengan AutoShape. Baca/tulis int.

**Mengembalikan:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public abstract void setTextSelectionStart(int value)
```


Mengembalikan atau mengatur posisi awal seleksi teks dalam text frame jika komentar terkait dengan AutoShape. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public abstract int getTextSelectionLength()
```


Mengembalikan atau mengatur panjang seleksi teks dalam text frame jika komentar terkait dengan AutoShape. Baca/tulis int.

**Mengembalikan:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public abstract void setTextSelectionLength(int value)
```


Mengembalikan atau mengatur panjang seleksi teks dalam text frame jika komentar terkait dengan AutoShape. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public abstract byte getStatus()
```


Mengembalikan atau mengatur status komentar. Baca/tulis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Mengembalikan:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public abstract void setStatus(byte value)
```


Mengembalikan atau mengatur status komentar. Baca/tulis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |