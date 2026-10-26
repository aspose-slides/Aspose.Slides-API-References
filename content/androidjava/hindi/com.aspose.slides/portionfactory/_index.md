---
title: PortionFactory
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: परीक्षण भाग बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/portionfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

परीक्षण भाग बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createPortion()](#createPortion--) | एक खाली टेक्स्ट भाग बनाता है। |
| [createPortion(String str)](#createPortion-java.lang.String-) | निर्दिष्ट स्ट्रिंग से एक टेक्स्ट भाग बनाता है। |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | निर्दिष्ट भाग डेटा का उपयोग करके एक भाग बनाता है। |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


एक खाली टेक्स्ट भाग बनाता है।

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


निर्दिष्ट स्ट्रिंग से एक टेक्स्ट भाग बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | java.lang.String | String. |

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


निर्दिष्ट भाग डेटा का उपयोग करके एक भाग बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | उपयोग करने के लिए एक भाग। |

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.