---
title: Section
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een sectie van dia's voor.
type: docs
url: /nl/com.aspose.slides/section/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Stelt een sectie van dia's voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Naam van de sectie. |
| [setName(String value)](#setName-java.lang.String-) | Naam van de sectie. |
| [getSectionId()](#getSectionId--) | Sectie-Id. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Retourneert de eerste dia van de sectie. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Retourneert een lijst met dia's in de sectie. |
### getName() {#getName--}
```
public final String getName()
```


Naam van de sectie.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Naam van de sectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Sectie-Id.

**Retourneert:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Retourneert de eerste dia van de sectie.

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Retourneert een lijst met dia's in de sectie.

**Retourneert:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lijst met dia's.