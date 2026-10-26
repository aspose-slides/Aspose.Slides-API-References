---
title: Comment
second_title: Aspose.Slides Java API Referenciája
description: Egy diára vonatkozó megjegyzést reprezentál.
type: docs
url: /hu/com.aspose.slides/comment/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Egy diára adott megjegyzést reprezentál.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Létrehozza a Presentation osztályt
>  Presentation presentation = new Presentation();
>  try {
>     // Üres diát ad hozzá
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Szerzőt ad hozzá
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Beállítja a megjegyzések pozícióját
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Szerzőnek diára 1 megjegyzést ad hozzá
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Szerzőnek diára 2 megjegyzést ad hozzá
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Mentés a PowerPoint prezentáció fájlba
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Létrehozza a Presentation osztályt
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Végigiterál a CommentAuthors-on
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Végigiterál a Comments-on
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
>  // Létrehozza a Presentation osztályt
>  Presentation pres = new Presentation();
>  try {
>     // Megjegyzést ad hozzá
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Válasz hozzáadása a comment1-hez
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Másik válasz hozzáadása a comment1-hez
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Válasz hozzáadása a meglévő válaszhoz
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Kiírja a megjegyzések hierarchiáját a konzolra
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
>      // Törli a comment1-et és minden hozzá tartozó választ
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getText()](#getText--) | Visszaadja vagy beállítja a diamegjegyzés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Visszaadja vagy beállítja a diamegjegyzés egyszerű szövegét. |
| [getCreatedTime()](#getCreatedTime--) | Visszaadja vagy beállítja a megjegyzés létrehozásának idejét. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Visszaadja vagy beállítja a megjegyzés létrehozásának idejét. |
| [getSlide()](#getSlide--) | Visszaadja vagy beállítja a megjegyzés szülő diáját. |
| [getAuthor()](#getAuthor--) | Visszaadja a megjegyzés szerzőjét. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a megjegyzés pozícióját a dián. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Visszaadja vagy beállítja a megjegyzés pozícióját a dián. |
| [remove()](#remove--) | Eltávolítja a megjegyzést és minden válaszát a szülőgyűjteményből. |
| [getParentComment()](#getParentComment--) | Lekérdezi vagy beállítja a szülő megjegyzést. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Lekérdezi vagy beállítja a szülő megjegyzést. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Visszaadja vagy beállítja a diamegjegyzés egyszerű szövegét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Visszaadja vagy beállítja a diamegjegyzés egyszerű szövegét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Visszaadja vagy beállítja egy megjegyzés létrehozásának idejét. Ennek beállítása a java.util.Date(Long.MIN_VALUE) értékre azt jelenti, hogy nincs megjegyzési idő beállítva. Olvasás/írás java.util.Date.

--------------------

A megjegyzés időpontja opcionális paraméter.

**Visszatérési érték:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Visszaadja vagy beállítja egy megjegyzés létrehozásának idejét. Ennek beállítása a java.util.Date(Long.MIN_VALUE) értékre azt jelenti, hogy nincs megjegyzési idő beállítva. Olvasás/írás java.util.Date.

--------------------

A megjegyzés időpontja opcionális paraméter.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Visszaadja vagy beállítja a megjegyzés szülő diáját. Csak olvasható [ISlide](../../com.aspose.slides/islide).

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Visszaadja a megjegyzés szerzőjét. Csak olvasható [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Visszatérési érték:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Visszaadja vagy beállítja egy megjegyzés pozícióját a dián. Olvasás/írás java.awt.geom.Point2D.Float.

**Visszatérési érték:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Visszaadja vagy beállítja egy megjegyzés pozícióját a dián. Olvasás/írás java.awt.geom.Point2D.Float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

Eltávolítja a megjegyzést és minden válaszát a szülőgyűjteményből.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Lekérdezi vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Visszatérési érték:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Lekérdezi vagy beállítja a szülő megjegyzést. Olvasás/írás [IComment](../../com.aspose.slides/icomment).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject