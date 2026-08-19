---
title: Section
second_title: Aspose.Slides för Java API-referens
description: Representerar ett avsnitt av bilder.
type: docs
url: /sv/com.aspose.slides/section/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Representerar ett avsnitt av bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Namn på sektionen. |
| [setName(String value)](#setName-java.lang.String-) | Namn på sektionen. |
| [getSectionId()](#getSectionId--) | Avsnittsid. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returnerar den första bilden i sektionen. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returnerar en lista med bilder i sektionen. |
### getName() {#getName--}
```
public final String getName()
```

Namn på sektionen.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Namn på sektionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

Avsnittsid.

**Returnerar:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

Returnerar den första bilden i sektionen.

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

Returnerar en lista med bilder i sektionen.

**Returnerar:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista med bilder.