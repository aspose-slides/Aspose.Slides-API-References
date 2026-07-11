---
title: Section
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет раздел слайдов.
type: docs
url: /ru/com.aspose.slides/section/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Представляет раздел слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [getName()](#getName--) | Имя раздела. |
| [setName(String value)](#setName-java.lang.String-) | Имя раздела. |
| [getSectionId()](#getSectionId--) | Идентификатор раздела. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Возвращает первый слайд раздела. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Возвращает список слайдов в разделе. |
### getName() {#getName--}
```
public final String getName()
```

Имя раздела.

**Возвращаемое значение:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Имя раздела.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

Идентификатор раздела.

**Возвращаемое значение:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

Возвращает первый слайд раздела.

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

Возвращает список слайдов в разделе.

**Возвращаемое значение:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Список слайдов.