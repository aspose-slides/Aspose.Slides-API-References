---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /hi/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

स्थायी वस्तु जो प्रभावी कैमरा गुणों को समेटे हुए है।

--------------------

यह इंटरफ़ेस [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) का हिस्सा के रूप में उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getCameraType()](#getCameraType--) | कैमरा प्रकार। |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | कैमरा FOV (0-180 deg, field of View)। |
| [getZoom()](#getZoom--) | कैमरा जूम (percentage में सकारात्मक मान)। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्ष के चारों ओर अक्षांश निर्देशांक, देशांश निर्देशांक और एक परिक्रमा के उपयोग द्वारा परिभाषित किया जाता है, जहाँ अक्षांश और देशांश निर्देशांक का उपयोग किया जाता है। |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


कैमरा प्रकार। केवल-पढ़ने योग्य [CameraPresetType](../../com.aspose.slides/camerapresettype)।

**वापसी:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


कैमरा FOV (0-180 deg, field of View)। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


कैमरा जूम (percentage में सकारात्मक मान)। केवल-पढ़ने योग्य float।

**वापसी:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


एक घूर्णन को अक्ष के चारों ओर अक्षांश निर्देशांक, देशांश निर्देशांक और एक परिक्रमा के उपयोग द्वारा परिभाषित किया जाता है, जहाँ अक्षांश और देशांश निर्देशांक का उपयोग किया जाता है। वापसी सरणी का पहला तत्व - अक्षांश, दूसरा - देशांश, तीसरा - परिक्रमा। यदि कोई घूर्णन परिभाषित नहीं है तो null लौटाता है।

**वापसी:**
float[] - float[] के रूप में घूर्णन मानों की सरणी।