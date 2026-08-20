---
title: ColorChange
second_title: Java के लिए Aspose.Slides API संदर्भ
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

एक Color Change प्रभाव का प्रतिनिधित्व करता है। FromColor के उदाहरण ToColor के उदाहरणों से बदल दिए जाते हैं।
## मेथड्स

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | रंग जिसे बदला जाएगा। |
| [getToColor()](#getToColor--) | रंग जिसे प्रतिस्थापित किया जाएगा। |
| [getEffective()](#getEffective--) | विरासत लागू होते हुए प्रभावी Color Change प्रभाव डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित [ColorChange](../../com.aspose.slides/colorchange) वर्तमान [ColorChange](../../com.aspose.slides/colorchange) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

रंग जिसे बदला जाएगा। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

रंग जिसे प्रतिस्थापित किया जाएगा। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**रिटर्न:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

विरासत लागू होते हुए प्रभावी Color Change प्रभाव डेटा प्राप्त करता है।

**रिटर्न:**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - एक [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata)।
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**रिटर्न:**  
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित [ColorChange](../../com.aspose.slides/colorchange) वर्तमान [ColorChange](../../com.aspose.slides/colorchange) के बराबर है या नहीं निर्धारित करता है।

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [ColorChange](../../com.aspose.slides/colorchange)। |

**रिटर्न:**  
boolean - सही यदि ऑब्जेक्ट समान हैं; अन्यथा, गलत।
### hashCode() {#hashCode--}
```
public int hashCode()
```

एक विशेष प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**  
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।