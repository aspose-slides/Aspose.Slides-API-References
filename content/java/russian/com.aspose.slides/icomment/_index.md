---
title: IComment
second_title: Aspose.Slides for Java API Reference
description: Represents a comment on a slide.
type: docs
url: /ru/com.aspose.slides/icomment/
---```
public interface IComment
```

Представляет комментарий на слайде.
## Методы

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Возвращает или задает простой текст комментария к слайду. |
| [setText(String value)](#setText-java.lang.String-) | Возвращает или задает простой текст комментария к слайду. |
| [getCreatedTime()](#getCreatedTime--) | Возвращает или задает время создания комментария. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Возвращает или задает время создания комментария. |
| [getSlide()](#getSlide--) | Возвращает или задает родительский слайд комментария. |
| [getAuthor()](#getAuthor--) | Возвращает автора комментария. |
| [getPosition()](#getPosition--) | Возвращает или задает позицию комментария на слайде. |
| [setPosition(Point2D.Float value)](#setPosition-java.awt.geom.Point2D.Float-) | Возвращает или задает позицию комментария на слайде. |
| [remove()](#remove--) | Удаляет комментарий и все его ответы из родительской коллекции. |
| [getParentComment()](#getParentComment--) | Получает или задает родительский комментарий. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Получает или задает родительский комментарий. |
### getText() {#getText--}
```
public abstract String getText()
```

Возвращает или задает простой текст комментария к слайду. Чтение/запись String.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Возвращает или задает простой текст комментария к слайду. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

--------------------

Время комментария является необязательным параметром.

**Returns:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

--------------------

Время комментария является необязательным параметром.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |
### getSlide() {#getSlide--}
```
public abstract ISlide getSlide()
```

Возвращает или задает родительский слайд комментария. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Возвращает автора комментария. Только для чтения [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Returns:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract Point2D.Float getPosition()
```

Возвращает или задает позицию комментария на слайде. Чтение/запись java.awt.geom.Point2D.Float.

**Returns:**
java.awt.geom.Point2D.Float
### setPosition(Point2D.Float value) {#setPosition-java.awt.geom.Point2D.Float-}
```
public abstract void setPosition(Point2D.Float value)
```

Возвращает или задает позицию комментария на слайде. Чтение/запись java.awt.geom.Point2D.Float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |
### remove() {#remove--}
```
public abstract void remove()
```

Удаляет комментарий и все его ответы из родительской коллекции.
### getParentComment() {#getParentComment--}
```
public abstract IComment getParentComment()
```

Получает или задает родительский комментарий. Чтение/запись [IComment](../../com.aspose.slides/icomment).

**Returns:**
[IComment](../../com.aspose.slides/icomment)
### setParentComment(IComment value) {#setParentComment-com.aspose.slides.IComment-}
```
public abstract void setParentComment(IComment value)
```

Получает или задает родительский комментарий. Чтение/запись [IComment](../../com.aspose.slides/icomment).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IComment](../../com.aspose.slides/icomment) |  |