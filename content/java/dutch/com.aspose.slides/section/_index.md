---
title: Section
second_title: Aspose.Slides voor Java API-referentie
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
| [getStartedFromSlide()](#getStartedFromSlide--) | Geeft de eerste dia van de sectie terug. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Geeft een lijst van dia's in de sectie terug. |
### getName() {#getName--}
```
public final String getName()
```


Naam van de sectie.

**Retour:**
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

**Retour:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Geeft de eerste dia van de sectie terug.

**Retour:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Geeft een lijst van dia's in de sectie terug.

**Retour:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lijst van dia's.