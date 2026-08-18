---
title: ICommentCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de comentários de um autor.
type: docs
url: /pt/com.aspose.slides/icommentcollection/
---
**Todas as interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Representa uma coleção de comentários de um autor.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Adiciona um novo comentário ao final de uma coleção. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Adiciona um novo comentário moderno ao final de uma coleção. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Insere um novo comentário em uma coleção no índice especificado. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Insere um novo comentário moderno em uma coleção no índice especificado. |
| [toArray()](#toArray--) | Cria e retorna um array com todos os comentários. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array com todos os comentários do intervalo especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado em uma coleção. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Remove a primeira ocorrência do comentário especificado em uma coleção. |
| [clear()](#clear--) | Remove todos os comentários de uma coleção. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IComment](../../com.aspose.slides/icomment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Adiciona um novo comentário ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto simples de um novo comentário. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário. |
| creationTime | java.util.Date | Hora da criação do comentário. |

**Retorna:**
[IComment](../../com.aspose.slides/icomment) - Comentário adicionado.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Adiciona um novo comentário moderno ao final de uma coleção.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new Point2D.Float(100, 100), new Date());
>      pres.save(outPptxFileName, SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto simples de um novo comentário moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma em um slide à qual um novo comentário moderno está associado. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário moderno. |
| creationTime | java.util.Date | Hora da criação do comentário moderno. |

**Retorna:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentário moderno adicionado.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Insere um novo comentário em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento em uma coleção no qual o comentário deve ser inserido. |
| text | java.lang.String | Texto simples de um novo comentário. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário. |
| creationTime | java.util.Date | Hora da criação do comentário. |

**Retorna:**
[IComment](../../com.aspose.slides/icomment) - Comentário inserido.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Insere um novo comentário moderno em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento em uma coleção no qual o comentário moderno deve ser inserido. |
| text | java.lang.String | Texto simples de um novo comentário moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma em um slide à qual um novo comentário moderno está associado. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário moderno. |
| creationTime | java.util.Date | Hora da criação do comentário moderno. |

**Retorna:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentário moderno inserido.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Cria e retorna um array com todos os comentários.

**Retorna:**
com.aspose.slides.IComment[] - Array de [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Cria e retorna um array com todos os comentários do intervalo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Um índice do primeiro comentário a ser retornado. |
| count | int | Um número de comentários a ser retornado. |

**Retorna:**
com.aspose.slides.IComment[] - Array de [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Remove o elemento no índice especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Remove a primeira ocorrência do comentário especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | O comentário a ser removido de uma coleção. |
### clear() {#clear--}
```
public abstract void clear()
```

Remove todos os comentários de uma coleção.