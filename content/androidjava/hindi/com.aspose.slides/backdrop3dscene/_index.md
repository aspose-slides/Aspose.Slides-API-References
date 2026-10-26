---
title: Backdrop3DScene
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफरेंस के माध्यम से
description: एक समतल को परिभाषित करता है जिसमें प्रभाव, जैसे चमक और छाया, उस आकार के सापेक्ष लागू होते हैं जिस पर इन्हें लागू किया जा रहा है।
type: docs
url: /hi/com.aspose.slides/backdrop3dscene/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

एक समतल को परिभाषित करता है जिसमें प्रभाव, जैसे चमक और छाया, उस आकार के सापेक्ष लागू होते हैं जिस पर उन्हें लागू किया जा रहा है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | एक सामान्य वेक्टर को लौटाता है या सेट करता है। |
| [setNormalVector(float[] value)](#setNormalVector-float---) | एक सामान्य वेक्टर को लौटाता है या सेट करता है। |
| [getAnchorPoint()](#getAnchorPoint--) | एक बिंदु को 3D स्थान में लौटाता है या सेट करता है। |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | एक बिंदु को 3D स्थान में लौटाता है या सेट करता है। |
| [getUpVector()](#getUpVector--) | ऊपर की दिशा दर्शाता हुआ एक वेक्टर को लौटाता है या सेट करता है। |
| [setUpVector(float[] value)](#setUpVector-float---) | ऊपर की दिशा दर्शाता हुआ एक वेक्टर को लौटाता है या सेट करता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल पढ़ने योग्य long.

**रिटर्न:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

एक सामान्य वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह विशेषता बैकड्रॉप समतल के चेहरे के सामान्य वेक्टर को परिभाषित करती है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**रिटर्न:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

एक सामान्य वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह विशेषता बैकड्रॉप समतल के चेहरे के सामान्य वेक्टर को परिभाषित करती है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

एक बिंदु को 3D स्थान में लौटाता है या सेट करता है। यह बिंदु वह बिंदु है जो बैकड्रॉप समतल को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**रिटर्न:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

एक बिंदु को 3D स्थान में लौटाता है या सेट करता है। यह बिंदु वह बिंदु है जो बैकड्रॉप समतल को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

ऊपर की दिशा दर्शाता हुआ एक वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह विशेषता बैकड्रॉप समतल के चेहरे के सापेक्ष ऊपर की दिशा दर्शाता हुआ वेक्टर परिभाषित करती है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**रिटर्न:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

ऊपर की दिशा दर्शाता हुआ एक वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह विशेषता बैकड्रॉप समतल के चेहरे के सापेक्ष ऊपर की दिशा दर्शाता हुआ वेक्टर परिभाषित करती है। वेक्टर 3 फ़्लोट मानों की सरणी द्वारा दर्शाया गया है जो X, Y और Z निर्देशांक को परिभाषित करती है। पढ़ने/लिखने योग्य float[]।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float[] |  |