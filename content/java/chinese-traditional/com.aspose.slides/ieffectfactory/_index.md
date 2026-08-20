---
title: IEffectFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create effects instances
type: docs
url: /zh-hant/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

允許建立效果的實例

--------------------

用於 COM 相容性。
## 方法

| Method | Description |
| --- | --- |
| [createGlow()](#createGlow--) | 建立 Glow 效果。 |
| [createInnerShadow()](#createInnerShadow--) | 建立內部陰影效果。 |
| [createOuterShadow()](#createOuterShadow--) | 建立外部陰影效果。 |
| [createPresetShadow()](#createPresetShadow--) | 建立預設陰影效果。 |
| [createReflection()](#createReflection--) | 建立反射效果。 |
| [createSoftEdge()](#createSoftEdge--) | 建立柔和邊緣效果。 |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | 傳回 ImageTransformOperationFactory。 |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```


建立 Glow 效果。

**傳回:**
[IGlow](../../com.aspose.slides/iglow) - Glow effect.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```


建立內部陰影效果。

**傳回:**
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow effect.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


建立外部陰影效果。

**傳回:**
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow effect.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


建立預設陰影效果。

**傳回:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow effect.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```


建立反射效果。

**傳回:**
[IReflection](../../com.aspose.slides/ireflection) - Reflection effect.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```


建立柔和邊緣效果。

**傳回:**
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge effect.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```


傳回 ImageTransformOperationFactory。唯讀 [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)。

**傳回:**
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)