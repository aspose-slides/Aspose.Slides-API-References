---
title: Section
second_title: Android के लिए Aspose.Slides Java API संदर्भ
description: स्लाइड्स के सेक्शन का प्रतिनिधित्व करता है।
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

स्लाइड्स के अनुभाग का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getName()](#getName--) | सेक्शन का नाम। |
| [setName(String value)](#setName-java.lang.String-) | सेक्शन का नाम। |
| [getSectionId()](#getSectionId--) | सेक्शन Id। |
| [getStartedFromSlide()](#getStartedFromSlide--) | सेक्शन की पहली स्लाइड लौटाता है। |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | सेक्शन में स्लाइड्स की सूची लौटाता है। |

### getName() {#getName--}
```
public final String getName()
```

सेक्शन का नाम।

**वापसी:**  
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

सेक्शन Id।

**वापसी:**  
java.util.UUID

### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```

सेक्शन की पहली स्लाइड लौटाता है।

**वापसी:**  
[ISlide](../../com.aspose.slides/islide)

### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```

सेक्शन में स्लाइड्स की सूची लौटाता है।

**वापसी:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - स्लाइड्स की सूची।