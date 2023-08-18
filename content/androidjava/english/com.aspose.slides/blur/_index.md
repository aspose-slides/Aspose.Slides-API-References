---
title: Blur
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Blur effect that is applied to the entire shape including its fill.
type: docs
weight: 58
url: /com.aspose.slides/blur/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Represents a Blur effect that is applied to the entire shape, including its fill. All color channels, including alpha, are affected.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Returns or sets blur radius. |
| [setRadius(double value)](#setRadius-double-) | Returns or sets blur radius. |
| [getGrow()](#getGrow--) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determines whether the bounds of the object should be grown as a result of the blurring. |
| [getEffective()](#getEffective--) | Gets effective Blur effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Blur](../../com.aspose.slides/blur) is equal to the current [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Returns or sets blur radius. Read/write double.

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Returns or sets blur radius. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. Read/write boolean.

**Returns:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Determines whether the bounds of the object should be grown as a result of the blurring. True indicates the bounds are grown while false indicates that they are not. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Gets effective Blur effect data with the inheritance applied.

**Returns:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [Blur](../../com.aspose.slides/blur) is equal to the current [Blur](../../com.aspose.slides/blur).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [Blur](../../com.aspose.slides/blur) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
