---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 允許建立效果實例
type: docs
url: /zh-hant/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

允許建立效果的實例

--------------------

供 COM 相容性使用。
## 方法

| Method | Description |
| --- | --- |
| [createGlow()](#createGlow--) | 建立 Glow 效果。 |
| [createInnerShadow()](#createInnerShadow--) | 建立 Inner shafow 效果。 |
| [createOuterShadow()](#createOuterShadow--) | 建立 Outer shadow 效果。 |
| [createPresetShadow()](#createPresetShadow--) | 建立 Preset shadow 效果。 |
| [createReflection()](#createReflection--) | 建立 Reflection 效果。 |
| [createSoftEdge()](#createSoftEdge--) | 建立 Soft Edge 效果。 |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | 傳回 ImageTransformOperationFactory。 |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```


建立 Glow 效果。

**傳回：**
[IGlow](../../com.aspose.slides/iglow) - Glow 效果。
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```


建立 Inner shafow 效果。

**傳回：**
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow 效果。
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


建立 Outer shadow 效果。

**傳回：**
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow 效果。
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


建立 Preset shadow 效果。

**傳回：**
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow 效果。
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```


建立 Reflection 效果。

**傳回：**
[IReflection](../../com.aspose.slides/ireflection) - Reflection 效果。
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```


建立 Soft Edge 效果。

**傳回：**
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge 效果。
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```


傳回 ImageTransformOperationFactory。唯讀 [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)。

**傳回：**
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)