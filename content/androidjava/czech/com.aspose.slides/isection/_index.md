---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /cs/com.aspose.slides/isection/
---```
public interface ISection
```

Představuje sekci snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Název sekce. |
| [setName(String value)](#setName-java.lang.String-) | Název sekce. |
| [getSectionId()](#getSectionId--) | ID sekce. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Vrací první snímek sekce. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Vrací seznam snímků v sekci. |
### getName() {#getName--}
```
public abstract String getName()
```


Název sekce.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Název sekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


ID sekce.

**Vrací:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Vrací první snímek sekce.

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Vrací seznam snímků v sekci.

**Vrací:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Seznam snímků [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)