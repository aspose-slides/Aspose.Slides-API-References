---
title: ModernComment
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili komentar pada slide.
type: docs
url: /id/com.aspose.slides/moderncomment/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Comment](../../com.aspose.slides/comment)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IModernComment](../../com.aspose.slides/imoderncomment), com.aspose.slides.IDOMObject
```
public final class ModernComment extends Comment implements IModernComment, IDOMObject
```

Mewakili komentar pada sebuah slide.

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
| [getTextSelectionStart()](#getTextSelectionStart--) | Mendapatkan atau mengatur posisi awal pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. |
| [setTextSelectionStart(int value)](#setTextSelectionStart-int-) | Mendapatkan atau mengatur posisi awal pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. |
| [getTextSelectionLength()](#getTextSelectionLength--) | Mendapatkan atau mengatur panjang pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. |
| [setTextSelectionLength(int value)](#setTextSelectionLength-int-) | Mendapatkan atau mengatur panjang pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. |
| [getStatus()](#getStatus--) | Mendapatkan atau mengatur status komentar. |
| [setStatus(byte value)](#setStatus-byte-) | Mendapatkan atau mengatur status komentar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getShape() {#getShape--}
```
public final IShape getShape()
```


Mengembalikan shape yang terkait dengan komentar. Hanya-baca [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### getTextSelectionStart() {#getTextSelectionStart--}
```
public final int getTextSelectionStart()
```


Mendapatkan atau mengatur posisi awal pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. Baca/tulis int.

**Mengembalikan:**
int
### setTextSelectionStart(int value) {#setTextSelectionStart-int-}
```
public final void setTextSelectionStart(int value)
```


Mendapatkan atau mengatur posisi awal pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getTextSelectionLength() {#getTextSelectionLength--}
```
public final int getTextSelectionLength()
```


Mendapatkan atau mengatur panjang pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. Baca/tulis int.

**Mengembalikan:**
int
### setTextSelectionLength(int value) {#setTextSelectionLength-int-}
```
public final void setTextSelectionLength(int value)
```


Mendapatkan atau mengatur panjang pemilihan teks dalam bingkai teks jika komentar terkait dengan AutoShape. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getStatus() {#getStatus--}
```
public final byte getStatus()
```


Mendapatkan atau mengatur status komentar. Baca/tulis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Mengembalikan:**
byte
### setStatus(byte value) {#setStatus-byte-}
```
public final void setStatus(byte value)
```


Mendapatkan atau mengatur status komentar. Baca/tulis [ModernCommentStatus](../../com.aspose.slides/moderncommentstatus).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Hanya-baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject