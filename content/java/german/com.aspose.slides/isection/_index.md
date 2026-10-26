---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: Stellt einen Abschnitt von Folien dar.
type: docs
url: /de/com.aspose.slides/isection/
---```
public interface ISection
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
public abstract String getName()
```


Name des Abschnitts.

**Rückgabe:** 
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Name des Abschnitts.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Abschnitts-ID.

**Rückgabe:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Gibt die erste Folie des Abschnitts zurück.

**Rückgabe:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Gibt die Liste der Folien im Abschnitt zurück.

**Rückgabe:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Liste der Folien [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)