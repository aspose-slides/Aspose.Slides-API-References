---
title: BiLevel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a Bi-Level black/white effect.
type: docs
weight: 56
url: /androidjava/com.aspose.slides/bilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Represents a Bi-Level (black/white) effect. Input colors whose luminance is less than the specified threshold value are changed to black. Input colors whose luminance are greater than or equal the specified value are set to white. The alpha effect values are unaffected by this effect.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Gets effective Bi-Level effect data with the inheritance applied.

**Returns:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [BiLevel](../../com.aspose.slides/bilevel) is equal to the current [BiLevel](../../com.aspose.slides/bilevel).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [BiLevel](../../com.aspose.slides/bilevel) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
