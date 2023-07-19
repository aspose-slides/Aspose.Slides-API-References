---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
weight: 1016
url: /androidjava/com.aspose.slides/isection/
---```
public interface ISection
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
public abstract String getName()
```


Name of the section.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Name of the section.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Section Id.

**Returns:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Returns first slide of the section.

**Returns:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Returns list of slides in the section.

**Returns:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - List of slides [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
