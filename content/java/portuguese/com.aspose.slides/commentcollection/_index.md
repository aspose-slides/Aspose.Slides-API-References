---
title: CommentCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de comentários de um autor.
type: docs
url: /pt/com.aspose.slides/commentcollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Representa uma coleção de comentários de um autor.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Obtém o número de elementos realmente contidos na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Adiciona um novo comentário no final de uma coleção. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Adiciona um novo comentário moderno no final de uma coleção. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Insere um novo comentário em uma coleção no índice especificado. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Insere um novo comentário moderno em uma coleção no índice especificado. |
| [toArray()](#toArray--) | Cria e retorna um array com todos os comentários. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Cria e retorna um array com todos os comentários do intervalo especificado. |
| [removeAt(int index)](#removeAt-int-) | Remove o elemento no índice especificado em uma coleção. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Remove a primeira ocorrência do comentário especificado em uma coleção. |
| [clear()](#clear--) | Remove todos os comentários de uma coleção. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Encontra um comentário na coleção pelo índice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos os elementos da coleção para o array especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
### size() {#size--}
```
public final int size()
```


Obtém o número de elementos realmente contidos na coleção. Somente leitura  int .

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [Comment](../../com.aspose.slides/comment).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Adiciona um novo comentário no final de uma coleção.

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
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Adiciona um novo comentário moderno no final de uma coleção.

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
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```


Insere um novo comentário em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento na coleção onde o comentário deve ser inserido. |
| text | java.lang.String | Texto simples de um novo comentário. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário. |
| creationTime | java.util.Date | Hora da criação do comentário. |

**Retorna:**
[IComment](../../com.aspose.slides/icomment) - Comentário inserido.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```


Insere um novo comentário moderno em uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento na coleção onde o comentário moderno deve ser inserido. |
| text | java.lang.String | Texto simples de um novo comentário moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide em uma apresentação onde adicionar um novo comentário moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma em um slide à qual um novo comentário moderno está associado. |
| position | java.awt.geom.Point2D.Float | Posição em um slide onde adicionar um novo comentário moderno. |
| creationTime | java.util.Date | Hora da criação do comentário moderno. |

**Retorna:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentário moderno inserido.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```


Cria e retorna um array com todos os comentários.

**Retorna:**
com.aspose.slides.IComment[] - Array de [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```


Cria e retorna um array com todos os comentários do intervalo especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| startIndex | int | Índice do primeiro comentário a ser retornado. |
| count | int | Número de comentários a serem retornados. |

**Retorna:**
com.aspose.slides.IComment[] - Array de [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove o elemento no índice especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | O índice baseado em zero do elemento a ser removido. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```


Remove a primeira ocorrência do comentário especificado em uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | O comentário a ser removido da coleção. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os comentários de uma coleção.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Um java.util.Iterator para toda a coleção.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```


Encontra um comentário na coleção pelo índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| idx | int | Índice único de um comentário a ser encontrado  int . |

**Retorna:**
[IComment](../../com.aspose.slides/icomment) - Comentário encontrado ou null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia todos os elementos da coleção para o array especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array de destino. |
| index | int | Índice inicial no array de destino. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). Somente leitura  boolean .

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna a raiz de sincronização. Somente leitura  Object .

**Retorna:**
java.lang.Object