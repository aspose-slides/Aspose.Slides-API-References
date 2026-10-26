---
title: ICommentCollection
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una colección de comentarios de un autor.
type: docs
url: /es/com.aspose.slides/icommentcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ICommentCollection extends IGenericCollection<IComment>
```

Representa una colección de comentarios de un autor.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addComment(String text, ISlide slide, PointF position, Date creationTime)](#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Añade un nuevo comentario al final de una colección. |
| [addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Añade un nuevo comentario moderno al final de una colección. |
| [insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)](#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-) | Inserta un nuevo comentario en una colección en el índice especificado. |
| [insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)](#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-) | Inserta un nuevo comentario moderno en una colección en el índice especificado. |
| [toArray()](#toArray--) | Crea y devuelve un array con todos los comentarios. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve un array con los comentarios del rango especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina el elemento en el índice especificado de una colección. |
| [remove(IComment comment)](#remove-com.aspose.slides.IComment-) | Elimina la primera aparición del comentario especificado en una colección. |
| [clear()](#clear--) | Elimina todos los comentarios de una colección. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IComment get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [IComment](../../com.aspose.slides/icomment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment)
### addComment(String text, ISlide slide, PointF position, Date creationTime) {#addComment-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment addComment(String text, ISlide slide, PointF position, Date creationTime)
```

Añade un nuevo comentario al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto plano de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde añadir un nuevo comentario. |
| position | android.graphics.PointF | Posición en una diapositiva donde añadir un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario añadido.
### addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#addModernComment-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment addModernComment(String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Añade un nuevo comentario moderno al final de una colección.

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
| text | java.lang.String | Texto plano de un nuevo comentario moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde añadir un nuevo comentario moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | android.graphics.PointF | Posición en una diapositiva donde añadir un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación del comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno añadido.
### insertComment(int index, String text, ISlide slide, PointF position, Date creationTime) {#insertComment-int-java.lang.String-com.aspose.slides.ISlide-android.graphics.PointF-java.util.Date-}
```
public abstract IComment insertComment(int index, String text, ISlide slide, PointF position, Date creationTime)
```

Inserta un nuevo comentario en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección en el que debe insertarse el comentario. |
| text | java.lang.String | Texto plano de un nuevo comentario. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde añadir un nuevo comentario. |
| position | android.graphics.PointF | Posición en una diapositiva donde añadir un nuevo comentario. |
| creationTime | java.util.Date | Hora de creación del comentario. |

**Devuelve:**
[IComment](../../com.aspose.slides/icomment) - Comentario insertado.
### insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime) {#insertModernComment-int-java.lang.String-com.aspose.slides.ISlide-com.aspose.slides.IShape-android.graphics.PointF-java.util.Date-}
```
public abstract IModernComment insertModernComment(int index, String text, ISlide slide, IShape shape, PointF position, Date creationTime)
```

Inserta un nuevo comentario moderno en una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento en una colección en el que debe insertarse el comentario moderno. |
| text | java.lang.String | Texto plano de un nuevo comentario moderno. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva en una presentación donde añadir un nuevo comentario moderno. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma en una diapositiva a la que se asocia un nuevo comentario moderno. |
| position | android.graphics.PointF | Posición en una diapositiva donde añadir un nuevo comentario moderno. |
| creationTime | java.util.Date | Hora de creación del comentario moderno. |

**Devuelve:**
[IModernComment](../../com.aspose.slides/imoderncomment) - Comentario moderno insertado.
### toArray() {#toArray--}
```
public abstract IComment[] toArray()
```

Crea y devuelve un array con todos los comentarios.

**Devuelve:**
com.aspose.slides.IComment[] - Array de [IComment](../../com.aspose.slides/icomment).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IComment[] toArray(int startIndex, int count)
```

Crea y devuelve un array con los comentarios del rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | Un índice del primer comentario a devolver. |
| count | int | Un número de comentarios a devolver. |

**Devuelve:**
com.aspose.slides.IComment[] - Array de [IComment](../../com.aspose.slides/icomment).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina el elemento en el índice especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero del elemento a eliminar. |

### remove(IComment comment) {#remove-com.aspose.slides.IComment-}
```
public abstract void remove(IComment comment)
```

Elimina la primera aparición del comentario especificado en una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| comment | [IComment](../../com.aspose.slides/icomment) | El comentario a eliminar de una colección. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los comentarios de una colección.