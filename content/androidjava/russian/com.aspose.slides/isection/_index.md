---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет раздел слайдов.
type: docs
url: /ru/com.aspose.slides/isection/
---```
public interface ISection
```

Представляет раздел слайдов.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Имя раздела. |
| [setName(String value)](#setName-java.lang.String-) | Имя раздела. |
| [getSectionId()](#getSectionId--) | Идентификатор раздела. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Возвращает первый слайд раздела. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Возвращает список слайдов в разделе. |
### getName() {#getName--}
```
public abstract String getName()
```


Имя раздела.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Имя раздела.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Идентификатор раздела.

**Returns:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Возвращает первый слайд раздела.

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Возвращает список слайдов в разделе.

**Returns:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Список слайдов [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)