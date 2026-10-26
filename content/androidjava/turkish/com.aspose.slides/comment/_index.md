---
title: Comment
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir slayt üzerindeki yorumu temsil eder.
type: docs
url: /tr/com.aspose.slides/comment/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Bir slayt üzerindeki yorumu temsil eder.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Presentation sınıfını örnekler
>  Presentation presentation = new Presentation();
>  try {
>     // Boş bir slayt ekler
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Bir yazar ekler
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Yorumların konumunu ayarlar
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Yazar için slayt 1'de slayt yorumu ekler
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Yazar için slayt 2'de slayt yorumu ekler
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// PowerPoint Sunum dosyasını kaydet
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Presentation sınıfını örnekler
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // CommentAuthors üzerinde yineleme yap
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Yorumlar üzerinde yineleme yap
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
>  // Presentation sınıfını örnekler
>  Presentation pres = new Presentation();
>  try {
>     // Bir yorum ekler
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // comment1'e bir yanıt ekler
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // comment1'e bir yanıt daha ekler
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Mevcut yanıta bir yanıt ekler
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Yorum hiyerarşisini konsolda gösterir
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
>      // comment1'i ve ona ait tüm yanıtları kaldırır
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getText()](#getText--) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [setText(String value)](#setText-java.lang.String-) | Bir slayt yorumunun düz metnini alır veya ayarlar. |
| [getCreatedTime()](#getCreatedTime--) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Bir yorumun oluşturulma zamanını alır veya ayarlar. |
| [getSlide()](#getSlide--) | Bir yorumun ana slaydını alır veya ayarlar. |
| [getAuthor()](#getAuthor--) | Bir yorumun yazarını alır. |
| [getPosition()](#getPosition--) | Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. |
| [remove()](#remove--) | Yorumu ve tüm yanıtlarını ana koleksiyondan kaldırır. |
| [getParentComment()](#getParentComment--) | Üst yorum alır veya ayarlar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Üst yorum alır veya ayarlar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okuma/Yazma String.

**Döndürür:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Bir slayt yorumunun düz metnini alır veya ayarlar. Okuma/Yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN\_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Okuma/Yazma java.util.Date.

--------------------

Yorum zamanı isteğe bağlı bir parametredir.

**Döndürür:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Bir yorumun oluşturulma zamanını alır veya ayarlar. Bu özelliği java.util.Date(Long.MIN\_VALUE) olarak ayarlamak, yorum zamanının ayarlanmadığını gösterir. Okuma/Yazma java.util.Date.

--------------------

Yorum zamanı isteğe bağlı bir parametredir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Bir yorumun ana slaydını alır veya ayarlar. Yalnızca okunur [ISlide](../../com.aspose.slides/islide).

**Döndürür:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Bir yorumun yazarını alır. Yalnızca okunur [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Döndürür:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. Okuma/Yazma android.graphics.PointF.

**Döndürür:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Bir slayt üzerindeki yorumun konumunu alır veya ayarlar. Okuma/Yazma android.graphics.PointF.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Yorumu ve tüm yanıtlarını ana koleksiyondan kaldırır.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Üst yorumu alır veya ayarlar. Okuma/Yazma [IComment](../../com.aspose.slides/icomment).

**Döndürür:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Üst yorumu alır veya ayarlar. Okuma/Yazma [IComment](../../com.aspose.slides/icomment).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini alır. Yalnızca okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject