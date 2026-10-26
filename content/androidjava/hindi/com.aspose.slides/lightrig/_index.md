---
title: LightRig
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: LightRig का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/lightrig/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)  
```
public final class LightRig extends PVIObject implements ILightRig
```

LightRig का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | प्रकाश दिशा। |
| [setDirection(int value)](#setDirection-int-) | प्रकाश दिशा। |
| [getLightType()](#getLightType--) | एक प्रीसेट लाइट राइट का प्रतिनिधित्व करता है जिसे आकार पर लागू किया जा सकता है। |
| [setLightType(int value)](#setLightType-int-) | एक प्रीसेट लाइट राइट का प्रतिनिधित्व करता है जिसे आकार पर लागू किया जा सकता है। |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक घुमाव को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है। |
| [getRotation()](#getRotation--) | एक घुमाव को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने-योग्य long.

**वापसी:**  
long

### getDirection() {#getDirection--}
```
public final int getDirection()
```

प्रकाश दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection)।

**वापसी:**  
int

### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

प्रकाश दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

एक प्रीसेट लाइट राइट का प्रतिनिधित्व करता है जिसे आकार पर लागू किया जा सकता है। लाइट रिग 3D दृश्य के सापेक्ष विशिष्ट रूप में व्यवस्थित प्रकाश समूह का प्रतिनिधित्व करता है। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**वापसी:**  
int

### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

एक प्रीसेट लाइट राइट का प्रतिनिधित्व करता है जिसे आकार पर लागू किया जा सकता है। लाइट रिग 3D दृश्य के सापेक्ष विशिष्ट रूप में व्यवस्थित प्रकाश समूह का प्रतिनिधित्व करता है। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

एक घुमाव को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है। यदि किसी भी निर्देशांक मान को Float.NaN किया जाता है, तो सभी घुमाव अनिर्धारित होते हैं।

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

एक घुमाव को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर एक क्रांति के उपयोग द्वारा परिभाषित किया जाता है। पहले तत्व में लौटाए गए एरे - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति। यदि कोई घुमाव परिभाषित नहीं है तो null लौटाता है।

**वापसी:**  
float[]