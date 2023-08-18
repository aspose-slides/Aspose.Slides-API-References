---
title: GrayScale
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Gray Scale effect.
type: docs
weight: 234
url: /com.aspose.slides/grayscale/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Represents a Gray Scale effect. Converts all effect color values to a shade of gray, corresponding to their luminance. Effect alpha (opacity) values are unaffected.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Gray Scale effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [GrayScale](../../com.aspose.slides/grayscale) is equal to the current [GrayScale](../../com.aspose.slides/grayscale). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```


Gets effective Gray Scale effect data with the inheritance applied.

**Returns:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [GrayScale](../../com.aspose.slides/grayscale) is equal to the current [GrayScale](../../com.aspose.slides/grayscale).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [GrayScale](../../com.aspose.slides/grayscale) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
