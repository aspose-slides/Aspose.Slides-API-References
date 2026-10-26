---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: कैमरा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icamera/
---```
public interface ICamera
```

कैमरा का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCameraType()](#getCameraType--) | कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | कैमरा FOV (0-180 deg, field of View) पढ़ें/लिखें float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | कैमरा FOV (0-180 deg, field of View) पढ़ें/लिखें float. |
| [getZoom()](#getZoom--) | कैमरा ज़ूम (पॉज़िटिव वैल्यू प्रतिशत में) पढ़ें/लिखें float. |
| [setZoom(float value)](#setZoom-float-) | कैमरा ज़ूम (पॉज़िटिव वैल्यू प्रतिशत में) पढ़ें/लिखें float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक रोटेशन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के बारे में घूर्णन द्वारा परिभाषित किया जाता है। |
| [getRotation()](#getRotation--) | एक रोटेशन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के बारे में घूर्णन द्वारा परिभाषित किया जाता है। |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype).

**रिटर्न:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```

कैमरा प्रकार पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype).

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

कैमरा FOV (0-180 deg, field of View) पढ़ें/लिखें float.

**रिटर्न:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```

कैमरा FOV (0-180 deg, field of View) पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

कैमरा ज़ूम (पॉज़िटिव वैल्यू प्रतिशत में) पढ़ें/लिखें float.

**रिटर्न:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```

कैमरा ज़ूम (पॉज़िटिव वैल्यू प्रतिशत में) पढ़ें/लिखें float.

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

एक रोटेशन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के बारे में घूर्णन द्वारा परिभाषित किया जाता है। यदि किसी भी निर्देशांक मान की मान Float.NaN है, तो सभी रोटेशन अनिर्धारित होते हैं।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| latitude | float | अक्षांश मान float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक रोटेशन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के बारे में घूर्णन द्वारा परिभाषित किया जाता है। रिटर्न एरे का पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - घूर्णन। यदि कोई रोटेशन परिभाषित नहीं है तो null लौटाता है।

**रिटर्न:**
float[] - रोटेशन मानों का एरे जैसा float[].