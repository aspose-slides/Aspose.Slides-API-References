---
title: Comment
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en kommentar på en bild.
type: docs
url: /sv/com.aspose.slides/comment/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Representerar en kommentar på en bild.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instansierar Presentation-klassen
>  Presentation presentation = new Presentation();
>  try {
>     // Lägger till en tom bild
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Lägger till en författare
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Anger positionen för kommentarer
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Lägger till en bildkommentar för en författare på bild 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Lägger till en bildkommentar för en författare på bild 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Sparar PowerPoint-presentationen
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instansierar Presentation-klassen
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Itererar över CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Itererar över kommentarer
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
>  // Instansierar Presentation-klassen
>  Presentation pres = new Presentation();
>  try {
>     // Lägger till en kommentar
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Lägger till ett svar på comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Lägger till ett annat svar på comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Lägger till ett svar på befintligt svar
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Visar kommentarshierarkin i konsolen
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
>      // Tar bort comment1 och alla svar på den
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Returnerar eller anger den rena texten för en bildkommentar. |
| [setText(String value)](#setText-java.lang.String-) | Returnerar eller anger den rena texten för en bildkommentar. |
| [getCreatedTime()](#getCreatedTime--) | Returnerar eller anger tiden för skapandet av en kommentar. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Returnerar eller anger tiden för skapandet av en kommentar. |
| [getSlide()](#getSlide--) | Returnerar eller anger den överordnade bilden för en kommentar. |
| [getAuthor()](#getAuthor--) | Returnerar författaren till en kommentar. |
| [getPosition()](#getPosition--) | Returnerar eller anger positionen för en kommentar på en bild. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Returnerar eller anger positionen för en kommentar på en bild. |
| [remove()](#remove--) | Tar bort kommentaren och alla dess svar från den överordnade samlingen. |
| [getParentComment()](#getParentComment--) | Hämtar eller anger föräldrakommentar. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Hämtar eller anger föräldrakommentar. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

Returnerar eller anger den rena texten för en bildkommentar. Läs/skriv String.

**Returnerar:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Returnerar eller anger den rena texten för en bildkommentar. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Returnerar eller anger tiden för en kommentarsskapelse. Att sätta denna egenskap till java.util.Date(Long.MIN_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentarstiden är en valfri parameter.

**Returnerar:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Returnerar eller anger tiden för en kommentarsskapelse. Att sätta denna egenskap till java.util.Date(Long.MIN_VALUE) betyder att ingen kommentarstid är angiven. Läs/skriv java.util.Date.

--------------------

Kommentarstiden är en valfri parameter.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Returnerar eller anger den överordnade bilden för en kommentar. Skrivskyddad [ISlide](../../com.aspose.slides/islide).

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Returnerar författaren till en kommentar. Skrivskyddad [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returnerar:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv android.graphics.PointF.

**Returnerar:**
android.graphics.PointF

### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Returnerar eller anger positionen för en kommentar på en bild. Läs/skriv android.graphics.PointF.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Tar bort kommentaren och alla dess svar från den överordnade samlingen.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Hämtar eller anger föräldrakommentar. Läs/skriv [IComment](../../com.aspose.slides/icomment).

**Returnerar:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Hämtar eller anger föräldrakommentar. Läs/skriv [IComment](../../com.aspose.slides/icomment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject