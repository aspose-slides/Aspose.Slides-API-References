---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create effects instances
type: docs
url: /ja/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

エフェクトのインスタンスを作成することができます。

--------------------

COM 互換性のため。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createGlow()](#createGlow--) | Glow エフェクトを作成します。 |
| [createInnerShadow()](#createInnerShadow--) | Inner shafow エフェクトを作成します。 |
| [createOuterShadow()](#createOuterShadow--) | Outer shadow エフェクトを作成します。 |
| [createPresetShadow()](#createPresetShadow--) | Preset shadow エフェクトを作成します。 |
| [createReflection()](#createReflection--) | Reflection エフェクトを作成します。 |
| [createSoftEdge()](#createSoftEdge--) | Soft Edge エフェクトを作成します。 |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | ImageTransformOperationFactory を返します。 |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```

Glow エフェクトを作成します。

**戻り値:**  
[IGlow](../../com.aspose.slides/iglow) - Glow エフェクト。
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```

Inner shafow エフェクトを作成します。

**戻り値:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow エフェクト。
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```

Outer shadow エフェクトを作成します。

**戻り値:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow エフェクト。
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```

Preset shadow エフェクトを作成します。

**戻り値:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow エフェクト。
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```

Reflection エフェクトを作成します。

**戻り値:**  
[IReflection](../../com.aspose.slides/ireflection) - Reflection エフェクト。
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```

Soft Edge エフェクトを作成します。

**戻り値:**  
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge エフェクト。
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```

ImageTransformOperationFactory を返します。 読み取り専用 [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)。

**戻り値:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)