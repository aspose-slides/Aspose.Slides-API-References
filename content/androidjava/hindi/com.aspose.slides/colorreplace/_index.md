---
title: ColorReplace
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक Color Replacement प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/colorreplace/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

एक Color Replacement प्रभाव का प्रतिनिधित्व करता है। सभी प्रभाव रंगों को एक निश्चित रंग में बदल दिया जाता है। अल्फा मान अपरिवर्तित रहते हैं।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColor()](#getColor--) | प्रत्येक पिक्सेल के रंग को बदलने वाले रंग स्वरूप को लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने पर प्रभावी Color Replacement प्रभाव डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [ColorReplace](../../com.aspose.slides/colorreplace) वर्तमान [ColorReplace](../../com.aspose.slides/colorreplace) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

प्रत्येक पिक्सेल के रंग को बदलने वाले रंग स्वरूप को लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

विरासत लागू होने पर प्रभावी Color Replacement प्रभाव डेटा प्राप्त करता है।

**वापसी:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - एक [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata)।

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long।

**वापसी:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [ColorReplace](../../com.aspose.slides/colorreplace) वर्तमान [ColorReplace](../../com.aspose.slides/colorreplace) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [ColorReplace](../../com.aspose.slides/colorreplace)। |

**वापसी:**
boolean - true यदि वस्तुएँ बराबर हैं; अन्यथा false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान वस्तु के लिए एक हैश कोड।