---
title: Section
second_title: Aspose.Slides for Java API संदर्भ
description: स्लाइडों के सेक्शन का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/section/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

स्लाइडों के सेक्शन का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getName()](#getName--) | सेक्शन का नाम। |
| [setName(String value)](#setName-java.lang.String-) | सेक्शन का नाम। |
| [getSectionId()](#getSectionId--) | सेक्शन आईडी। |
| [getStartedFromSlide()](#getStartedFromSlide--) | सेक्शन की पहली स्लाइड लौटाता है। |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | सेक्शन में स्लाइडों की सूची लौटाता है। |
### getName() {#getName--}
```
public final String getName()
```


सेक्शन का नाम।

**रिटर्न:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


सेक्शन का नाम।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


सेक्शन आईडी।

**रिटर्न:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


सेक्शन की पहली स्लाइड लौटाता है।

**रिटर्न:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


सेक्शन में स्लाइडों की सूची लौटाता है।

**रिटर्न:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - स्लाइडों की सूची।