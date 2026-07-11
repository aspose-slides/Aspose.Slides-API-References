---
title: IEffectFactory
second_title: Aspose.Slides για Android μέσω Java API
description: Επιτρέπει τη δημιουργία αντιγράφων εφέ
type: docs
url: /el/com.aspose.slides/ieffectfactory/
---```
public interface IEffectFactory
```

Επιτρέπει τη δημιουργία αντιγράφων εφέ

--------------------

Για συμβατότητα με COM.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createGlow()](#createGlow--) | Δημιουργεί το εφέ Glow. |
| [createInnerShadow()](#createInnerShadow--) | Δημιουργεί το εφέ Inner shafow. |
| [createOuterShadow()](#createOuterShadow--) | Δημιουργεί το εφέ Outer shadow. |
| [createPresetShadow()](#createPresetShadow--) | Δημιουργεί το εφέ Preset shadow. |
| [createReflection()](#createReflection--) | Δημιουργεί το εφέ Reflection. |
| [createSoftEdge()](#createSoftEdge--) | Δημιουργεί το εφέ Soft Edge. |
| [getImageTransformOperationFactory()](#getImageTransformOperationFactory--) | Επιστρέφει ImageTransformOperationFactory. |
### createGlow() {#createGlow--}
```
public abstract IGlow createGlow()
```


Δημιουργεί το εφέ Glow.

**Returns:**
[IGlow](../../com.aspose.slides/iglow) - Glow effect.
### createInnerShadow() {#createInnerShadow--}
```
public abstract IInnerShadow createInnerShadow()
```


Δημιουργεί το εφέ Inner shafow.

**Returns:**
[IInnerShadow](../../com.aspose.slides/iinnershadow) - Inner shafow effect.
### createOuterShadow() {#createOuterShadow--}
```
public abstract IOuterShadow createOuterShadow()
```


Δημιουργεί το εφέ Outer shadow.

**Returns:**
[IOuterShadow](../../com.aspose.slides/ioutershadow) - Outer shadow effect.
### createPresetShadow() {#createPresetShadow--}
```
public abstract IPresetShadow createPresetShadow()
```


Δημιουργεί το εφέ Preset shadow.

**Returns:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow) - Preset shadow effect.
### createReflection() {#createReflection--}
```
public abstract IReflection createReflection()
```


Δημιουργεί το εφέ Reflection.

**Returns:**
[IReflection](../../com.aspose.slides/ireflection) - Reflection effect.
### createSoftEdge() {#createSoftEdge--}
```
public abstract ISoftEdge createSoftEdge()
```


Δημιουργεί το εφέ Soft Edge.

**Returns:**
[ISoftEdge](../../com.aspose.slides/isoftedge) - Soft Edge effect.
### getImageTransformOperationFactory() {#getImageTransformOperationFactory--}
```
public abstract IImageTransformOperationFactory getImageTransformOperationFactory()
```


Επιστρέφει ImageTransformOperationFactory. Μόνο για ανάγνωση [IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory).

**Returns:**
[IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)