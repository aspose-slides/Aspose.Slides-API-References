---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective light rig properties.
type: docs
url: /hi/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

एक अपरिवर्तनीय वस्तु जिसमें प्रभावी लाइट रिग गुण होते हैं।

--------------------

यह इंटरफ़ेस [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) का एक भाग के रूप में उपयोग किया जाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | लाइट दिशा। |
| [getLightType()](#getLightType--) | एक प्रीसेट लाइट राइट को दर्शाता है जिसे shape पर लागू किया जा सकता है। |
| [getRotation()](#getRotation--) | एक रोटेशन को latitude निर्देशांक, longitude निर्देशांक और अक्ष के चारों ओर latitude और longitude निर्देशांक के रूप में एक revolution के उपयोग से परिभाषित किया जाता है। |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

लाइट दिशा। केवल-पढ़ने योग्य [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

एक प्रीसेट लाइट राइट को दर्शाता है जिसे shape पर लागू किया जा सकता है। लाइट रिग एक समूह लाइट्स को दर्शाता है जो 3D सीन के सापेक्ष एक विशिष्ट तरीके से अभिविन्यस्त होते हैं। केवल-पढ़ने योग्य [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक रोटेशन को latitude निर्देशांक, longitude निर्देशांक और अक्ष के चारों ओर latitude और longitude निर्देशांक के रूप में एक revolution के उपयोग से परिभाषित किया जाता है। रिटर्न एरे का पहला तत्व - latitude, दूसरा - longitude, तीसरा - revolution।

**Returns:**
float[] - Rotation coordinates as float[]