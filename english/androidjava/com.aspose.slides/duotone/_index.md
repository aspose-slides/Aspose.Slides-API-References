---
title: Duotone
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Duotone effect.
type: docs
weight: 161
url: /androidjava/com.aspose.slides/duotone/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Represents a Duotone effect. For each pixel, combines Color1 and Color2 through a linear interpolation to determine the new color for that pixel.
## Methods

| Method | Description |
| --- | --- |
| [getColor1()](#getColor1--) | Returns target color format for dark pixels. |
| [getColor2()](#getColor2--) | Returns target color format for light pixels. |
| [getEffective()](#getEffective--) | Gets effective Duotone effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [Duotone](../../com.aspose.slides/duotone) is equal to the current [Duotone](../../com.aspose.slides/duotone). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Returns target color format for dark pixels. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Returns target color format for light pixels. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Gets effective Duotone effect data with the inheritance applied.

**Returns:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [Duotone](../../com.aspose.slides/duotone) is equal to the current [Duotone](../../com.aspose.slides/duotone).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [Duotone](../../com.aspose.slides/duotone) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
