---
title: Comment
second_title: Aspose.Slides pro Android přes referenci Java API
description: Představuje komentář na snímku.
type: docs
url: /cs/com.aspose.slides/comment/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Představuje komentář na snímku.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Vytvoří instanci třídy Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Přidá prázdný snímek
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Přidá autora
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Nastaví pozici pro komentáře
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Přidá komentář na snímek pro autora na snímek 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Přidá komentář na snímek pro autora na snímek 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Uloží soubor PowerPoint prezentace
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Vytvoří instanci třídy Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Procházet CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Procházet Comments
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
>  // Vytvoří instanci třídy Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Přidá komentář
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Přidá odpověď k comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Přidá další odpověď k comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Přidá odpověď k existující odpovědi
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
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
>      // Odebere comment1 a všechny odpovědi k němu
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getText()](#getText--) | Vrací nebo nastavuje prostý text komentáře na snímku. |
| [setText(String value)](#setText-java.lang.String-) | Vrací nebo nastavuje prostý text komentáře na snímku. |
| [getCreatedTime()](#getCreatedTime--) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Vrací nebo nastavuje čas vytvoření komentáře. |
| [getSlide()](#getSlide--) | Vrací nebo nastavuje nadřazený snímek komentáře. |
| [getAuthor()](#getAuthor--) | Vrací autora komentáře. |
| [getPosition()](#getPosition--) | Vrací nebo nastavuje pozici komentáře na snímku. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Vrací nebo nastavuje pozici komentáře na snímku. |
| [remove()](#remove--) | Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce. |
| [getParentComment()](#getParentComment--) | Získá nebo nastaví nadřazený komentář. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Získá nebo nastaví nadřazený komentář. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Vrací nebo nastavuje prostý text komentáře na snímku. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Vrací nebo nastavuje prostý text komentáře na snímku. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Vrací nebo nastavuje čas vytvoření komentáře. Nastavením této vlastnosti na java.util.Date(Long.MIN_VALUE) znamená, že čas komentáře není nastaven. Čtení/Zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Vrací:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Vrací nebo nastavuje čas vytvoření komentáře. Nastavením této vlastnosti na java.util.Date(Long.MIN_VALUE) znamená, že čas komentáře není nastaven. Čtení/Zápis java.util.Date.

--------------------

Čas komentáře je volitelný parametr.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Vrací nebo nastavuje nadřazený snímek komentáře. Pouze pro čtení [ISlide](../../com.aspose.slides/islide).

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Vrací autora komentáře. Pouze pro čtení [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Vrací:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Vrací nebo nastavuje pozici komentáře na snímku. Čtení/Zápis android.graphics.PointF.

**Vrací:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Vrací nebo nastavuje pozici komentáře na snímku. Čtení/Zápis android.graphics.PointF.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Odstraní komentář a všechny jeho odpovědi z nadřazené kolekce.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Získá nebo nastaví nadřazený komentář. Čtení/Zápis [IComment](../../com.aspose.slides/icomment).

**Vrací:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Získá nebo nastaví nadřazený komentář. Čtení/Zápis [IComment](../../com.aspose.slides/icomment).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject