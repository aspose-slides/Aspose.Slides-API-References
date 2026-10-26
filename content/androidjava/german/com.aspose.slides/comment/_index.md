---
title: Comment
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Kommentar auf einer Folie dar.
type: docs
url: /de/com.aspose.slides/comment/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Stellt einen Kommentar auf einer Folie dar.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instanziert die Klasse Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Fügt eine leere Folie hinzu
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Fügt einen Autor hinzu
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Setzt die Position für Kommentare
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Fügt einen Folienkommentar für einen Autor auf Folie 1 hinzu
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Fügt einen Folienkommentar für einen Autor auf Folie 2 hinzu
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Speichert die PowerPoint-Präsentationsdatei
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instanziert die Klasse Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Iteriert über CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Iteriert über Kommentare
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
>  // Instanziert die Klasse Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Fügt einen Kommentar hinzu
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Fügt eine Antwort zu comment1 hinzu
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Fügt eine weitere Antwort zu comment1 hinzu
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Fügt eine Antwort auf die vorhandene Antwort hinzu
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Gibt die Kommentarthierarchie auf der Konsole aus
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
>      // Entfernt comment1 und alle Antworten darauf
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getText()](#getText--) | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. |
| [setText(String value)](#setText-java.lang.String-) | Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. |
| [getCreatedTime()](#getCreatedTime--) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. |
| [getAuthor()](#getAuthor--) | Gibt den Autor eines Kommentars zurück. |
| [getPosition()](#getPosition--) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. |
| [remove()](#remove--) | Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung. |
| [getParentComment()](#getParentComment--) | Gibt den übergeordneten Kommentar zurück oder legt ihn fest. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Gibt den übergeordneten Kommentar zurück oder legt ihn fest. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Gibt den Klartext eines Folienkommentars zurück oder legt ihn fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Festlegen dieser Eigenschaft auf java.util.Date(Long.MIN_VALUE) bedeutet, dass keine Kommentierungszeit festgelegt ist. Lesen/Schreiben java.util.Date.

--------------------

Die Kommentierungszeit ist ein optionaler Parameter.

**Rückgabe:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Gibt die Erstellungszeit eines Kommentars zurück oder legt sie fest. Das Festlegen dieser Eigenschaft auf java.util.Date(Long.MIN_VALUE) bedeutet, dass keine Kommentierungszeit festgelegt ist. Lesen/Schreiben java.util.Date.

--------------------

Die Kommentierungszeit ist ein optionaler Parameter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Gibt die übergeordnete Folie eines Kommentars zurück oder legt sie fest. Nur lesen [ISlide](../../com.aspose.slides/islide).

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Gibt den Autor eines Kommentars zurück. Nur lesen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Rückgabe:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben android.graphics.PointF.

**Rückgabe:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Gibt die Position eines Kommentars auf einer Folie zurück oder legt sie fest. Lesen/Schreiben android.graphics.PointF.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public final void remove()
```

Entfernt den Kommentar und alle seine Antworten aus der übergeordneten Sammlung.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Gibt den übergeordneten Kommentar zurück oder legt ihn fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Rückgabe:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Gibt den übergeordneten Kommentar zurück oder legt ihn fest. Lesen/Schreiben [IComment](../../com.aspose.slides/icomment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject