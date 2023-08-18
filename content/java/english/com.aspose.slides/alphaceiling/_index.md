---
title: AlphaCeiling
second_title: Aspose.Slides for Java API Reference
description: Represents an Alpha Ceiling effect.
type: docs
url: /com.aspose.slides/alphaceiling/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaCeiling](../../com.aspose.slides/ialphaceiling), com.aspose.slides.IVisualEffect
```
public final class AlphaCeiling extends ImageTransformOperation implements IAlphaCeiling, IVisualEffect
```

Represents an Alpha Ceiling effect. Alpha (opacity) values greater than zero are changed to 100%. In other words, anything partially opaque becomes fully opaque.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Ceiling effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaCeiling](../../com.aspose.slides/alphaceiling) is equal to the current [AlphaCeiling](../../com.aspose.slides/alphaceiling). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaCeilingEffectiveData getEffective()
```


Gets effective Alpha Ceiling effect data with the inheritance applied.

**Returns:**
[IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata) - A [IAlphaCeilingEffectiveData](../../com.aspose.slides/ialphaceilingeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaCeiling](../../com.aspose.slides/alphaceiling) is equal to the current [AlphaCeiling](../../com.aspose.slides/alphaceiling).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaCeiling](../../com.aspose.slides/alphaceiling) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
