---
title: Luminance
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents a Luminance effect.
type: docs
weight: 291
url: /java/com.aspose.slides/luminance/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Represents a Luminance effect. Brightness linearly shifts all colors closer to white or black. Contrast scales all colors to be either closer or further apart.
## Constructors

| Constructor | Description |
| --- | --- |
| [Luminance(float brightness, float contrast, IDOMObject parentImmediate)](#Luminance-float-float-com.aspose.slides.IDOMObject-) | Luminance effect constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Luminance effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Luminance](../../com.aspose.slides/luminance) is equal to the current [Luminance](../../com.aspose.slides/luminance). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### Luminance(float brightness, float contrast, IDOMObject parentImmediate) {#Luminance-float-float-com.aspose.slides.IDOMObject-}
```
 Luminance(float brightness, float contrast, IDOMObject parentImmediate)
```


Luminance effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| brightness | float | The percent to change the brightness. |
| contrast | float | The percent to change the contrast. |
| parentImmediate | com.aspose.slides.IDOMObject | The parent collection for Luminance. |

### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


Gets effective Luminance effect data with the inheritance applied.

**Returns:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - A [ILuminanceEffectiveData](../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [Luminance](../../com.aspose.slides/luminance) is equal to the current [Luminance](../../com.aspose.slides/luminance).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [Luminance](../com.aspose.slides/luminance) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
