---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: Представляет секцию слайдов.
type: docs
url: /ru/com.aspose.slides/isection/
---```
public interface ISection
```

Представляет секцию слайдов.
## Методы

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Имя секции. |
| [setName(String value)](#setName-java.lang.String-) | Имя секции. |
| [getSectionId()](#getSectionId--) | Идентификатор секции. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Возвращает первый слайд секции. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Возвращает список слайдов в секции. |
### getName() {#getName--}
```
public abstract String getName()
```

Имя секции.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Имя секции.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Идентификатор секции.

**Returns:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Возвращает первый слайд секции.

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Возвращает список слайдов в секции.

**Returns:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)