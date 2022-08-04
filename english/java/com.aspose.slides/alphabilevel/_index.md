---
title: AlphaBiLevel
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an Alpha Bi-Level effect.
type: docs
weight: 12
url: /java/com.aspose.slides/alphabilevel/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Represents an Alpha Bi-Level effect. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque).
## Constructors

| Constructor | Description |
| --- | --- |
| [AlphaBiLevel(float threshold, IDOMObject parentImmediate)](#AlphaBiLevel-float-com.aspose.slides.IDOMObject-) | Alpha Bi-Level effect constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
| [setThreshold(float value)](#setThreshold-float-) | Returns effect threshold. |
| [getEffective()](#getEffective--) | Gets effective Alpha Bi-Level effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaBiLevel](../../com.aspose.slides/alphabilevel) is equal to the current [AlphaBiLevel](../../com.aspose.slides/alphabilevel). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### AlphaBiLevel(float threshold, IDOMObject parentImmediate) {#AlphaBiLevel-float-com.aspose.slides.IDOMObject-}
```
 AlphaBiLevel(float threshold, IDOMObject parentImmediate)
```


Alpha Bi-Level effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| threshold | float | The threshold value for the alpha bi-level effect. |
| parentImmediate | com.aspose.slides.IDOMObject | The parent of Alpha Bi-Level. |

### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


Returns effect threshold. Read/write float.

**Returns:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


Returns effect threshold. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


Gets effective Alpha Bi-Level effect data with the inheritance applied.

**Returns:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaBiLevel](../../com.aspose.slides/alphabilevel) is equal to the current [AlphaBiLevel](../../com.aspose.slides/alphabilevel).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaBiLevel](../com.aspose.slides/alphabilevel) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
