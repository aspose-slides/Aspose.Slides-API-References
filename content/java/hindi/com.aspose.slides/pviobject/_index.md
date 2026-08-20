---
title: PVIObject
second_title: Aspose.Slides for Java API संदर्भ
description: ऑब्जेक्ट्स के लिए बुनियादी सेवा अवसंरचना को संलग्न करता है, जो प्रॉपर्टी मान वंशागति का विषय बन सकते हैं।
type: docs
url: /hi/com.aspose.slides/pviobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

ऑब्जेक्ट्स के लिए बुनियादी सेवा अवसंरचना को संलग्न करता है, जो प्रॉपर्टी मूल्य वंशागति का विषय बन सकते हैं।

## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares with specified object. |
| [hashCode()](#hashCode--) | Returns hash code. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

parent IPresentationComponent लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)।

**वापसी:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**वापसी:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए ऑब्जेक्ट। |

**वापसी:**
boolean - True is objects are equal, otherwise false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

हैश कोड लौटाता है।

**वापसी:**
int - Hash code.