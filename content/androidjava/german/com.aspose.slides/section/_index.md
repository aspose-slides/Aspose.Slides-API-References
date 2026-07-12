---
title: Section
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Abschnitt von Folien dar.
type: docs
url: /de/com.aspose.slides/section/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Stellt einen Abschnitt von Folien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Name des Abschnitts. |
| [setName(String value)](#setName-java.lang.String-) | Name des Abschnitts. |
| [getSectionId()](#getSectionId--) | Abschnitts-ID. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Gibt die erste Folie des Abschnitts zurück. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Gibt die Liste der Folien im Abschnitt zurück. |
### getName() {#getName--}
```
public final String getName()
```


Name des Abschnitts.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Name des Abschnitts.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Abschnitts-ID.

**Rückgabewert:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Gibt die erste Folie des Abschnitts zurück.

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Gibt die Liste der Folien im Abschnitt zurück.

**Rückgabewert:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Liste der Folien.