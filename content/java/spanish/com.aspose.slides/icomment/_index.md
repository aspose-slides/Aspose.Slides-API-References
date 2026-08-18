---
title: IComment
second_title: Aspose.Slides para Java Referencia de API
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
| [getText()](#getText--) | Devuelve o establece el texto sin formato de un comentario de diapositiva. |
| [setText(String value)](#setText-java.lang.String-) | Devuelve o establece el texto sin formato de un comentario de diapositiva. |
| [getCreatedTime()](#getCreatedTime--) | Devuelve o establece la hora de creación de un comentario. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Devuelve o establece la hora de creación de un comentario. |
| [getSlide()](#getSlide--) | Devuelve o establece la diapositiva principal de un comentario. |
| [getAuthor()](#getAuthor--) | Devuelve el autor de un comentario. |
| [getPosition()](#getPosition--) | Devuelve o establece la posición de un comentario en una diapositiva. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Devuelve o establece la posición de un comentario en una diapositiva. |
| [remove()](#remove--) | Elimina el comentario y todas sus respuestas de la colección principal. |
| [getParentComment()](#getParentComment--) | Obtiene o establece el comentario padre. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Obtiene o establece el comentario padre. |
### getText() {#getText--}
```
public abstract String getText()
```

Devuelve o establece el texto sin formato de un comentario de diapositiva. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Devuelve o establece el texto sin formato de un comentario de diapositiva. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Devuelve o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN_VALUE) significa que no se ha establecido una hora para el comentario. Lectura/escritura java.util.Date.

--------------------

La hora del comentario es un parámetro opcional.

**Devuelve:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Devuelve o establece la hora de creación de un comentario. Establecer esta propiedad a java.util.Date(Long.MIN_VALUE) significa que no se ha establecido una hora para el comentario. Lectura/escritura java.util.Date.

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

Devuelve o establece la diapositiva principal de un comentario. Solo lectura [ISlide](../../com.aspose.slides/islide).

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Devuelve el autor de un comentario. Solo lectura [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Devuelve:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura java.awt.geom.Point2D.Float.

**Devuelve:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Devuelve o establece la posición de un comentario en una diapositiva. Lectura/escritura java.awt.geom.Point2D.Float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
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