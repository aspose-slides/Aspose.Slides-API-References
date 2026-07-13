---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en sektion av bilder.
type: docs
url: /sv/com.aspose.slides/isection/
---```
public interface ISection
```

Representerar en sektion av bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Namnet på sektionen. |
| [setName(String value)](#setName-java.lang.String-) | Namnet på sektionen. |
| [getSectionId()](#getSectionId--) | Sektionens ID. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returnerar den första bilden i sektionen. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returnerar en lista med bilder i sektionen. |
### getName() {#getName--}
```
public abstract String getName()
```


Namnet på sektionen.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Namnet på sektionen.

**Parametrar:**
| Parameter | Type | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Sektionens ID.

**Returnerar:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Returnerar den första bilden i sektionen.

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Returnerar en lista med bilder i sektionen.

**Returnerar:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista med bilder [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)