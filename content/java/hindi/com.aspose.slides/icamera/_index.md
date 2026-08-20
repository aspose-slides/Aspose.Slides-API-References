---
title: ICamera
second_title: Aspose.Slides for Java API Reference
description: Represents Camera.
type: docs
url: /hi/com.aspose.slides/icamera/
---```
public interface ICamera
```

कैमरा का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)। |
| [setCameraType(int value)](#setCameraType-int-) | कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)। |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र) पढ़ें/लिखें float। |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र) पढ़ें/लिखें float। |
| [getZoom()](#getZoom--) | कैमरा ज़ूम (प्रतिशत में सकारात्मक मान) पढ़ें/लिखें float। |
| [setZoom(float value)](#setZoom-float-) | कैमरा ज़ूम (प्रतिशत में सकारात्मक मान) पढ़ें/लिखें float। |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक घूर्णन को अक्ष के चारों ओर लैटिट्यूड निर्देशांक, लॉन्गिट्यूड निर्देशांक और उनका उपयोग करके घूर्णन द्वारा परिभाषित किया जाता है। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्ष के चारों ओर लैटिट्यूड निर्देशांक, लॉन्गिट्यूड निर्देशांक और उनका उपयोग करके घूर्णन द्वारा परिभाषित किया जाता है। |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)।

**वापसी:**
int

### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र) पढ़ें/लिखें float।

**वापसी:**
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

कैमरा FOV (0-180 डिग्री, दृश्य क्षेत्र) पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

कैमरा ज़ूम (प्रतिशत में सकारात्मक मान) पढ़ें/लिखें float।

**वापसी:**
float

### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

कैमरा ज़ूम (प्रतिशत में सकारात्मक मान) पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

एक घूर्णन को अक्ष के चारों ओर लैटिट्यूड निर्देशांक, लॉन्गिट्यूड निर्देशांक और उनका उपयोग करके घूर्णन द्वारा परिभाषित किया जाता है। यदि किसी भी निर्देशांक का मान Float.NaN है, तो सभी घूर्णन अपरिभाषित हो जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| latitude | float | लैटिट्यूड मान float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक घूर्णन को अक्ष के चारों ओर लैटिट्यूड निर्देशांक, लॉन्गिट्यूड निर्देशांक और उनका उपयोग करके घूर्णन द्वारा परिभाषित किया जाता है। पहला तत्व लौटाए गए एरे में - लैटिट्यूड, दूसरा - लॉन्गिट्यूड, तीसरा - क्रांति। यदि कोई घूर्णन परिभाषित नहीं है तो null लौटाता है।

**वापसी:**
float[] - Array of rotation values as float[].