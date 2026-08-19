---
title: Comment
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje komentář na snímku.
type: docs
url: /cs/com.aspose.slides/comment/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject  
```
public class Comment implements IComment, IDOMObject
```

Represents a comment on a slide.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Vytváří instanci třídy Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Přidá prázdný snímek
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Přidá autora
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Nastaví pozici pro komentáře
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Přidá komentář ke snímku pro autora na snímku 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Přidá komentář ke snímku pro autora na snímku 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Uloží soubor PowerPoint prezentace
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Vytváří instanci třídy Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Iteruje CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Iteruje komentáře
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
>  // Vytváří instanci třídy Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Přidá komentář
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Přidá odpověď na comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Přidá další odpověď na comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Přidá odpověď na existující odpověď
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Zobrazí hierarchii komentářů v konzoli
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
>      // Odstraní comment1 a všechny odpovědi na něj
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

## Metody

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Vrací nebo nastavuje prostý text komentáře ke snímku. |
| [setText(String value)](#setText-java.lang.String-) | Vrací nebo nastavuje prostý text komentáře ke snímku. |
| [getCreatedTime()](#getCreatedTime--) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [getSlide()](#getSlide--) | Vrací nebo nastavuje nadřazený snímek komentáře. |
| [getAuthor()](#getAuthor--) | Vrací autora komentáře. |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje pozici komentáře na snímku. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Vrací nebo nastavuje pozici komentáře na snímku. |
| [remove()](#remove--) | Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce. |
| [getParentComment()](#getParentComment--) | Získá nebo nastaví nadřazený komentář. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Získá nebo nastaví nadřazený komentář. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Vrací nebo nastavuje prostý text komentáře ke snímku. Čtení/zápis String.

**Returns:**  
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Vrací nebo nastavuje prostý text komentáře ke snímku. Čtení/zápis String.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Vrací nebo nastavuje čas vytvoření komentáře. Nastavení této vlastnosti na java.util.Date(Long.MIN\_VALUE) znamená, že čas komentáře není nastaven. Čtení/zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Returns:**  
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Vrací nebo nastavuje čas vytvoření komentáře. Nastavení této vlastnosti na java.util.Date(Long.MIN\_VALUE) znamená, že čas komentáře není nastaven. Čtení/zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Vrací nebo nastavuje nadřazený snímek komentáře. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Returns:**  
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Vrací autora komentáře. Pouze pro čtení [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Vrací nebo nastavuje pozici komentáře na snímku. Čtení/zápis java.awt.geom.Point2D.Float.

**Returns:**  
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Vrací nebo nastavuje pozici komentáře na snímku. Čtení/zápis java.awt.geom.Point2D.Float.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public final void remove()
```

Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Získá nebo nastaví nadřazený komentář. Čtení/zápis [IComment](../../com.aspose.slides/icomment).

**Returns:**  
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Získá nebo nastaví nadřazený komentář. Čtení/zápis [IComment](../../com.aspose.slides/icomment).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Vrací objekt Parent\_Immediate. Pouze pro čtení IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject