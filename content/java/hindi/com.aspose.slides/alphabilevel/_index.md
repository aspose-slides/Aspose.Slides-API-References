---
title: AlphaBiLevel
second_title: Aspose.Slides for Java API संदर्भ
description: एक Alpha Bi-Level इफ़ेक्ट को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level इफ़ेक्ट को दर्शाता है। थ्रेशहोल्ड से कम Alpha (Opacity) मानों को 0 (पूरी तरह पारदर्शी) और थ्रेशहोल्ड से बराबर या अधिक Alpha मानों को 100% (पूरी तरह अपारदर्शी) में बदल दिया जाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getThreshold()](#getThreshold--) | इफ़ेक्ट थ्रेशहोल्ड लौटाता है। |
| [setThreshold(float value)](#setThreshold-float-) | इफ़ेक्ट थ्रेशहोल्ड लौटाता है। |
| [getEffective()](#getEffective--) | इनहेरिटेंस लागू करके प्रभावी Alpha Bi-Level इफ़ेक्ट डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [AlphaBiLevel](../../com.aspose.slides/alphabilevel) वर्तमान [AlphaBiLevel](../../com.aspose.slides/alphabilevel) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

इफ़ेक्ट थ्रेशहोल्ड लौटाता है। पढ़ें/लिखें float.

**रिटर्न:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

इफ़ेक्ट थ्रेशहोल्ड लौटाता है। पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

इनहेरिटेंस लागू करके प्रभावी Alpha Bi-Level इफ़ेक्ट डेटा प्राप्त करता है।

**रिटर्न:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - एक [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)।
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [AlphaBiLevel](../../com.aspose.slides/alphabilevel) वर्तमान [AlphaBiLevel](../../com.aspose.slides/alphabilevel) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [AlphaBiLevel](../../com.aspose.slides/alphabilevel)। |

**रिटर्न:**
boolean - यदि वस्तुएँ बराबर हैं तो true; अन्यथा false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।