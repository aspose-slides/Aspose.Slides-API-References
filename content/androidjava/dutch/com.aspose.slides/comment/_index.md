---
title: Comment
second_title: Aspose.Slides voor Android via Java API-referentie
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
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Voegt een diaopmerking toe voor een auteur op dia 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Voegt een diaopmerking toe voor een auteur op dia 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Sla het PowerPoint-presentatiebestand op
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
>          // Itereer over opmerkingen
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
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Voegt een antwoord toe aan comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Voegt een ander antwoord toe aan comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Voegt een antwoord toe aan bestaand antwoord
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
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
>      // Verwijdert comment1 en alle antwoorden daarop
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getText()](#getText--) | Retourneert of stelt de platte tekst van een diaopmerking in. |
| [setText(String value)](#setText-java.lang.String-) | Retourneert of stelt de platte tekst van een diaopmerking in. |
| [getCreatedTime()](#getCreatedTime--) | Retourneert of stelt de tijd van het maken van een opmerking in. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retourneert of stelt de tijd van het maken van een opmerking in. |
| [getSlide()](#getSlide--) | Retourneert of stelt de bovenliggende dia van een opmerking in. |
| [getAuthor()](#getAuthor--) | Retourneert de auteur van een opmerking. |
| [getPosition()](#getPosition--) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Retourneert of stelt de positie van een opmerking op een dia in. |
| [remove()](#remove--) | Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie. |
| [getParentComment()](#getParentComment--) | Haalt of stelt de bovenliggende opmerking op. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Haalt of stelt de bovenliggende opmerking op. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Retourneert of stelt de platte tekst van een diaopmerking in. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Retourneert of stelt de platte tekst van een diaopmerking in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Retourneert of stelt de tijd van het maken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/Schrijven java.util.Date.

--------------------

Opmerkingstijd is een optionele parameter.

**Retour:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Retourneert of stelt de tijd van het maken van een opmerking in. Het instellen van deze eigenschap op java.util.Date(Long.MIN\_VALUE) betekent dat er geen opmerkingstijd is ingesteld. Lezen/Schrijven java.util.Date.

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

**Retour:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Retourneert de auteur van een opmerking. Alleen-lezen [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Retour:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/Schrijven android.graphics.PointF.

**Retour:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Retourneert of stelt de positie van een opmerking op een dia in. Lezen/Schrijven android.graphics.PointF.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### remove() {#remove--}
```
public final void remove()
```

Verwijdert de opmerking en al zijn antwoorden uit de bovenliggende collectie.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Haalt of stelt de bovenliggende opmerking op. Lezen/Schrijven [IComment](../../com.aspose.slides/icomment).

**Retour:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Haalt of stelt de bovenliggende opmerking op. Lezen/Schrijven [IComment](../../com.aspose.slides/icomment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retourneert Parent\_Immediate object. Alleen-lezen IDOMObject.

**Retour:**
com.aspose.slides.IDOMObject