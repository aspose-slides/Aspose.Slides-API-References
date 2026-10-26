---
title: Comment
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un commento su una diapositiva.
type: docs
url: /it/com.aspose.slides/comment/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Rappresenta un commento su una diapositiva.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Istanzia la classe Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Aggiunge una diapositiva vuota
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Aggiunge un autore
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Imposta la posizione per i commenti
>      android.graphics.PointF point = new android.graphics.PointF();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Aggiunge un commento alla diapositiva per un autore sulla diapositiva 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Aggiunge un commento alla diapositiva per un autore sulla diapositiva 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Salva il file PowerPoint Presentation
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Istanzia la classe Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Itera i CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Itera i Commenti
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
>  // Istanzia la classe Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Aggiunge un commento
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      // Aggiunge una risposta al commento1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Aggiunge un'altra risposta al commento1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Aggiunge una risposta a una risposta esistente
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new android.graphics.PointF(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Visualizza la gerarchia dei commenti sulla console
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
>      // Rimuove commento1 e tutte le risposte ad esso
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Restituisce o imposta il testo semplice di un commento su una diapositiva. |
| [setText(String value)](#setText-java.lang.String-) | Restituisce o imposta il testo semplice di un commento su una diapositiva. |
| [getCreatedTime()](#getCreatedTime--) | Restituisce o imposta l'ora di creazione di un commento. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Restituisce o imposta l'ora di creazione di un commento. |
| [getSlide()](#getSlide--) | Restituisce o imposta la diapositiva principale di un commento. |
| [getAuthor()](#getAuthor--) | Restituisce l'autore di un commento. |
| [getPosition()](#getPosition--) | Restituisce o imposta la posizione di un commento su una diapositiva. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Restituisce o imposta la posizione di un commento su una diapositiva. |
| [remove()](#remove--) | Rimuove il commento e tutte le sue risposte dalla collezione principale. |
| [getParentComment()](#getParentComment--) | Ottiene o imposta il commento principale. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Ottiene o imposta il commento principale. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```

Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/Scrittura String.

**Restituisce:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Restituisce o imposta il testo semplice di un commento su una diapositiva. Lettura/Scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Restituisce o imposta l'ora di creazione di un commento. Impostare questa proprietà a java.util.Date(Long.MIN_VALUE) indica che non è impostata alcuna ora del commento. Lettura/Scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Restituisce:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Restituisce o imposta l'ora di creazione di un commento. Impostare questa proprietà a java.util.Date(Long.MIN_VALUE) indica che non è impostata alcuna ora del commento. Lettura/Scrittura java.util.Date.

--------------------

Il tempo del commento è un parametro opzionale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Restituisce o imposta la diapositiva principale di un commento. Sola lettura [ISlide](../../com.aspose.slides/islide).

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Restituisce l'autore di un commento. Sola lettura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Restituisce:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final PointF getPosition()
```

Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/Scrittura android.graphics.PointF.

**Restituisce:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public final void setPosition(PointF value)
```

Restituisce o imposta la posizione di un commento su una diapositiva. Lettura/Scrittura android.graphics.PointF.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public final void remove()
```

Rimuove il commento e tutte le sue risposte dalla collezione principale.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Ottiene o imposta il commento principale. Lettura/Scrittura [IComment](../../com.aspose.slides/icomment).

**Restituisce:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Ottiene o imposta il commento principale. Lettura/Scrittura [IComment](../../com.aspose.slides/icomment).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject