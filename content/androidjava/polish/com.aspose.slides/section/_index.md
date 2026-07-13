---
title: Section
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje sekcję slajdów.
type: docs
url: /pl/com.aspose.slides/section/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Reprezentuje sekcję slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Nazwa sekcji. |
| [setName(String value)](#setName-java.lang.String-) | Nazwa sekcji. |
| [getSectionId()](#getSectionId--) | Id sekcji. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Zwraca pierwszy slajd sekcji. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Zwraca listę slajdów w sekcji. |
### getName() {#getName--}
```
public final String getName()
```


Nazwa sekcji.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nazwa sekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Id sekcji.

**Zwraca:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Zwraca pierwszy slajd sekcji.

**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Zwraca listę slajdów w sekcji.

**Zwraca:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista slajdów.