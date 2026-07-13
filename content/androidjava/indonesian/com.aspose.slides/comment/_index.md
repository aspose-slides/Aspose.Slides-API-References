---
title: Comment
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili komentar pada slide.
type: docs
url: /id/com.aspose.slides/comment/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Mewakili komentar pada slide.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Menginstansiasi kelas Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Menambahkan slide kosong
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Menambahkan penulis
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Menetapkan posisi untuk komentar
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Menambahkan komentar slide untuk penulis pada slide 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Menambahkan komentar slide untuk penulis pada slide 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Simpan file Presentasi PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Menginstansiasi kelas Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Iterasi CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Iterasi Komentar
>          for (IComment comment1 : author.getComments())
>          {
>              Comment comment = (Comment) comment1;
>              System.out.println("ISlide :" + comment.getSlide().getSlideNumber() + " has comment: " + comment.getText() + " with Author: " + comment.getAuthor().getName() + " posted on time :" + comment.getCreatedTime().toString() + "\n");
>          }
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to add comments and get replies to them.
>  
>  // Menginstansiasi kelas Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Menambahkan komentar
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Menambahkan balasan untuk comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Menambahkan balasan lain untuk comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Menambahkan balasan ke balasan yang ada
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Menampilkan hierarki komentar di konsol
>      ISlide slide = pres.getSlides().get_Item(0);
>      IComment[] comments = slide.getSlideComments(null);
>      for (int i = 0; i < comments.length; i++)
>      {
>          IComment comment = comments[i];
>          while (comment.getParentComment() != null)
>          {
>              System.out.println("\t");
>              comment = comment.getParentComment();
>          }
>          System.out.println(comments[i].getAuthor().getName() + " : " + comments[i].getText());
>      }
>      pres.save("parent_comment.pptx",SaveFormat.Pptx);
>      // Menghapus comment1 dan semua balasannya
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

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
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


Mengembalikan atau mengatur teks biasa dari komentar slide. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Mengembalikan atau mengatur teks biasa dari komentar slide. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Mengembalikan atau mengatur waktu pembuatan komentar. Menetapkan properti ini ke java.util.Date(Long.MIN_VALUE) berarti tidak ada waktu komentar yang diatur. Baca/tulis java.util.Date.

--------------------

Waktu komentar adalah parameter opsional.

**Mengembalikan:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
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
public final ISlide getSlide()
```


Mengembalikan atau mengatur slide induk dari komentar. Hanya baca [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


Mengembalikan penulis komentar. Hanya baca [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Mengembalikan:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis android.graphics.PointF.

**Mengembalikan:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```


Mengembalikan atau mengatur posisi komentar pada slide. Baca/tulis android.graphics.PointF.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```


Menghapus komentar dan semua balasannya dari koleksi induk.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


Mengambil atau mengatur komentar induk. Baca/tulis [IComment](../../com.aspose.slides/icomment).

**Mengembalikan:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


Mengambil atau mengatur komentar induk. Baca/tulis [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Mengembalikan objek Parent_Immediate. Hanya baca IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject