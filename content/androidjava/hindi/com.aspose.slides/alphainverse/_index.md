---
title: AlphaInverse
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: एक Alpha Inverse प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/alphainverse/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

एक Alpha Inverse प्रभाव का प्रतिनिधित्व करता है। Alpha (opacity) मानों को 100% से घटाकर उलटा जाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | Alpha Inverse प्रभाव डेटा को विरासत लागू होने के साथ प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [AlphaInverse](../../com.aspose.slides/alphainverse) वर्तमान [AlphaInverse](../../com.aspose.slides/alphainverse) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में काम करता है। |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```

Alpha Inverse प्रभाव डेटा को विरासत लागू होने के साथ प्राप्त करता है।

**वापसी:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - एक [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata)।

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [AlphaInverse](../../com.aspose.slides/alphainverse) वर्तमान [AlphaInverse](../../com.aspose.slides/alphainverse) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना के लिए [AlphaInverse](../../com.aspose.slides/alphainverse)। |

**वापसी:**
boolean - true यदि वस्तुएँ समान हैं; अन्यथा, false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में काम करता है।

**वापसी:**
int - वर्तमान वस्तु का एक हैश कोड।