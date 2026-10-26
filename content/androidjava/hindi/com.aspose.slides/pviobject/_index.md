---
title: PVIObject
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस
description: ऑब्जेक्ट्स जो प्रॉपर्टी वैल्यू इनहेरिटेंस का विषय हो सकते हैं, उनके लिए बुनियादी सेवा इन्फ्रास्ट्रक्चर को संलग्न करता है।
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

ऑब्जेक्ट्स के लिए बुनियादी सेवा इन्फ्रास्ट्रक्चर को संलग्न करता है जो प्रॉपर्टी वैल्यू इनहेरिटेंस का विषय हो सकते हैं।
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| [hashCode()](#hashCode--) | हैश कोड लौटाता है। |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


वापस देता है Parent_Immediate ऑब्जेक्ट। केवल-पढ़ने योग्य IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPPresentationComponent getParent_IPresentationComponent()
```


वापस देती है parent IPresentationComponent। केवल-पढ़ने योग्य [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```




**Returns:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```


वापस देता है बेस स्लाइड। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


वापस देता है प्रेजेंटेशन। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - यदि ऑब्जेक्ट समान हैं तो true, अन्यथा false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


हैश कोड लौटाता है।

**Returns:**
int - हैश कोड.