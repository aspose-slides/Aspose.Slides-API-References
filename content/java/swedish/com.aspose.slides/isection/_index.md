---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: Representerar ett avsnitt av bilder.
type: docs
url: /sv/com.aspose.slides/isection/
---```
public interface ISection
```

Representerar ett avsnitt av bilder.
## Metoder

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Namn på avsnittet. |
| [setName(String value)](#setName-java.lang.String-) | Namn på avsnittet. |
| [getSectionId()](#getSectionId--) | Avsnittsid. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returnerar den första bilden i avsnittet. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returnerar en lista med bilder i avsnittet. |
### getName() {#getName--}
```
public abstract String getName()
```

Namn på avsnittet.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Namn på avsnittet.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Avsnittsid.

**Returnerar:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Returnerar den första bilden i avsnittet.

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Returnerar en lista med bilder i avsnittet.

**Returnerar:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista med bilder [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)