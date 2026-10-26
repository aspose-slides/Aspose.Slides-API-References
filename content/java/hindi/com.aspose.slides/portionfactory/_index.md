---
title: PortionFactory
second_title: Aspose.Slides के लिए Java API संदर्भ
description: परीक्षण भाग बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/portionfactory/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

परीक्षण भाग बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createPortion()](#createPortion--) | एक खाली टेक्स्ट Portion बनाता है। |
| [createPortion(String str)](#createPortion-java.lang.String-) | निर्दिष्ट स्ट्रिंग से एक टेक्स्ट Portion बनाता है। |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | निर्दिष्ट portion डेटा का उपयोग करके एक Portion बनाता है। |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```

### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```

एक खाली टेक्स्ट Portion बनाता है।

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```

निर्दिष्ट स्ट्रिंग से एक टेक्स्ट Portion बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| str | java.lang.String | स्ट्रिंग। |

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```

निर्दिष्ट portion डेटा का उपयोग करके एक Portion बनाता है।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | उपयोग करने के लिए एक Portion। |

**रिटर्न:**
[IPortion](../../com.aspose.slides/iportion) - Portion.