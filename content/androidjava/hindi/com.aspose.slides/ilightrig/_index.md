---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: Represents LightRig.
type: docs
url: /hi/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

LightRig का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | लाइट दिशा। |
| [setDirection(int value)](#setDirection-int-) | लाइट दिशा। |
| [getLightType()](#getLightType--) | एक प्रीसेट लाइट राइट जो एक आकृति पर लागू किया जा सकता है। |
| [setLightType(int value)](#setLightType-int-) | एक प्रीसेट लाइट राइट जो एक आकृति पर लागू किया जा सकता है। |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के चारों ओर एक क्रांति के उपयोग से परिभाषित किया जाता है, जो अक्षांश और देशांतर निर्देशांक के रूप में होते हैं। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के चारों ओर एक क्रांति के उपयोग से परिभाषित किया जाता है, जो अक्षांश और देशांतर निर्देशांक के रूप में होते हैं। |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


लाइट दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection)।

**वापसी:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```


लाइट दिशा। पढ़ें/लिखें [LightingDirection](../../com.aspose.slides/lightingdirection)।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


एक प्रीसेट लाइट राइट जो एक आकृति पर लागू किया जा सकता है। Light rig एक समूह लाइट्स का प्रतिनिधित्व करता है जो 3D दृश्य के सापेक्ष एक विशिष्ट तरीके से अभिविन्यासित होते हैं। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**वापसी:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```


एक प्रीसेट लाइट राइट जो एक आकृति पर लागू किया जा सकता है। Light rig एक समूह लाइट्स का प्रतिनिधित्व करता है जो 3D दृश्य के सापेक्ष एक विशिष्ट तरीके से अभिविन्यासित होते हैं। पढ़ें/लिखें [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के चारों ओर एक क्रांति के उपयोग से परिभाषित किया जाता है, जो अक्षांश और देशांतर निर्देशांक के रूप में होते हैं।

**परिमाण:**
| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| latitude | float | अक्षांश निर्देशांक फ़्लोट |
| longitude | float | देशांतर निर्देशांक फ़्लोट |
| revolution | float | क्रांति निर्देशांक फ़्लोट |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक और अक्ष के चारों ओर एक क्रांति के उपयोग से परिभाषित किया जाता है, जो अक्षांश और देशांतर निर्देशांक के रूप में होते हैं। लौटाए गए array का पहला तत्व - अक्षांश, दूसरा - देशांतर, तीसरा - क्रांति।

**वापसी:**
float[] - घूर्णन निर्देशांक फ़्लोट[] के रूप में