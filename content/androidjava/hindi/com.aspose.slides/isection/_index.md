---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents section of slides.
type: docs
url: /hi/com.aspose.slides/isection/
---```
public interface ISection
```

सेक्शन का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getName()](#getName--) | सेक्शन का नाम। |
| [setName(String value)](#setName-java.lang.String-) | सेक्शन का नाम। |
| [getSectionId()](#getSectionId--) | सेक्शन आईडी। |
| [getStartedFromSlide()](#getStartedFromSlide--) | सेक्शन की पहली स्लाइड लौटाता है। |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | सेक्शन में स्लाइड्स की सूची लौटाता है। |
### getName() {#getName--}
```
public abstract String getName()
```

सेक्शन का नाम।

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

सेक्शन का नाम।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

सेक्शन आईडी।

**रिटर्न:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

सेक्शन की पहली स्लाइड लौटाता है।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

सेक्शन में स्लाइड्स की सूची लौटाता है।

**रिटर्न:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - स्लाइड्स की सूची [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)