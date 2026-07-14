---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /hi/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

परीक्षण भाग बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createPortion()](#createPortion--) | खाली टेक्स्ट भाग बनाता है। |
| [createPortion(String str)](#createPortion-java.lang.String-) | निर्दिष्ट स्ट्रिंग से टेक्स्ट भाग बनाता है। |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | निर्दिष्ट भाग डेटा का उपयोग करके भाग बनाता है। |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


खाली टेक्स्ट भाग बनाता है।

**रिटर्न:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


निर्दिष्ट स्ट्रिंग से टेक्स्ट भाग बनाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | java.lang.String | String. |

**रिटर्न:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


निर्दिष्ट भाग डेटा का उपयोग करके भाग बनाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | उपयोग करने के लिए एक भाग। |

**रिटर्न:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.