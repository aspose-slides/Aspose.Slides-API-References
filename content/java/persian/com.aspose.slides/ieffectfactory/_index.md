---
title: IEffectFactory
second_title: Aspose.Slides برای Java مرجع API
description: به ایجاد نمونه‌های افکت‌ها اجازه می‌دهد
type: docs
url: /fa/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

به ایجاد نمونه‌های افکت‌ها اجازه می‌دهد

--------------------

برای سازگاری با COM.
## متدها

| متد | توضیح |
| --- | --- |
| [createGlow()](#createGlow--) | یک افکت Glow ایجاد می‌کند. |
| [createInnerShadow()](#createInnerShadow--) | یک افکت Inner shafow ایجاد می‌کند. |
| [createOuterShadow()](#createOuterShadow--) | یک افکت Outer shadow ایجاد می‌کند. |
| [createPresetShadow()](#createPresetShadow--) | یک افکت Preset shadow ایجاد می‌کند. |
| [createReflection()](#createReflection--) | یک افکت Reflection ایجاد می‌کند. |
| [createSoftEdge()](#createSoftEdge--) | یک افکت Soft Edge ایجاد می‌کند. |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | ImageTransformOperationFactory را باز می‌گرداند. |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```

یک افکت Glow ایجاد می‌کند.

**بازگشت:**  
[IGlow](../../com.aspose.slides/iglow) - Glow افکت.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```

یک افکت Inner shafow ایجاد می‌کند.

**بازگشت:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow افکت.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```

یک افکت Outer shadow ایجاد می‌کند.

**بازگشت:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow افکت.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```

یک افکت Preset shadow ایجاد می‌کند.

**بازگشت:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow افکت.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```

یک افکت Reflection ایجاد می‌کند.

**بازگشت:**  
[IReflection](../../com.aspose.slides/ireflection) - Reflection افکت.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```

یک افکت Soft Edge ایجاد می‌کند.

**بازگشت:**  
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge افکت.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```

باز می‌گرداند ImageTransformOperationFactory. فقط-خواندنی [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory).

**بازگشت:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)