---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een sectie van dia's voor.
type: docs
url: /nl/com.aspose.slides/isection/
---```
public interface ISection
```

Stelt een sectie van dia's voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Naam van de sectie. |
| [setName(String value)](#setName-java.lang.String-) | Naam van de sectie. |
| [getSectionId()](#getSectionId--) | Sectie-ID. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Retourneert de eerste dia van de sectie. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Retourneert een lijst met dia's in de sectie. |
### getName() {#getName--}
```
public abstract String getName()
```

Naam van de sectie.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Naam van de sectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Sectie-ID.

**Retourneert:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Retourneert de eerste dia van de sectie.

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Retourneert een lijst met dia's in de sectie.

**Retourneert:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lijst met dia's [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)