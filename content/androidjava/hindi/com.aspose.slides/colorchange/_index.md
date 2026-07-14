---
title: ColorChange
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक Color Change प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/colorchange/
---

**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

एक Color Change प्रभाव का प्रतिनिधित्व करता है। FromColor के उदाहरणों को ToColor के उदाहरणों से बदल दिया जाता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFromColor()](#getFromColor--) | जिस रंग को बदला जाएगा। |
| [getToColor()](#getToColor--) | जिस रंग से बदला जाएगा। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी Color Change प्रभाव डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [ColorChange](../../com.aspose.slides/colorchange) वर्तमान [ColorChange](../../com.aspose.slides/colorchange) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

जिस रंग को बदला जाएगा। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

जिस रंग से बदला जाएगा। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी Color Change प्रभाव डेटा प्राप्त करता है।

**वापसी:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).

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

निर्धारित करता है कि निर्दिष्ट [ColorChange](../../com.aspose.slides/colorchange) वर्तमान [ColorChange](../../com.aspose.slides/colorchange) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [ColorChange](../../com.aspose.slides/colorchange)। |

**वापसी:**
boolean - सही यदि वस्तुएँ समान हैं; अन्यथा, गलत।

### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।