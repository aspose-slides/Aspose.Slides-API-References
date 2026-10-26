---
title: Section
second_title: Aspose.Slides Androidra a Java API hivatkozásával
description: A diák szakaszát reprezentálja.
type: docs
url: /hu/com.aspose.slides/section/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

A diák szakaszát reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getName()](#getName--) | A szakasz neve. |
| [setName(String value)](#setName-java.lang.String-) | A szakasz neve. |
| [getSectionId()](#getSectionId--) | A szakasz azonosítója. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Visszaadja a szakasz első diát. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Visszaadja a szakasz diák listáját. |
### getName() {#getName--}
```
public final String getName()
```

A szakasz neve.

**Visszatér:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

A szakasz neve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```

A szakasz azonosítója.

**Visszatér:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

Visszaadja a szakasz első diát.

**Visszatér:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

Visszaadja a szakasz diák listáját.

**Visszatér:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Diák listája.