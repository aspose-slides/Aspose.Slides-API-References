---
title: ISlideText
second_title: Aspose.Slides for Android через справочник API Java
description: Представляет текст, извлечённый из слайда
type: docs
url: /ru/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Представляет текст, извлечённый из слайда
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | The text on the slide's shapes |
| [getMasterText()](#getMasterText--) | The text on the master page's shapes for this slide |
| [getLayoutText()](#getLayoutText--) | The text on the layout page's shapes for this slide |
| [getNotesText()](#getNotesText--) | The text on the notes page's shapes for this slide |
| [getCommentsText()](#getCommentsText--) | The text of the slide comments |
### getText() {#getText--}
```
public abstract String getText()
```

Текст на объектах слайда

**Возвращаемое значение:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

Текст на объектах главной страницы для этого слайда

**Возвращаемое значение:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

Текст на объектах страницы макета для этого слайда

**Возвращаемое значение:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

Текст на объектах страницы заметок для этого слайда

**Возвращаемое значение:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

Текст комментариев слайда

--------------------

Это поле пусто, когда текст извлекается с использованием режима Arranged.

**Возвращаемое значение:**
java.lang.String