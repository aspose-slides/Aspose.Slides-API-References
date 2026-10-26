---
title: Comment
second_title: Referência da API Aspose.Slides para Java
description: Representa um comentário em um slide.
type: docs
url: /pt/com.aspose.slides/comment/
---
**Herança:**
java.lang.Object

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IComment](../../com.aspose.slides/icomment), com.aspose.slides.IDOMObject
```
public class Comment implements IComment, IDOMObject
```

Representa um comentário em um slide.

--------------------

> ```
> This example shows you how to add a comment to a slide in a PowerPoint presentation.
>  
>  // Instancia a classe Presentation
>  Presentation presentation = new Presentation();
>  try {
>     // Adiciona um slide vazio
>      presentation.getSlides().addEmptySlide(presentation.getLayoutSlides().get_Item(0));
>      // Adiciona um autor
>      ICommentAuthor author = presentation.getCommentAuthors().addAuthor("Jawad", "MF");
>      // Define a posição dos comentários
>      Point2D.Float point = new Point2D.Float();
>      point.x = 0.2f;
>      point.y = 0.2f;
>      // Adiciona comentário de slide para um autor no slide 1
>      author.getComments().addComment("Hello Jawad, this is slide comment", presentation.getSlides().get_Item(0), point, new Date());
>      // Adiciona comentário de slide para um autor no slide 2
>      author.getComments().addComment("Hello Jawad, this is second slide comment", presentation.getSlides().get_Item(1), point, new Date());
>  	// Salva o arquivo PowerPoint Presentation file
>      presentation.save("Comments_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  This example shows you how to access an existing comment on a slide in a PowerPoint presentation.
>  
>  // Instancia a classe Presentation
>  Presentation presentation = new Presentation("Comments1.pptx");
>  try {
>      // Itera pelos CommentAuthors
>      for (ICommentAuthor commentAuthor : presentation.getCommentAuthors())
>      {
>          CommentAuthor author = (CommentAuthor) commentAuthor;
>          // Itera pelos Comentários
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
>  // Instancia a classe Presentation
>  Presentation pres = new Presentation();
>  try {
>     // Adiciona um comentário
>      ICommentAuthor author1 = pres.getCommentAuthors().addAuthor("Author_1", "A.A.");
>      IComment comment1 = author1.getComments().addComment("comment1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      // Adiciona uma resposta ao comment1
>      ICommentAuthor author2 = pres.getCommentAuthors().addAuthor("Autror_2", "B.B.");
>      IComment reply1 = author2.getComments().addComment("reply 1 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply1.setParentComment(comment1);
>      // Adiciona outra resposta ao comment1
>      IComment reply2 = author2.getComments().addComment("reply 2 for comment 1", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply2.setParentComment(comment1);
>      // Adiciona uma resposta a uma resposta existente
>      IComment subReply = author1.getComments().addComment("subreply 3 for reply 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      subReply.setParentComment(reply2);
>      IComment comment2 = author2.getComments().addComment("comment 2", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment comment3 = author2.getComments().addComment("comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      IComment reply3 = author1.getComments().addComment("reply 4 for comment 3", pres.getSlides().get_Item(0), new Point2D.Float(10, 10), new Date());
>      reply3.setParentComment(comment3);
>      // Exibe a hierarquia de comentários no console
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
>      // Remove o comment1 e todas as respostas dele
>      comment1.remove();
>      pres.save("remove_comment.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Métodos

| Método | Descrição |
| --- | --- |
| [getText()](#getText--) | Retorna ou define o texto simples de um comentário de slide. |
| [setText(String value)](#setText-java.lang.String-) | Retorna ou define o texto simples de um comentário de slide. |
| [getCreatedTime()](#getCreatedTime--) | Retorna ou define o horário de criação de um comentário. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Retorna ou define o horário de criação de um comentário. |
| [getSlide()](#getSlide--) | Retorna ou define o slide pai de um comentário. |
| [getAuthor()](#getAuthor--) | Retorna o autor de um comentário. |
| [getPosition()](#getPosition--) | Retorna ou define a posição de um comentário em um slide. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Retorna ou define a posição de um comentário em um slide. |
| [remove()](#remove--) | Remove o comentário e todas as suas respostas da coleção pai. |
| [getParentComment()](#getParentComment--) | Obtém ou define o comentário pai. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtém ou define o comentário pai. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getText() {#getText--}
```
public final String getText()
```

Retorna ou define o texto simples de um comentário de slide. Leitura/gravação String.

**Retorna:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Retorna ou define o texto simples de um comentário de slide. Leitura/gravação String.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```

Retorna ou define o horário de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhum horário de comentário está definido. Leitura/gravação java.util.Date.

--------------------

O horário do comentário é um parâmetro opcional.

**Retorna:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Retorna ou define o horário de criação de um comentário. Definir esta propriedade para java.util.Date(Long.MIN\_VALUE) significa que nenhum horário de comentário está definido. Leitura/gravação java.util.Date.

--------------------

O horário do comentário é um parâmetro opcional.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public final ISlide getSlide()
```

Retorna ou define o slide pai de um comentário. Somente leitura [ISlide](../../com.aspose.slides/islide).

**Retorna:**
[ISlide](../../com.aspose.slides/islide)

### getAuthor() {#getAuthor--}
```
public final ICommentAuthor getAuthor()
```

Retorna o autor de um comentário. Somente leitura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Retorna:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)

### getPosition() {#getPosition--}
```
public final Point2D.Float getPosition()
```

Retorna ou define a posição de um comentário em um slide. Leitura/gravação java.awt.geom.Point2D.Float.

**Retorna:**
java.awt.geom.Point2D.Float

### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public final void setPosition(Point2D.Float value)
```

Retorna ou define a posição de um comentário em um slide. Leitura/gravação java.awt.geom.Point2D.Float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### remove() {#remove--}
```
public final void remove()
```

Remove o comentário e todas as suas respostas da coleção pai.

### getParentComment() {#getParentComment--}
```
public final IComment getParentComment()
```

Obtém ou define o comentário pai. Leitura/gravação [IComment](../../com.aspose.slides/icomment).

**Retorna:**
[IComment](../../com.aspose.slides/icomment)

### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public final void setParentComment(IComment value)
```

Obtém ou define o comentário pai. Leitura/gravação [IComment](../../com.aspose.slides/icomment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Retorna o objeto Parent_Immediate. Somente leitura IDOMObject.

**Retorna:**
com.aspose.slides.IDOMObject