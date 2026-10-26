---
title: Backdrop3DScene
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक समतल को परिभाषित करता है जिसमें ग्लो और शैडो जैसे प्रभाव उस आकार के सापेक्ष लागू होते हैं जिस पर वे लागू किए जा रहे हैं।
type: docs
url: /hi/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

एक प्लेन को परिभाषित करता है जिसमें प्रभाव, जैसे ग्लो और शैडो, उस आकार के सापेक्ष लागू होते हैं जिससे वे लागू हो रहे हैं।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | एक सामान्य वेक्टर को वापस करता है या सेट करता है। |
| [setNormalVector(float[] value)](#setNormalVector-float---) | एक सामान्य वेक्टर को वापस करता है या सेट करता है। |
| [getAnchorPoint()](#getAnchorPoint--) | 3D स्थान में एक बिंदु को वापस करता है या सेट करता है। |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 3D स्थान में एक बिंदु को वापस करता है या सेट करता है। |
| [getUpVector()](#getUpVector--) | ऊपर की दिशा दर्शाने वाले वेक्टर को वापस करता है या सेट करता है। |
| [setUpVector(float[] value)](#setUpVector-float---) | ऊपर की दिशा दर्शाने वाले वेक्टर को वापस करता है या सेट करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long.

**वापसी:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

एक सामान्य वेक्टर को वापस करता है या सेट करता है। अधिक स्पष्ट रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन के चेहरे के लम्बवत एक वेक्टर को परिभाषित करता है। वेक्टर 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**वापसी:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

एक सामान्य वेक्टर को वापस करता है या सेट करता है। अधिक स्पष्ट रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन के चेहरे के लम्बवत एक वेक्टर को परिभाषित करता है। वेक्टर 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

एक बिंदु को वापस करता है या सेट करता है जो 3D स्थान में बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**वापसी:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

एक बिंदु को वापस करता है या सेट करता है जो 3D स्थान में बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

ऊपर की दिशा दर्शाने वाले वेक्टर को वापस करता है या सेट करता है। अधिक स्पष्ट रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन के चेहरे के सापेक्ष ऊपर की दिशा दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**वापसी:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

ऊपर की दिशा दर्शाने वाले वेक्टर को वापस करता है या सेट करता है। अधिक स्पष्ट रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन के चेहरे के सापेक्ष ऊपर की दिशा दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 float मानों की array द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float[] |  |