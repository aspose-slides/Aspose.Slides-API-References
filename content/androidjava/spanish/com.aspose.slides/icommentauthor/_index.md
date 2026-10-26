---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Representa un autor de comentarios.
type: docs
url: /es/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Representa un autor de comentarios.
## Métodos

| Method | Descripción |
| --- | --- |
| [getName()](#getName--) | Devuelve o establece el nombre del autor. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve o establece el nombre del autor. |
| [getInitials()](#getInitials--) | Devuelve o establece las iniciales del autor. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Devuelve o establece las iniciales del autor. |
| [getComments()](#getComments--) | Devuelve la colección de comentarios realizados por este autor. |
| [remove()](#remove--) | Elimina al autor de la colección padre. |
### getName() {#getName--}
```
public abstract String getName()
```


Devuelve o establece el nombre del autor. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Devuelve o establece el nombre del autor. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Devuelve o establece las iniciales del autor. Lectura/escritura String.

**Devuelve:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Devuelve o establece las iniciales del autor. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Devuelve la colección de comentarios realizados por este autor. Solo lectura [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Devuelve:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Elimina al autor de la colección padre.