---
title: GrayScale
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: ग्रे स्केल इफ़ेक्ट का प्रतिनिधित्व करता है।
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

ग्रे स्केल इफ़ेक्ट का प्रतिनिधित्व करता है। सभी इफ़ेक्ट रंग मानों को उनके चमक के अनुरूप ग्रे के एक शेड में बदलता है। इफ़ेक्ट अल्फा (अपारदर्शिता) मान अपरिवर्तित रहते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी ग्रे स्केल इफ़ेक्ट डेटा प्राप्त करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [GrayScale](../../com.aspose.slides/grayscale) वर्तमान [GrayScale](../../com.aspose.slides/grayscale) के बराबर है। |
| [hashCode()](#hashCode--) | किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

विरासत लागू करके प्रभावी ग्रे स्केल इफ़ेक्ट डेटा प्राप्त करता है।

**रिटर्न:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - एक [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata)।

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
boolean - यदि ऑब्जेक्ट समान हों तो true; अन्यथा false।

### hashCode() {#hashCode--}
```
public int hashCode()
```

किसी विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।