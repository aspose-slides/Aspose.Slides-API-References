---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: अपरिवर्तनीय वस्तु जो प्रभावी कैमरा गुणों को समाहित करती है।
type: docs
url: /hi/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

अपरिवर्तनीय वस्तु जो प्रभावी कैमरा गुणों को समाहित करती है।

--------------------

यह इंटरफ़ेस [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) का हिस्सा के रूप में प्रयोग किया जाता है।

## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | कैमरा प्रकार। |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र)। |
| [getZoom()](#getZoom--) | कैमरा ज़ूम (प्रतिशत में धनात्मक मान)। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश-देशांतर निर्देशांक के रूप में अक्ष के चारों ओर क्रांति के उपयोग द्वारा परिभाषित किया जाता है। |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

कैमरा प्रकार। केवल पढ़ने योग्य [CameraPresetType](../../com.aspose.slides/camerapresettype).

**रिटर्न:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र)। केवल पढ़ने योग्य float.

**रिटर्न:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

कैमरा ज़ूम (प्रतिशत में धनात्मक मान)। केवल पढ़ने योग्य float.

**रिटर्न:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश-देशांतर निर्देशांक के रूप में अक्ष के चारों ओर क्रांति के उपयोग द्वारा परिभाषित किया जाता है। लौटाए गए सरणी में पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति। यदि कोई घूर्णन परिभाषित नहीं है तो null लौटाता है।

**रिटर्न:**
float[] - float[] के रूप में घूर्णन मानों की सरणी।