---
title: Comment
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un comentario en una diapositiva.
type: docs
url: /es/com.aspose.slides/comment/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Representa un comentario en una diapositiva.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instancia la clase Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Añade una diapositiva vacía
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Añade un autor
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Establece la posición para los comentarios
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Añade un comentario de diapositiva para un autor en la diapositiva 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Añade un comentario de diapositiva para un autor en la diapositiva 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Guarda el archivo de presentación PowerPoint
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instancia la clase Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Itera CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Itera Comments
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
>  // Instancia la clase Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Añade un comentario
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Añade una respuesta al comentario1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Añade otra respuesta al comentario1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Añade una respuesta a la respuesta existente
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Muestra la jerarquía de comentarios en la consola
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
>      // Elimina comment1 y todas sus respuestas
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Devuelve o establece el texto sin formato de un comentario en una diapositiva. |
| [setText(String value)](#setText-java.lang.String-) | Devuelve o establece el texto sin formato de un comentario en una diapositiva. |
| [getCreatedTime()](#getCreatedTime--) | Devuelve o establece la hora de creación de un comentario. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Devuelve o establece la hora de creación de un comentario. |
| [getSlide()](#getSlide--) | Devuelve o establece la diapositiva principal de un comentario. |
| [getAuthor()](#getAuthor--) | Devuelve el autor de un comentario. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición de un comentario en una diapositiva. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Devuelve o establece la posición de un comentario en una diapositiva. |
| [remove()](#remove--) | Elimina el comentario y todas sus respuestas de la colección principal. |
| [getParentComment()](#getParentComment--) | Obtiene o establece el comentario principal. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtiene o establece el comentario principal. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getText() {#getText--}
```
public final String getText()
```


Devuelve o establece el texto sin formato de un comentario en una diapositiva. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Devuelve o establece el texto sin formato de un comentario en una diapositiva. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```


Devuelve o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN\_VALUE) significa que no se ha establecido la hora del comentario. Lectura/escritura java.util.Date.

--------------------

El tiempo del comentario es un parámetro opcional.

**Devuelve:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```


Devuelve o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN\_VALUE) significa que no se ha establecido la hora del comentario. Lectura/escritura java.util.Date.

--------------------

El tiempo del comentario es un parámetro opcional.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```


Devuelve o establece la diapositiva principal de un comentario. Sólo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```


Devuelve el autor de un comentario. Sólo lectura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```


Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```


Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```


Elimina el comentario y todas sus respuestas de la colección principal.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```


Obtiene o establece el comentario principal. Lectura/escritura [IComment](../../com.aspose.slides/icomment).

**Devuelve:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```


Obtiene o establece el comentario principal. Lectura/escritura [IComment](../../com.aspose.slides/icomment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


Devuelve el objeto Parent_Immediate. Sólo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject