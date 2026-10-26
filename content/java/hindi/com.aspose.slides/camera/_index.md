---
title: Camera
second_title: Aspose.Slides for Java API संदर्भ
description: कैमरा का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/camera/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)  
```
public final class Camera extends PVIObject implements ICamera
```

कैमरा का प्रतिनिधित्व करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | कैमरा प्रकार। |
| [setCameraType(int value)](#setCameraType-int-) | कैमरा प्रकार। |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | कैमरा FOV (0-180 डिग्री, दृश्य का क्षेत्र)। |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | कैमरा FOV (0-180 डिग्री, दृश्य का क्षेत्र)। |
| [getZoom()](#getZoom--) | कैमरा ज़ूम (प्रतिशत में सकारात्मक मान)। |
| [setZoom(float value)](#setZoom-float-) | कैमरा ज़ूम (प्रतिशत में सकारात्मक मान)। |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक घूर्णन द्वारा, जो अक्षांश और देशांतर निर्देशांक के रूप में उपयोग किया जाता है, परिभाषित किया जाता है। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक घूर्णन द्वारा, जो अक्षांश और देशांतर निर्देशांक के रूप में उपयोग किया जाता है, परिभाषित किया जाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य लंबा।

**रिटर्न:**  
long

### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

कैमरा प्रकार। पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)।

**रिटर्न:**  
int

### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

कैमरा प्रकार। पढ़ें/लिखें [CameraPresetType](../../com.aspose.slides/camerapresettype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

कैमरा FOV (0-180 डिग्री, दृश्य का क्षेत्र)। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

कैमरा FOV (0-180 डिग्री, दृश्य का क्षेत्र)। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```

कैमरा ज़ूम (प्रतिशत में सकारात्मक मान)। पढ़ें/लिखें float।

**रिटर्न:**  
float

### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

कैमरा ज़ूम (प्रतिशत में सकारात्मक मान)। पढ़ें/लिखें float।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक घूर्णन द्वारा, जो अक्षांश और देशांतर निर्देशांक के रूप में उपयोग किया जाता है, परिभाषित किया जाता है। यदि किसी भी निर्देशांक का मान Float.NaN है, तो सभी घूर्णन अपरिभाषित होते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक घूर्णन द्वारा, जो अक्षांश और देशांतर निर्देशांक के रूप में उपयोग किया जाता है, परिभाषित किया जाता है। लौटाए गए array का पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - घूर्णन। यदि कोई घूर्णन परिभाषित नहीं है तो null लौटाता है।

**रिटर्न:**  
float[]