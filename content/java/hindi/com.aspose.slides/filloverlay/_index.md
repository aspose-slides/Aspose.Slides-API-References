---
title: FillOverlay
second_title: Aspose.Slides for Java API संदर्भ
description: एक Fill Overlay प्रभाव का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/filloverlay/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

एक Fill Overlay प्रभाव का प्रतिनिधित्व करता है। एक Fill Overlay का उपयोग किसी वस्तु के लिए अतिरिक्त भराव निर्दिष्ट करने और दो भरावों को मिलाने के लिए किया जा सकता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill फ़ॉर्मेट। |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी Fill Overlay प्रभाव डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [FillOverlay](../../com.aspose.slides/filloverlay) वर्तमान [FillOverlay](../../com.aspose.slides/filloverlay) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. पढ़ने/लिखने योग्य [FillBlendMode](../../com.aspose.slides/fillblendmode).

**वापसी:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. पढ़ने/लिखने योग्य [FillBlendMode](../../com.aspose.slides/fillblendmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

विरासत लागू करके प्रभावी Fill Overlay प्रभाव डेटा प्राप्त करता है।

**वापसी:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - एक [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. केवल-पढ़ने योग्य long।

**वापसी:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

निर्धारित करता है कि निर्दिष्ट [FillOverlay](../../com.aspose.slides/filloverlay) वर्तमान [FillOverlay](../../com.aspose.slides/filloverlay) के बराबर है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए [FillOverlay](../../com.aspose.slides/filloverlay)। |

**वापसी:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**वापसी:**
int - A hash code for the current object.