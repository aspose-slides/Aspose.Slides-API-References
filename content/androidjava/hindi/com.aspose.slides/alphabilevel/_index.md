---
title: AlphaBiLevel
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: Alpha Bi-Level इफ़ेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/alphabilevel/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect  
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Alpha Bi-Level इफ़ेक्ट का प्रतिनिधित्व करता है। थ्रेशोल्ड से कम Alpha (Opacity) मान 0 (पूरा पारदर्शी) में बदल दिए जाते हैं और थ्रेशोल्ड से बराबर या अधिक Alpha मान 100 % (पूरा अपारदर्शी) में बदल दिए जाते हैं।

## विधियाँ

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | इफ़ेक्ट थ्रेशोल्ड लौटाता है। |
| [setThreshold(float value)](#setThreshold-float-) | इफ़ेक्ट थ्रेशोल्ड लौटाता है। |
| [getEffective()](#getEffective--) | इनहेरिटेंस लागू करके प्रभावी Alpha Bi-Level इफ़ेक्ट डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [AlphaBiLevel](../../com.aspose.slides/alphabilevel) वर्तमान [AlphaBiLevel](../../com.aspose.slides/alphabilevel) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

इफ़ेक्ट थ्रेशोल्ड लौटाता है। पढ़ने/लिखने योग्य float।

**वापसी:**
float

### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

इफ़ेक्ट थ्रेशोल्ड लौटाता है। पढ़ने/लिखने योग्य float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

इनहेरिटेंस लागू करके प्रभावी Alpha Bi-Level इफ़ेक्ट डेटा प्राप्त करता है।

**वापसी:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - एक [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata)।

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [AlphaBiLevel](../../com.aspose.slides/alphabilevel) वर्तमान [AlphaBiLevel](../../com.aspose.slides/alphabilevel) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) तुलना करने के लिए। |

**वापसी:**
boolean - यदि ऑब्जेक्ट समान हैं तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।