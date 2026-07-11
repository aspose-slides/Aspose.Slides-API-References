---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет автора комментариев.
type: docs
url: /ru/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

Представляет автора комментариев.
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Возвращает или задает имя автора. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задает имя автора. |
| [getInitials()](#getInitials--) | Возвращает или задает инициалы автора. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Возвращает или задает инициалы автора. |
| [getComments()](#getComments--) | Возвращает коллекцию комментариев, сделанных этим автором. |
| [remove()](#remove--) | Удаляет автора из родительской коллекции. |
### getName() {#getName--}
```
public abstract String getName()
```


Возвращает или задает имя автора. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Возвращает или задает имя автора. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getInitials() {#getInitials--}
```
public abstract String getInitials()
```


Возвращает или задает инициалы автора. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```


Возвращает или задает инициалы автора. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```


Возвращает коллекцию комментариев, сделанных этим автором. Только для чтения [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Возвращаемое значение:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```


Удаляет автора из родительской коллекции.