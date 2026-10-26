---
title: Comment
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje komentarz na slajdzie.
type: docs
url: /pl/com.aspose.slides/comment/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Reprezentuje komentarz na slajdzie.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Tworzy instancję klasy Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Dodaje pusty slajd
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Dodaje autora
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Ustawia pozycję komentarzy
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Dodaje komentarz slajdu dla autora na slajdzie 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Dodaje komentarz slajdu dla autora na slajdzie 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Zapisuje plik prezentacji PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Tworzy instancję klasy Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Iteruje autorów komentarzy
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Iteruje komentarze
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
>  // Tworzy instancję klasy Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Dodaje komentarz
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Dodaje odpowiedź do comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Dodaje kolejną odpowiedź do comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Dodaje odpowiedź do istniejącej odpowiedzi
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Wyświetla hierarchię komentarzy w konsoli
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
>      // Usuwa comment1 i wszystkie odpowiedzi do niego
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getText()](#getText--) | Zwraca lub ustawia zwykły tekst komentarza slajdu. |
| [setText(String value)](#setText-java.lang.String-) | Zwraca lub ustawia zwykły tekst komentarza slajdu. |
| [getCreatedTime()](#getCreatedTime--) | Zwraca lub ustawia czas utworzenia komentarza. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Zwraca lub ustawia czas utworzenia komentarza. |
| [getSlide()](#getSlide--) | Zwraca lub ustawia slajd nadrzędny komentarza. |
| [getAuthor()](#getAuthor--) | Zwraca autora komentarza. |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję komentarza na slajdzie. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Zwraca lub ustawia pozycję komentarza na slajdzie. |
| [remove()](#remove--) | Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej. |
| [getParentComment()](#getParentComment--) | Zwraca lub ustawia komentarz nadrzędny. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Zwraca lub ustawia komentarz nadrzędny. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Zwraca lub ustawia zwykły tekst komentarza slajdu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Zwraca lub ustawia zwykły tekst komentarza slajdu. Odczyt/zapis String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Zwraca lub ustawia czas utworzenia komentarza. Ustawienie tej właściwości na java.util.Date(Long.MIN_VALUE) oznacza, że czas komentarza nie jest ustawiony. Odczyt/zapis java.util.Date.

--------------------

Czas komentarza jest opcjonalnym parametrem.

**Zwraca:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Zwraca lub ustawia czas utworzenia komentarza. Ustawienie tej właściwości na java.util.Date(Long.MIN_VALUE) oznacza, że czas komentarza nie jest ustawiony. Odczyt/zapis java.util.Date.

--------------------

Czas komentarza jest opcjonalnym parametrem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Zwraca lub ustawia slajd nadrzędny komentarza. Tylko do odczytu [ISlide](../../com.aspose.slides/islide).

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Zwraca autora komentarza. Tylko do odczytu [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Zwraca:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Zwraca lub ustawia pozycję komentarza na slajdzie. Odczyt/zapis android.graphics.PointF.

**Zwraca:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Zwraca lub ustawia pozycję komentarza na slajdzie. Odczyt/zapis android.graphics.PointF.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Usuwa komentarz i wszystkie jego odpowiedzi z kolekcji nadrzędnej.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Zwraca lub ustawia komentarz nadrzędny. Odczyt/zapis [IComment](../../com.aspose.slides/icomment).

**Zwraca:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Zwraca lub ustawia komentarz nadrzędny. Odczyt/zapis [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject