---
title: CommentCollection
second_title: Referencia de la API de Aspose.Slides para Android vía Java
description: Representa una colección de comentarios de un autor.
type: docs
url: /es/com.aspose.slides/commentcollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ICommentCollection](../../com.aspose.slides/icommentcollection)
```
public final class CommentCollection extends DomObject<CommentAuthor> implements ICommentCollection
```

Representa una colección de comentarios de un autor.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Add new comment at the end of a collection. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Add new modern comment at the end of a collection. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Insert new comment to a collection at the specified index. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Insert new modern comment to a collection at the specified index. |
| [toArray()](#toArray--) | Creates and returns an array with all comments. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all comments from the specified range. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index in a collection. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Removes the first occurrence of the specified comment in a collection. |
| [clear()](#clear--) | Removes all comments from a collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [findCommentByIdx(int idx)](#findCommentByIdx-int-) | Finds a comment in the collection by index. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
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
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Agrega un nuevo comentario al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto sin formato de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario. |
| position | android.graphics.PointF | Posición en una diapositiva donde agregar un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario agregado.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Agrega un nuevo comentario moderno al final de una colección.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ICommentAuthor newAuthor = pres.getCommentAuthors().addAuthor("Some Author", "SA");
>      newAuthor.getComments().addModernComment("This is modern comment", pres.getSlides().get_Item(0), null, new android.graphics.PointF(100, 100), new Date());
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
| position | android.graphics.PointF | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación del comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno agregado.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public final IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Inserta un nuevo comentario en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección donde se debe insertar el comentario. |
| text | java.lang.String | Texto sin formato de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario. |
| position | android.graphics.PointF | Posición en una diapositiva donde agregar un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario insertado.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public final IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Inserta un nuevo comentario moderno en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección donde se debe insertar el comentario moderno. |
| text | java.lang.String | Texto sin formato de un nuevo comentario moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde agregar un nuevo comentario moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | android.graphics.PointF | Posición en una diapositiva donde agregar un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación del comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno insertado.
### toArray() {#toArray--}
```
public final IComment[] toArray()
```

Crea y devuelve una matriz con todos los comentarios.

**Devuelve:**
com.aspose.slides.IComment[] - Matriz de [Comment](../../com.aspose.slides/comment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IComment[] toArray(int startIndex, int count)
```

Crea y devuelve una matriz con todos los comentarios del rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Un índice del primer comentario a devolver. |
| count | int | Un número de comentarios a devolver. |

**Devuelve:**
com.aspose.slides.IComment[] - Matriz de [Comment](../../com.aspose.slides/comment).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina el elemento en el índice especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice base cero del elemento a eliminar. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public final void remove(IComment comment)
```

Elimina la primera ocurrencia del comentario especificado en una colección.

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

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IComment> - Un IGenericEnumerator que se puede usar para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IComment> iteratorJava()
```

Devuelve un java iterator para toda la colección.

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
[IComment](../../com.aspose.slides/icomment) - Comentario encontrado o nulo [IComment](../../com.aspose.slides/icomment).
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

Devuelve la raíz de sincronización. Solo lectura  Object .

**Devuelve:**
java.lang.Object