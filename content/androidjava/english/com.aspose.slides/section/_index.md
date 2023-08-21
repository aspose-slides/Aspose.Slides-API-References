---
title: Section
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /com.aspose.slides/section/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Represents section of slides.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Name of the section. |
| [setName(String value)](#setName-java.lang.String-) | Name of the section. |
| [getSectionId()](#getSectionId--) | Section Id. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Returns first slide of the section. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Returns list of slides in the section. |
### getName() {#getName--}
```
public final String getName()
```


Name of the section.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Name of the section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Section Id.

**Returns:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Returns first slide of the section.

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Returns list of slides in the section.

**Returns:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides.
