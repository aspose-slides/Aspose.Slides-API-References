---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /hi/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | प्रकाश की दिशा। |
| [setDirection(int value)](#setDirection-int-) | प्रकाश की दिशा। |
| [getLightType()](#getLightType--) | एक प्रीसेट लाइट राइट जो किसी आकार पर लागू किया जा सकता है। |
| [setLightType(int value)](#setLightType-int-) | एक प्रीसेट लाइट राइट जो किसी आकार पर लागू किया जा सकता है। |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक रोटेशन को अक्ष के बारे में अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश एवं देशांतर निर्देशांकों के रूप में एक क्रांति का उपयोग करके परिभाषित किया जाता है। |
| [getRotation()](#getRotation--) | एक रोटेशन को अक्ष के बारे में अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश एवं देशांतर निर्देशांकों के रूप में एक क्रांति का उपयोग करके परिभाषित किया जाता है। |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

प्रकाश की दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection).

**रिटर्न:**
int

### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

प्रकाश की दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

एक प्रीसेट लाइट राइट जो किसी आकार पर लागू किया जा सकता है। लाइट रिग 3D दृश्य के सापेक्ष विशिष्ट दिशा में व्यवस्थित लाइटों का समूह दर्शाता है। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**रिटर्न:**
int

### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

एक प्रीसेट लाइट राइट जो किसी आकार पर लागू किया जा सकता है। लाइट रिग 3D दृश्य के सापेक्ष विशिष्ट दिशा में व्यवस्थित लाइटों का समूह दर्शाता है। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

एक रोटेशन को अक्ष के बारे में अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश एवं देशांतर निर्देशांकों के रूप में एक क्रांति का उपयोग करके परिभाषित किया जाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| latitude | float | अक्षांश निर्देशांक float |
| longitude | float | देशांतर निर्देशांक float |
| revolution | float | क्रांति निर्देशांक float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक रोटेशन को अक्ष के बारे में अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्षांश एवं देशांतर निर्देशांकों के रूप में एक क्रांति का उपयोग करके परिभाषित किया जाता है। रिटर्न एरे में पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति।

**रिटर्न:**
float[] - घूर्णन निर्देशांक float[] के रूप में