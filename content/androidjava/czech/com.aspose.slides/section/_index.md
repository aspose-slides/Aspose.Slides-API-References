---
title: Section
second_title: Aspose.Slides pro Android pomocí referencí Java API
description: Představuje sekci snímků.
type: docs
url: /cs/com.aspose.slides/section/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Představuje sekci snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [getName()](#getName--) | Název sekce. |
| [setName(String value)](#setName-java.lang.String-) | Název sekce. |
| [getSectionId()](#getSectionId--) | Identifikátor sekce. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Vrací první snímek sekce. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Vrací seznam snímků v sekci. |
### getName() {#getName--}
```
public final String getName()
```


Název sekce.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Název sekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Identifikátor sekce.

**Vrací:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Vrací první snímek sekce.

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Vrací seznam snímků v sekci.

**Vrací:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Seznam snímků.