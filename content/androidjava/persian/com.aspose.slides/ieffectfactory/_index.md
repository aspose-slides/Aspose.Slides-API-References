---
title: IEffectFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: اجازه می‌دهد نمونه‌های افکت‌ها ایجاد شوند
type: docs
url: /fa/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

اجازه می‌دهد تا نمونه‌های افکت‌ها ایجاد شوند

--------------------

برای سازگاری با COM.
## متدها

| Method | Description |
| --- | --- |
| [createGlow()](#createGlow--) | یک افکت Glow ایجاد می‌کند. |
| [createInnerShadow()](#createInnerShadow--) | یک افکت Inner shafow ایجاد می‌کند. |
| [createOuterShadow()](#createOuterShadow--) | یک افکت Outer shadow ایجاد می‌کند. |
| [createPresetShadow()](#createPresetShadow--) | یک افکت Preset shadow ایجاد می‌کند. |
| [createReflection()](#createReflection--) | یک افکت Reflection ایجاد می‌کند. |
| [createSoftEdge()](#createSoftEdge--) | یک افکت Soft Edge ایجاد می‌کند. |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | یک ImageTransformOperationFactory برمی‌گرداند. |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```


یک افکت Glow ایجاد می‌کند.

**باز می‌گرداند:**  
[IGlow](../../com.aspose.slides/iglow) - افکت Glow.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```


یک افکت Inner shafow ایجاد می‌کند.

**باز می‌گرداند:**  
[IInnerShadow](../../com.aspose.slides/iinnershadow) - افکت Inner shafow.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


یک افکت Outer shadow ایجاد می‌کند.

**باز می‌گرداند:**  
[IOuterShadow](../../com.aspose.slides/ioutershadow) - افکت Outer shadow.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


یک افکت Preset shadow ایجاد می‌کند.

**باز می‌گرداند:**  
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - افکت Preset shadow.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```


یک افکت Reflection ایجاد می‌کند.

**باز می‌گرداند:**  
[IReflection](../../com.aspose.slides/ireflection) - افکت Reflection.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```


یک افکت Soft Edge ایجاد می‌کند.

**باز می‌گرداند:**  
[ISoftEdge](../../com.aspose.slides/isoftedge) - افکت Soft Edge.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```


یک ImageTransformOperationFactory برمی‌گرداند. فقط-خواندنی [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory).

**باز می‌گرداند:**  
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)