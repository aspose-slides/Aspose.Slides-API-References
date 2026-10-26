---
title: ICommentCollection
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili koleksi komentar dari satu penulis.
type: docs
url: /id/com.aspose.slides/icommentcollection/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Mewakili koleksi komentar dari satu penulis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Mengambil elemen pada indeks yang ditentukan. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Menambahkan komentar baru di akhir koleksi. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Menambahkan komentar modern baru di akhir koleksi. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Menyisipkan komentar baru ke koleksi pada indeks yang ditentukan. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Menyisipkan komentar modern baru ke koleksi pada indeks yang ditentukan. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua komentar. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua komentar dari rentang yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Menghapus kemunculan pertama komentar yang ditentukan dalam koleksi. |
| [clear()](#clear--) | Menghapus semua komentar dari koleksi. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```


Mengambil elemen pada indeks yang ditentukan. Hanya-baca [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Menambahkan komentar baru di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks biasa dari komentar baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar baru. |
| position | java.awt.geom.Point2D.Float | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar. |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment) - Komentar yang ditambahkan.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Menambahkan komentar modern baru di akhir koleksi.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks biasa dari komentar modern baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [IShape](../../com.aspose.slides/ishape) | Bentuk pada slide yang terkait dengan komentar modern baru. |
| position | java.awt.geom.Point2D.Float | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar modern. |

**Mengembalikan:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Komentar modern yang ditambahkan.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Menyisipkan komentar baru ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen dalam koleksi tempat komentar harus disisipkan. |
| text | java.lang.String | Teks biasa dari komentar baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar baru. |
| position | java.awt.geom.Point2D.Float | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar. |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment) - Komentar yang disisipkan.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Menyisipkan komentar modern baru ke koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen dalam koleksi tempat komentar modern harus disisipkan. |
| text | java.lang.String | Teks biasa dari komentar modern baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [IShape](../../com.aspose.slides/ishape) | Bentuk pada slide yang terkait dengan komentar modern baru. |
| position | java.awt.geom.Point2D.Float | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar modern. |

**Mengembalikan:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Komentar modern yang disisipkan.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```


Membuat dan mengembalikan array dengan semua komentar.

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```


Membuat dan mengembalikan array dengan semua komentar dari rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks komentar pertama yang akan dikembalikan. |
| count | int | Jumlah komentar yang akan dikembalikan. |

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```


Menghapus kemunculan pertama komentar yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentar yang akan dihapus dari koleksi. |

### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua komentar dari koleksi.