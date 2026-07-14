---
title: ILightRigEffectiveData
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक अपरिवर्तनीय वस्तु जो प्रभावी लाइट रिग गुणों को समाहित करती है।
type: docs
url: /hi/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

एक अपरिवर्तनीय वस्तु जो प्रभावी लाइट रिग गुणों को समाहित करती है।

--------------------

यह इंटरफ़ेस [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) के हिस्से के रूप में उपयोग किया जाता है।

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [getDirection()](#getDirection--) | प्रकाश की दिशा। |
| [getLightType()](#getLightType--) | एक प्रीसेट प्रकाश जो आकार पर लागू किया जा सकता है। |
| [getRotation()](#getRotation--) | एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर घूर्णन के उपयोग से परिभाषित किया जाता है। |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

प्रकाश की दिशा। केवल-पढ़ने योग्य [LightingDirection](../../com.aspose.slides/lightingdirection)।

**रिटर्न:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

एक प्रीसेट प्रकाश जो आकार पर लागू किया जा सकता है। लाइट रिग 3D दृश्य के सापेक्ष विशिष्ट तरीके से अभिविमुखित प्रकाशों का समूह दर्शाता है। केवल-पढ़ने योग्य [LightRigPresetType](../../com.aspose.slides/lightrigpresettype)।

**रिटर्न:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

एक घूर्णन को अक्षांश निर्देशांक, देशांतर निर्देशांक, और अक्ष के चारों ओर घूर्णन के उपयोग से परिभाषित किया जाता है। लौटाए गए सरणी का पहला तत्व – अक्षांश, दूसरा – देशांतर, तीसरा – घूर्णन।

**रिटर्न:**
float[] - घूर्णन निर्देशांक फ़्लोट के रूप में[]