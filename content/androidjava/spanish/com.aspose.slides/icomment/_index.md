---
title: IComment
second_title: Referencia de API de Aspose.Slides para Android mediante Java
description: Representa un comentario en una diapositiva.
type: docs
url: /es/com.aspose.slides/icomment/
---```
public interface IComment
```

Representa un comentario en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getText()](#getText--) | Obtiene o establece el texto sin formato de un comentario de diapositiva. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto sin formato de un comentario de diapositiva. |
| [getCreatedTime()](#getCreatedTime--) | Obtiene o establece la hora de creación de un comentario. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Obtiene o establece la hora de creación de un comentario. |
| [getSlide()](#getSlide--) | Obtiene o establece la diapositiva principal de un comentario. |
| [getAuthor()](#getAuthor--) | Obtiene el autor de un comentario. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición de un comentario en una diapositiva. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Obtiene o establece la posición de un comentario en una diapositiva. |
| [remove()](#remove--) | Elimina el comentario y todas sus respuestas de la colección principal. |
| [getParentComment()](#getParentComment--) | Obtiene o establece el comentario padre. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtiene o establece el comentario padre. |
### getText() {#getText--}
```
public abstract String getText()
```

Obtiene o establece el texto sin formato de un comentario de diapositiva. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtiene o establece el texto sin formato de un comentario de diapositiva. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Obtiene o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN_VALUE) significa que no se ha fijado la hora del comentario. Lectura/escritura java.util.Date.

--------------------

La hora del comentario es un parámetro opcional.

**Devuelve:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Obtiene o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN_VALUE) significa que no se ha fijado la hora del comentario. Lectura/escritura java.util.Date.

--------------------

La hora del comentario es un parámetro opcional.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.util.Date |  |

### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Obtiene o establece la diapositiva principal de un comentario. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Obtiene el autor de un comentario. Solo lectura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Obtiene o establece la posición de un comentario en una diapositiva. Lectura/escritura android.graphics.PointF.

**Devuelve:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Obtiene o establece la posición de un comentario en una diapositiva. Lectura/escritura android.graphics.PointF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### remove() {#remove--}
```
public abstract void remove()
```

Elimina el comentario y todas sus respuestas de la colección principal.

### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Obtiene o establece el comentario padre. Lectura/escritura [IComment](../../com.aspose.slides/icomment).

**Devuelve:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Obtiene o establece el comentario padre. Lectura/escritura [IComment](../../com.aspose.slides/icomment).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |