---
title: HSL
second_title: Aspose.Slides for Java API Reference
description:  Represents a Hue/Saturation/Luminance effect.
type: docs
weight: 235
url: /java/com.aspose.slides/hsl/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Represents a Hue/Saturation/Luminance effect. The hue, saturation, and luminance may each be adjusted relative to its current value.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Hue/Saturation/Luminance effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [HSL](../../com.aspose.slides/hsl) is equal to the current [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```


Gets effective Hue/Saturation/Luminance effect data with the inheritance applied.

**Returns:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - A [IHSLEffectiveData](../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [HSL](../../com.aspose.slides/hsl) is equal to the current [HSL](../../com.aspose.slides/hsl).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [HSL](../com.aspose.slides/hsl) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
