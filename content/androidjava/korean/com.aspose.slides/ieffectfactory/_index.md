---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 효과 인스턴스를 생성할 수 있습니다
type: docs
url: /ko/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

효과 인스턴스를 생성할 수 있습니다

--------------------

COM 호환성을 위해.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createGlow()](#createGlow--) | Glow 효과를 생성합니다. |
| [createInnerShadow()](#createInnerShadow--) | Inner shafow 효과를 생성합니다. |
| [createOuterShadow()](#createOuterShadow--) | Outer shadow 효과를 생성합니다. |
| [createPresetShadow()](#createPresetShadow--) | Preset shadow 효과를 생성합니다. |
| [createReflection()](#createReflection--) | Reflection 효과를 생성합니다. |
| [createSoftEdge()](#createSoftEdge--) | Soft Edge 효과를 생성합니다. |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | ImageTransformOperationFactory를 반환합니다. |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```

Glow 효과를 생성합니다.

**반환:**  
[IGlow](../../com.aspose.slides/iglow) - Glow 효과.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```

Inner shafow 효과를 생성합니다.

**반환:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow 효과.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```

Outer shadow 효과를 생성합니다.

**반환:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow 효과.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```

Preset shadow 효과를 생성합니다.

**반환:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow 효과.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```

Reflection 효과를 생성합니다.

**반환:**  
[IReflection](../../com.aspose.slides/ireflection) - Reflection 효과.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```

Soft Edge 효과를 생성합니다.

**반환:**  
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge 효과.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```

ImageTransformOperationFactory를 반환합니다. 읽기 전용 [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory).

**반환:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)