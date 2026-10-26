---
title: CommentCollection
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kumpulan komentar dari satu penulis.
type: docs
url: /id/com.aspose.slides/commentcollection/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Mewakili kumpulan komentar dari satu penulis.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [size()](#size--) | Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan elemen pada indeks yang ditentukan. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Menambahkan komentar baru di akhir koleksi. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Menambahkan komentar modern baru di akhir koleksi. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Menyisipkan komentar baru ke dalam koleksi pada indeks yang ditentukan. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Menyisipkan komentar modern baru ke dalam koleksi pada indeks yang ditentukan. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua komentar. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua komentar dari rentang yang ditentukan. |
| [removeAt(int index)](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dalam koleksi. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Menghapus kemunculan pertama komentar yang ditentukan dalam koleksi. |
| [clear()](#clear--) | Menghapus semua komentar dari koleksi. |
| [iterator()](#iterator--) | Mengembalikan enumerator yang mengiterasi koleksi. |
| [iteratorJava()](#iteratorJava--) | Mengembalikan iterator java untuk seluruh koleksi. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Menemukan komentar dalam koleksi berdasarkan indeks. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Menyalin semua elemen dari koleksi ke array yang ditentukan. |
| [isSynchronized()](#isSynchronized--) | Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman dari thread). |
| [getSyncRoot()](#getSyncRoot--) | Mengembalikan akar sinkronisasi. |
### size() {#size--}
```
public final int size()
```


Mendapatkan jumlah elemen yang sebenarnya terkandung dalam koleksi. Hanya-baca  int .

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


Mendapatkan elemen pada indeks yang ditentukan. Hanya-baca [Comment](../../com.aspose.slides/comment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```


Menambahkan komentar baru di akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks biasa dari komentar baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar baru. |
| position | android.graphics.PointF | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar. |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment) - Komentar yang ditambahkan.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Menambahkan komentar modern baru di akhir koleksi.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks biasa dari komentar modern baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [IShape](../../com.aspose.slides/ishape) | Bentuk pada slide yang terkait dengan komentar modern baru. |
| position | android.graphics.PointF | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar modern. |

**Mengembalikan:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Komentar modern yang ditambahkan.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```


Menyisipkan komentar baru ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen dalam koleksi tempat komentar harus disisipkan. |
| text | java.lang.String | Teks biasa dari komentar baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar baru. |
| position | android.graphics.PointF | Posisi pada slide tempat menambahkan komentar baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar. |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment) - Komentar yang disisipkan.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```


Menyisipkan komentar modern baru ke dalam koleksi pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen dalam koleksi tempat komentar modern harus disisipkan. |
| text | java.lang.String | Teks biasa dari komentar modern baru. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide dalam presentasi tempat menambahkan komentar modern baru. |
| shape | [IShape](../../com.aspose.slides/ishape) | Bentuk pada slide yang terkait dengan komentar modern baru. |
| position | android.graphics.PointF | Posisi pada slide tempat menambahkan komentar modern baru. |
| creationTime | java.util.Date | Waktu pembuatan komentar modern. |

**Mengembalikan:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Komentar modern yang disisipkan.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Membuat dan mengembalikan array dengan semua komentar.

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Membuat dan mengembalikan array dengan semua komentar dari rentang yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks komentar pertama yang akan dikembalikan. |
| count | int | Jumlah komentar yang akan dikembalikan. |

**Mengembalikan:**
com.aspose.slides.IComment[] - Array dari [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus elemen pada indeks yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari elemen yang akan dihapus. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Menghapus kemunculan pertama komentar yang ditentukan dalam koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | Komentar yang akan dihapus dari koleksi. |
### clear() {#clear--}
```
public final void clear()
```


Menghapus semua komentar dari koleksi.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


Mengembalikan enumerator yang mengiterasi koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Sebuah IGenericEnumerator yang dapat digunakan untuk mengiterasi koleksi.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


Mengembalikan iterator java untuk seluruh koleksi.

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Sebuah java.util.Iterator untuk seluruh koleksi.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Menemukan komentar dalam koleksi berdasarkan indeks.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| idx | int | Indeks unik komentar yang akan dicari  int . |

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment) - Komentar yang ditemukan atau null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Menyalin semua elemen dari koleksi ke array yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array target. |
| index | int | Indeks mulai dalam array target. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Mengembalikan nilai yang menunjukkan apakah akses ke koleksi disinkronkan (aman dari thread). Hanya-baca  boolean .

**Mengembalikan:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Mengembalikan akar sinkronisasi. Hanya-baca  Object .

**Mengembalikan:**
java.lang.Object