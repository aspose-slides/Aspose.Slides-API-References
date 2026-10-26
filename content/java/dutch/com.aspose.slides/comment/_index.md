---
title: Comment
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een opmerking op een dia voor.
type: docs
url: /nl/com.aspose.slides/comment/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Stelt een opmerking op een dia voor.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instantieert de Presentation-klasse
>  Presentation presentation = new Presentation();
>  try {
>     // Voegt een lege dia toe
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Voegt een auteur toe
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Stelt de positie voor opmerkingen in
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Voegt een dia-opmerking toe voor een auteur op dia 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Voegt een dia-opmerking toe voor een auteur op dia 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Slaat het PowerPoint-presentatiebestand op
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instantieert de Presentation-klasse
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Itereer over CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Itereer over Comments
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
>  // Instantieert de Presentation-klasse
>  Presentation pres = new Presentation();
>  try {
>     // Voegt een opmerking toe
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Voegt een antwoord toe aan comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Voegt een ander antwoord toe aan comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Voegt een antwoord toe aan een bestaande reactie
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Toont de hiërarchie van opmerkingen op de console
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
>      // Verwijdert comment1 en alle antwoorden erop
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) | Retourneert of stelt de platte tekst van een dia-opmerking in. |
| [setText(String value)](#setText-java.lang.String-) | Retourneert of stelt de platte tekst van een dia-opmerking in. |
| [getCreatedTime()](#getCreatedTime--) | Retourneert of stelt de tijd van een opmerkingcreatie in. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert of stelt de tijd van een opmerkingcreatie in. |
| [getSlide()](#getSlide--) | Retourneert of stelt de bovenliggende dia van een opmerking in. |
| [getAuthor()](#getAuthor--) | Retourneert de auteur van een opmerking. |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [remove()](#remove--) | Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie. |
| [getParentComment()](#getParentComment--) | Haalt op of stelt bovenliggende opmerking in. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Haalt op of stelt bovenliggende opmerking in. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Retourneert of stelt de platte tekst van een dia-opmerking in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Retourneert of stelt de tijd van een opmerkingcreatie in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Retourneert:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Retourneert of stelt de tijd van een opmerkingcreatie in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


Retourneert of stelt de bovenliggende dia van een opmerking in. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


Retourneert de auteur van een opmerking. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Retourneert:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```


Retourneert of stelt de positie van een opmerking op een dia in. Lezen/schrijven java.awt.geom.Point2D.Float.

**Retourneert:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```


Retourneert of stelt de positie van een opmerking op een dia in. Lezen/schrijven java.awt.geom.Point2D.Float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```


Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


Haalt op of stelt bovenliggende opmerking in. Lezen/schrijven [IComment](../../com.aspose.slides/icomment).

**Retourneert:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


Haalt op of stelt bovenliggende opmerking in. Lezen/schrijven [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Retourneert Parent\_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject