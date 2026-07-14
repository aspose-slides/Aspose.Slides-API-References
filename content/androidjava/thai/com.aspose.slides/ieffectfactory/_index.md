---
title: IEffectFactory
second_title: Aspose.Slides for Android via Java API Reference
description: อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์
type: docs
url: /th/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์

--------------------

เพื่อความเข้ากันได้กับ COM.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createGlow()](#createGlow--) | สร้างเอฟเฟกต์ Glow. |
| [createInnerShadow()](#createInnerShadow--) | สร้างเอฟเฟกต์ Inner shafow. |
| [createOuterShadow()](#createOuterShadow--) | สร้างเอฟเฟกต์ Outer shadow. |
| [createPresetShadow()](#createPresetShadow--) | สร้างเอฟเฟกต์ Preset shadow. |
| [createReflection()](#createReflection--) | สร้างเอฟเฟกต์ Reflection. |
| [createSoftEdge()](#createSoftEdge--) | สร้างเอฟเฟกต์ Soft Edge. |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | คืนค่า ImageTransformOperationFactory. |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```


สร้างเอฟเฟกต์ Glow.

**คืนค่า:**
[IGlow](../../com.aspose.slides/iglow) - เอฟเฟกต์ Glow.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```


สร้างเอฟเฟกต์ Inner shafow.

**คืนค่า:**
[IInnerShadow](../../com.aspose.slides/iinnershadow) - เอฟเฟกต์ Inner shafow.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


สร้างเอฟเฟกต์ Outer shadow.

**คืนค่า:**
[IOuterShadow](../../com.aspose.slides/ioutershadow) - เอฟเฟกต์ Outer shadow.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


สร้างเอฟเฟกต์ Preset shadow.

**คืนค่า:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - เอฟเฟกต์ Preset shadow.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```


สร้างเอฟเฟกต์ Reflection.

**คืนค่า:**
[IReflection](../../com.aspose.slides/ireflection) - เอฟเฟกต์ Reflection.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```


สร้างเอฟเฟกต์ Soft Edge.

**คืนค่า:**
[ISoftEdge](../../com.aspose.slides/isoftedge) - เอฟเฟกต์ Soft Edge.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```


คืนค่า ImageTransformOperationFactory. อ่านอย่างเดียว [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory).

**คืนค่า:**
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)