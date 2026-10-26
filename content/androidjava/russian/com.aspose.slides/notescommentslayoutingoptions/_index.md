---
title: NotesCommentsLayoutingOptions
second_title: Справочник API Aspose.Slides для Android через Java
description: Предоставляет параметры, управляющие внешним видом разметки заметок и комментариев в экспортируемом документе.
type: docs
url: /ru/com.aspose.slides/notescommentslayoutingoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class NotesCommentsLayoutingOptions implements ISlidesLayoutOptions
```

Предоставляет параметры, управляющие внешним видом разметки заметок и комментариев в экспортируемом документе.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NotesCommentsLayoutingOptions()](#NotesCommentsLayoutingOptions--) | Конструктор по умолчанию. |
## Методы

| Метод | Описание |
| --- | --- |
| [getShowCommentsByNoAuthor()](#getShowCommentsByNoAuthor--) | Получает или задает видимость комментариев без автора. |
| [setShowCommentsByNoAuthor(boolean value)](#setShowCommentsByNoAuthor-boolean-) | Получает или задает видимость комментариев без автора. |
| [getNotesPosition()](#getNotesPosition--) | Получает или задает позицию заметок на странице. |
| [setNotesPosition(int value)](#setNotesPosition-int-) | Получает или задает позицию заметок на странице. |
| [getCommentsPosition()](#getCommentsPosition--) | Получает или задает позицию комментариев на странице. |
| [setCommentsPosition(int value)](#setCommentsPosition-int-) | Получает или задает позицию комментариев на странице. |
| [getCommentsAreaColor()](#getCommentsAreaColor--) | Получает или задает цвет области комментариев (Применяется только если комментарии отображаются справа). |
| [setCommentsAreaColor(Integer value)](#setCommentsAreaColor-java.lang.Integer-) | Получает или задает цвет области комментариев (Применяется только если комментарии отображаются справа). |
| [getCommentsAreaWidth()](#getCommentsAreaWidth--) | Получает или задает ширину области вывода комментариев в пикселях (Применяется только если комментарии отображаются справа). |
| [setCommentsAreaWidth(int value)](#setCommentsAreaWidth-int-) | Получает или задает ширину области вывода комментариев в пикселях (Применяется только если комментарии отображаются справа). |
### NotesCommentsLayoutingOptions() {#NotesCommentsLayoutingOptions--}
```
public NotesCommentsLayoutingOptions()
```

Конструктор по умолчанию.

### getShowCommentsByNoAuthor() {#getShowCommentsByNoAuthor--}
```
public final boolean getShowCommentsByNoAuthor()
```

Получает или задает видимость комментариев без автора. Если значение true, комментарии будут отображаться. (Применяется только если комментарии отображаются).

--------------------

Значение по умолчанию — **false**.

**Возвращаемое значение:**
boolean
### setShowCommentsByNoAuthor(boolean value) {#setShowCommentsByNoAuthor-boolean-}
```
public final void setShowCommentsByNoAuthor(boolean value)
```

Получает или задает видимость комментариев без автора. Если значение true, комментарии будут отображаться. (Применяется только если комментарии отображаются).

--------------------

Значение по умолчанию — **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getNotesPosition() {#getNotesPosition--}
```
public final int getNotesPosition()
```

Получает или задает позицию заметок на странице.

--------------------

Значение по умолчанию — **NotesPositions.None**.

**Возвращаемое значение:**
int
### setNotesPosition(int value) {#setNotesPosition-int-}
```
public final void setNotesPosition(int value)
```

Получает или задает позицию заметок на странице.

--------------------

Значение по умолчанию — **NotesPositions.None**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getCommentsPosition() {#getCommentsPosition--}
```
public final int getCommentsPosition()
```

Получает или задает позицию комментариев на странице.

--------------------

Значение по умолчанию — **CommentsPositions.None**.

**Возвращаемое значение:**
int
### setCommentsPosition(int value) {#setCommentsPosition-int-}
```
public final void setCommentsPosition(int value)
```

Получает или задает позицию комментариев на странице.

--------------------

Значение по умолчанию — **CommentsPositions.None**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getCommentsAreaColor() {#getCommentsAreaColor--}
```
public final Integer getCommentsAreaColor()
```

Получает или задает цвет области комментариев (Применяется только если комментарии отображаются справа).

--------------------

Значение по умолчанию — **SkyBlue**.

**Возвращаемое значение:**
java.lang.Integer
### setCommentsAreaColor(Integer value) {#setCommentsAreaColor-java.lang.Integer-}
```
public final void setCommentsAreaColor(Integer value)
```

Получает или задает цвет области комментариев (Применяется только если комментарии отображаются справа).

--------------------

Значение по умолчанию — **SkyBlue**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getCommentsAreaWidth() {#getCommentsAreaWidth--}
```
public final int getCommentsAreaWidth()
```

Получает или задает ширину области вывода комментариев в пикселях (Применяется только если комментарии отображаются справа).

--------------------

Минимальное и значение по умолчанию — **150**.

**Возвращаемое значение:**
int
### setCommentsAreaWidth(int value) {#setCommentsAreaWidth-int-}
```
public final void setCommentsAreaWidth(int value)
```

Получает или задает ширину области вывода комментариев в пикселях (Применяется только если комментарии отображаются справа).

--------------------

Минимальное и значение по умолчанию — **150**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |