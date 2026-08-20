---
title: IEffectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create effects instances
type: docs
url: /hi/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

इफ़ेक्ट्स के इंस्टेंस बनाने की अनुमति देता है

--------------------

COM संगतता के लिए.

## विधियां

| विधि | विवरण |
| --- | --- |
| [createGlow()](#createGlow--) | Glow इफ़ेक्ट बनाता है। |
| [createInnerShadow()](#createInnerShadow--) | Inner शैडो इफ़ेक्ट बनाता है। |
| [createOuterShadow()](#createOuterShadow--) | Outer शैडो इफ़ेक्ट बनाता है। |
| [createPresetShadow()](#createPresetShadow--) | Preset शैडो इफ़ेक्ट बनाता है। |
| [createReflection()](#createReflection--) | Reflection इफ़ेक्ट बनाता है। |
| [createSoftEdge()](#createSoftEdge--) | Soft Edge इफ़ेक्ट बनाता है। |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | ImageTransformOperationFactory लौटाता है। |

### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```

Glow इफ़ेक्ट बनाता है।

**रिटर्न:**
[IGlow](../../com.aspose.slides/iglow) - Glow इफ़ेक्ट।

### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```

Inner शैडो इफ़ेक्ट बनाता है।

**रिटर्न:**
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner शैडो इफ़ेक्ट।

### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```

Outer शैडो इफ़ेक्ट बनाता है।

**रिटर्न:**
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer शैडो इफ़ेक्ट।

### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```

Preset शैडो इफ़ेक्ट बनाता है।

**रिटर्न:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset शैडो इफ़ेक्ट।

### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```

Reflection इफ़ेक्ट बनाता है।

**रिटर्न:**
[IReflection](../../com.aspose.slides/ireflection) - Reflection इफ़ेक्ट।

### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```

Soft Edge इफ़ेक्ट बनाता है।

**रिटर्न:**
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge इफ़ेक्ट।

### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```

ImageTransformOperationFactory लौटाता है। केवल-पढ़ने योग्य [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)।

**रिटर्न:**
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)