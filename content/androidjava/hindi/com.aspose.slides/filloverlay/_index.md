---
title: FillOverlay
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक Fill Overlay प्रभाव को प्रतिनिधित्व करता है।
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

एक Fill Overlay प्रभाव का प्रतिनिधित्व करता है। एक fill overlay का उपयोग किसी ऑब्जेक्ट के लिए अतिरिक्त fill निर्दिष्ट करने और दो fills को मिलाने के लिए किया जा सकता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | विरासत लागू किए गए प्रभावी Fill Overlay डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट [FillOverlay](../../com.aspose.slides/filloverlay) वर्तमान [FillOverlay](../../com.aspose.slides/filloverlay) के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है। |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. पढ़ें/लिखें [FillBlendMode](../../com.aspose.slides/fillblendmode).

**रिटर्न:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. पढ़ें/लिखें [FillBlendMode](../../com.aspose.slides/fillblendmode).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

विरासत लागू किए गए प्रभावी Fill Overlay डेटा प्राप्त करता है।

**रिटर्न:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण. केवल पढ़ने योग्य long.

**रिटर्न:**
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

**रिटर्न:**
boolean - सही यदि ऑब्जेक्ट समान हैं; अन्यथा, गलत।

### hashCode() {#hashCode--}
```
public int hashCode()
```

विशिष्ट प्रकार के लिए हैश फ़ंक्शन के रूप में कार्य करता है।

**रिटर्न:**
int - वर्तमान ऑब्जेक्ट के लिए एक हैश कोड।