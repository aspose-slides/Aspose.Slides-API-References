---
title: IComment
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет комментарий к слайду.
type: docs
url: /ru/com.aspose.slides/icomment/
---```
public interface IComment
```

Представляет комментарий к слайду.
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Возвращает или задает простой текст комментария к слайду. |
| [setText(String value)](#setText-java.lang.String-) | Возвращает или задает простой текст комментария к слайду. |
| [getCreatedTime()](#getCreatedTime--) | Возвращает или задает время создания комментария. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Возвращает или задает время создания комментария. |
| [getSlide()](#getSlide--) | Возвращает или задает родительский слайд комментария. |
| [getAuthor()](#getAuthor--) | Возвращает автора комментария. |
| [getPosition()](#getPosition--) | Возвращает или задает позицию комментария на слайде. |
| [setPosition(PointF value)](#setPosition-android.graphics.PointF-) | Возвращает или задает позицию комментария на слайде. |
| [remove()](#remove--) | Удаляет комментарий и все его ответы из родительской коллекции. |
| [getParentComment()](#getParentComment--) | Получает или задает родительский комментарий. |
| [setParentComment(IComment value)](#setParentComment-com.aspose.slides.IComment-) | Получает или задает родительский комментарий. |
### getText() {#getText--}
```
public abstract String getText()
```

Возвращает или задает простой текст комментария к слайду. Чтение/запись String.

**Возвращаемое значение:**
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

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN\_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

--------------------

Время комментария является необязательным параметром.

**Возвращаемое значение:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Возвращает или задает время создания комментария. Установка этого свойства в java.util.Date(Long.MIN\_VALUE) означает, что время комментария не задано. Чтение/запись java.util.Date.

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

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)
### getAuthor() {#getAuthor--}
```
public abstract ICommentAuthor getAuthor()
```

Возвращает автора комментария. Только для чтения [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**Возвращаемое значение:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### getPosition() {#getPosition--}
```
public abstract PointF getPosition()
```

Возвращает или задает позицию комментария на слайде. Чтение/запись android.graphics.PointF.

**Возвращаемое значение:**
android.graphics.PointF
### setPosition(PointF value) {#setPosition-android.graphics.PointF-}
```
public abstract void setPosition(PointF value)
```

Возвращает или задает позицию комментария на слайде. Чтение/запись android.graphics.PointF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | android.graphics.PointF |  |

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

**Возвращаемое значение:**
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