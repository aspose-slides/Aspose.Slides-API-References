---
title: ColorReplace
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Color Replacement effect.
type: docs
weight: 113
url: /com.aspose.slides/colorreplace/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Represents a Color Replacement effect. All effect colors are changed to a fixed color. Alpha values are unaffected.
## Methods

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Returns color format which will replace color of every pixel. |
| [getEffective()](#getEffective--) | Gets effective Color Replacement effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [ColorReplace](../../com.aspose.slides/colorreplace) is equal to the current [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returns color format which will replace color of every pixel. Read-only [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Gets effective Color Replacement effect data with the inheritance applied.

**Returns:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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


Determines whether the specified [ColorReplace](../../com.aspose.slides/colorreplace) is equal to the current [ColorReplace](../../com.aspose.slides/colorreplace).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [ColorReplace](../../com.aspose.slides/colorreplace) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
