---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /ru/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

Представляет текст, извлечённый из слайда
## Методы

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Текст в фигурах слайда |
| [getMasterText()](#getMasterText--) | Текст в фигурах главной страницы для этого слайда |
| [getLayoutText()](#getLayoutText--) | Текст в фигурах страницы макета для этого слайда |
| [getNotesText()](#getNotesText--) | Текст в фигурах страницы заметок для этого слайда |
| [getCommentsText()](#getCommentsText--) | Текст комментариев к слайду |
### getText() {#getText--}
```
public abstract String getText()
```


Текст в фигурах слайда

**Возвращаемое значение:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


Текст в фигурах главной страницы для этого слайда

**Возвращаемое значение:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


Текст в фигурах страницы макета для этого слайда

**Возвращаемое значение:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


Текст в фигурах страницы заметок для этого слайда

**Возвращаемое значение:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


Текст комментариев к слайду

--------------------

Это поле пусто, когда текст извлекается в режиме Arranged.

**Возвращаемое значение:**
java.lang.String