---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /hi/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

एक समतल को परिभाषित करता है जिसमें चमक और छाया जैसी प्रभावों को उस आकार के सापेक्ष लागू किया जाता है जिस पर वे लागू किए जा रहे हैं।
## विधियाँ

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


एक सामान्य वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन की सतह के लम्बवत एक वेक्टर को परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**रिटर्न:**  
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


एक सामान्य वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन की सतह के लम्बवत एक वेक्टर को परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


3D स्थान में एक बिंदु को लौटाता है या सेट करता है। यह बिंदु वह बिंदु है जो बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**रिटर्न:**  
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


3D स्थान में एक बिंदु को लौटाता है या सेट करता है। यह बिंदु वह बिंदु है जो बैकड्रॉप प्लेन को एंकर करता है। 3D बिंदु 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


ऊपर की दिशा दर्शाने वाला वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन की सतह के सापेक्ष ऊपर की दिशा को दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**रिटर्न:**  
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


ऊपर की दिशा दर्शाने वाला वेक्टर को लौटाता है या सेट करता है। अधिक सटीक रूप से, यह एट्रिब्यूट बैकड्रॉप प्लेन की सतह के सापेक्ष ऊपर की दिशा को दर्शाने वाला वेक्टर परिभाषित करता है। वेक्टर 3 फ़्लोट मानों की एरे द्वारा दर्शाया जाता है जो X, Y और Z निर्देशांक को परिभाषित करते हैं। पढ़ें/लिखें float[]।

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |