---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
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
| [getName()](#getName--) | Возвращает или задаёт имя автора. |
| [setName(String value)](#setName-java.lang.String-) | Возвращает или задаёт имя автора. |
| [getInitials()](#getInitials--) | Возвращает или задаёт инициалы автора. |
| [setInitials(String value)](#setInitials-java.lang.String-) | Возвращает или задаёт инициалы автора. |
| [getComments()](#getComments--) | Возвращает коллекцию комментариев, сделанных этим автором. |
| [remove()](#remove--) | Удаляет автора из родительской коллекции. |
### getName() {#getName--}
```
public abstract String getName()
```

Возвращает или задаёт имя автора. Чтение/запись String.

**Возвращает:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Возвращает или задаёт имя автора. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

Возвращает или задаёт инициалы автора. Чтение/запись String.

**Возвращает:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

Возвращает или задаёт инициалы автора. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

Возвращает коллекцию комментариев, сделанных этим автором. Только для чтения [ICommentCollection](../../com.aspose.slides/icommentcollection).

**Возвращает:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

Удаляет автора из родительской коллекции.