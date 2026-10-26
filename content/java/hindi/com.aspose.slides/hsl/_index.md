---
title: HSL
second_title: Aspose.Slides for Java API संदर्भ
description: Hue/Saturation/Luminance प्रभाव को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/hsl/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Hue/Saturation/Luminance प्रभाव का प्रतिनिधित्व करता है। प्रत्येक hue, saturation, और luminance को उसके वर्तमान मान के संबंध में समायोजित किया जा सकता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत लागू होते हुए प्रभावी Hue/Saturation/Luminance डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [HSL](../../com.aspose.slides/hsl) वर्तमान [HSL](../../com.aspose.slides/hsl) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


विरासत लागू होते हुए प्रभावी Hue/Saturation/Luminance डेटा प्राप्त करता है।

**वापसी:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - A [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट [HSL](../../com.aspose.slides/hsl) वर्तमान [HSL](../../com.aspose.slides/hsl) के बराबर है या नहीं।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [HSL](../../com.aspose.slides/hsl)। |

**वापसी:**
boolean - सही यदि वस्तुएँ बराबर हैं; अन्यथा, गलत।
### hashCode() {#hashCode--}
```
public int hashCode()
```


किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान वस्तु के लिए एक हैश कोड।