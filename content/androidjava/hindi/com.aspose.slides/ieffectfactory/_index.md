---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: इफ़ेक्ट के उदाहरण बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

इफ़ेक्ट्स के उदाहरण बनाने की अनुमति देता है

--------------------

COM संगतता के लिए।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [createGlow()](#createGlow--) | Glow इफ़ेक्ट बनाता है। |
| [createInnerShadow()](#createInnerShadow--) | Inner shafow इफ़ेक्ट बनाता है। |
| [createOuterShadow()](#createOuterShadow--) | Outer shadow इफ़ेक्ट बनाता है। |
| [createPresetShadow()](#createPresetShadow--) | Preset shadow इफ़ेक्ट बनाता है। |
| [createReflection()](#createReflection--) | Reflection इफ़ेक्ट बनाता है। |
| [createSoftEdge()](#createSoftEdge--) | Soft Edge इफ़ेक्ट बनाता है। |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | ImageTransformOperationFactory को रिटर्न करता है। |
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


Inner shafow इफ़ेक्ट बनाता है।

**रिटर्न:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow इफ़ेक्ट।

### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


Outer shadow इफ़ेक्ट बनाता है।

**रिटर्न:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow इफ़ेक्ट।

### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


Preset shadow इफ़ेक्ट बनाता है।

**रिटर्न:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow इफ़ेक्ट।

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


ImageTransformOperationFactory को रिटर्न करता है। केवल-पढ़ने-योग्य [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)।

**रिटर्न:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)