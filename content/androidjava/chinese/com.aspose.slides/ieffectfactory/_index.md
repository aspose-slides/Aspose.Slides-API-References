---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允许创建效果实例
type: docs
url: /zh/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

允许创建效果实例

--------------------

用于 COM 兼容性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [createGlow()](#createGlow--) | 创建 Glow 效果。 |
| [createInnerShadow()](#createInnerShadow--) | 创建 Inner shafow 效果。 |
| [createOuterShadow()](#createOuterShadow--) | 创建 Outer shadow 效果。 |
| [createPresetShadow()](#createPresetShadow--) | 创建 Preset shadow 效果。 |
| [createReflection()](#createReflection--) | 创建 Reflection 效果。 |
| [createSoftEdge()](#createSoftEdge--) | 创建 Soft Edge 效果。 |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | 返回 ImageTransformOperationFactory。 |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```

创建 Glow 效果。

**返回:**  
[IGlow](../../com.aspose.slides/iglow) - Glow effect.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```

创建 Inner shafow 效果。

**返回:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow effect.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```

创建 Outer shadow 效果。

**返回:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow effect.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```

创建 Preset shadow 效果。

**返回:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow effect.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```

创建 Reflection 效果。

**返回:**  
[IReflection](../../com.aspose.slides/ireflection) - Reflection effect.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```

创建 Soft Edge 效果。

**返回:**  
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge effect.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```

返回 ImageTransformOperationFactory。只读 [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)。

**返回:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)