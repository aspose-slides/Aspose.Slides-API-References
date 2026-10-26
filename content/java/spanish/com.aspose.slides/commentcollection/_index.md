---
title: CommentCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de comentarios de un autor.
type: docs
url: /es/com.aspose.slides/commentcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Representa una colección de comentarios de un autor.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Obtiene el número de elementos realmente contenidos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Agrega un nuevo comentario al final de una colección. |
| [addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Agrega un nuevo comentario moderno al final de una colección. |
| [insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [toArray()](#toArray--) | Crea y devuelve un arreglo con todos los comentarios. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve un arreglo con todos los comentarios del rango especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de una colección. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Elimina la primera aparición del comentario especificado en una colección. |
| [clear()](#clear--) | Elimina todos los comentarios de una colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Busca un comentario en la colección por índice. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia todos los elementos de la colección al arreglo especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
### size() {#size--}
```
public final int size()
```

Obtiene el número de elementos realmente contenidos en la colección. Solo lectura  int .

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IComment get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [Comment](../../com.aspose.slides/comment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, Point2D.Float position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Agrega un nuevo comentario al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto sin formato de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario. |
| position | java.awt.geom.Point2D.Float | Posición en una diapositiva donde agregar un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario añadido.
### addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Agrega un nuevo comentario moderno al final de una colección.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto sin formato de un nuevo comentario moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | java.awt.geom.Point2D.Float | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación de un comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno añadido.
### insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, Point2D.Float position, Date creationTime)
```

Inserta un nuevo comentario en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección en el que se debe insertar el comentario. |
| text | java.lang.String | Texto sin formato de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario. |
| position | java.awt.geom.Point2D.Float | Posición en una diapositiva donde agregar un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario insertado.
### insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-java.awt.geom.Point2D.Float-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, Point2D.Float position, Date creationTime)
```

Inserta un nuevo comentario moderno en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección en el que se debe insertar el comentario moderno. |
| text | java.lang.String | Texto sin formato de un nuevo comentario moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | java.awt.geom.Point2D.Float | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación del comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno insertado.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Crea y devuelve un arreglo con todos los comentarios.

**Devuelve:**
com.aspose.slides.IComment[] - Arreglo de [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Crea y devuelve un arreglo con todos los comentarios del rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Índice del primer comentario a devolver. |
| count | int | Número de comentarios a devolver. |

**Devuelve:**
com.aspose.slides.IComment[] - Arreglo de [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |
### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Elimina la primera aparición del comentario especificado en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | El comentario a eliminar de una colección. |
### clear() {#clear--}
```
public final void clear()
```

Elimina todos los comentarios de una colección.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un java.util.Iterator para toda la colección.
### findCommentByIdx(int idx) {#findCommentByIdx-int-}
```
public final IComment findCommentByIdx(int idx)
```

Busca un comentario en la colección por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| idx | int | Índice único de un comentario a buscar  int . |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario encontrado o null [IComment](../../com.aspose.slides/icomment).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia todos los elementos de la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Arreglo objetivo. |
| index | int | Índice inicial en el arreglo objetivo. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura  boolean .

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo lectura  Object .

**Devuelve:**
java.lang.Object