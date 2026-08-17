---
title: Comment
second_title: Référence de l'API Aspose.Slides for Java
description: Représente un commentaire sur une diapositive.
type: docs
url: /fr/com.aspose.slides/comment/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject  
```
public class Comment implements IComment, IDOMObject
```

Représente un commentaire sur une diapositive.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instancie la classe Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Ajoute une diapositive vide
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Ajoute un auteur
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Définit la position des commentaires
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Ajoute un commentaire de diapositive pour un auteur sur la diapositive 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Ajoute un commentaire de diapositive pour un auteur sur la diapositive 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Enregistre le fichier de présentation PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instancie la classe Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Parcourt les CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Parcourt les commentaires
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
>  // Instancie la classe Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Ajoute un commentaire
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Ajoute une réponse au commentaire1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Ajoute une autre réponse au commentaire1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Ajoute une réponse à la réponse existante
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Affiche la hiérarchie des commentaires sur la console
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
>      // Supprime le commentaire1 et toutes ses réponses
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Renvoie ou définit le texte brut d'un commentaire de diapositive. |
| [setText(String value)](#setText-java.lang.String-) | Renvoie ou définit le texte brut d'un commentaire de diapositive. |
| [getCreatedTime()](#getCreatedTime--) | Renvoie ou définit le temps de création d'un commentaire. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Renvoie ou définit le temps de création d'un commentaire. |
| [getSlide()](#getSlide--) | Renvoie ou définit la diapositive parente d'un commentaire. |
| [getAuthor()](#getAuthor--) | Renvoie l'auteur d'un commentaire. |
| [getPosition()](#getPosition--) | Renvoie ou définit la position d'un commentaire sur une diapositive. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Renvoie ou définit la position d'un commentaire sur une diapositive. |
| [remove()](#remove--) | Supprime le commentaire et toutes ses réponses de la collection parente. |
| [getParentComment()](#getParentComment--) | Renvoie ou définit le commentaire parent. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Renvoie ou définit le commentaire parent. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String.

**Renvoie :**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Renvoie ou définit le texte brut d'un commentaire de diapositive. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Renvoie ou définit le temps de création d'un commentaire. Définir cette propriété sur java.util.Date(Long.MIN_VALUE) signifie qu'aucun temps de commentaire n'est défini. Lecture/écriture java.util.Date.

--------------------

Le temps du commentaire est un paramètre optionnel.

**Renvoie :**  
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Renvoie ou définit le temps de création d'un commentaire. Définir cette propriété sur java.util.Date(Long.MIN_VALUE) signifie qu'aucun temps de commentaire n'est défini. Lecture/écriture java.util.Date.

--------------------

Le temps du commentaire est un paramètre optionnel.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Renvoie ou définit la diapositive parente d'un commentaire. Lecture seule [ISlide](../../com.aspose.slides/islide).

**Renvoie :**  
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Renvoie l'auteur d'un commentaire. Lecture seule [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Renvoie :**  
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture java.awt.geom.Point2D.Float.

**Renvoie :**  
java.awt.geom.Point2D.Float

### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Renvoie ou définit la position d'un commentaire sur une diapositive. Lecture/écriture java.awt.geom.Point2D.Float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

Supprime le commentaire et toutes ses réponses de la collection parente.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Renvoie ou définit le commentaire parent. Lecture/écriture [IComment](../../com.aspose.slides/icomment).

**Renvoie :**  
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Renvoie ou définit le commentaire parent. Lecture/écriture [IComment](../../com.aspose.slides/icomment).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**  
com.aspose.slides.IDOMObject