---
title: GrayScale
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक ग्रे स्केल प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/grayscale/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Represents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी Gray Scale इफ़ेक्ट डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [GrayScale](../../com.aspose.slides/grayscale) वर्तमान [GrayScale](../../com.aspose.slides/grayscale) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Gets effective Gray Scale effect data with the inheritance applied.

**रिटर्न:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [GrayScale](../../com.aspose.slides/grayscale) वर्तमान [GrayScale](../../com.aspose.slides/grayscale) के बराबर है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [GrayScale](../../com.aspose.slides/grayscale)। |

**रिटर्न:**
boolean - यदि वस्तुएँ समान हैं तो true; अन्यथा false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान वस्तु के लिए एक हैश कोड।