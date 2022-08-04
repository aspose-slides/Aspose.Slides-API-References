---
title: AlphaInverse
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an Alpha Inverse effect.
type: docs
weight: 15
url: /java/com.aspose.slides/alphainverse/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

Represents an Alpha Inverse effect. Alpha (opacity) values are inverted by subtracting from 100%.
## Constructors

| Constructor | Description |
| --- | --- |
| [AlphaInverse(IDOMObject parentImmediate)](#AlphaInverse-com.aspose.slides.IDOMObject-) | Alpha Inverse effect constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Inverse effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaInverse](../../com.aspose.slides/alphainverse) is equal to the current [AlphaInverse](../../com.aspose.slides/alphainverse). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### AlphaInverse(IDOMObject parentImmediate) {#AlphaInverse-com.aspose.slides.IDOMObject-}
```
 AlphaInverse(IDOMObject parentImmediate)
```


Alpha Inverse effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


Gets effective Alpha Inverse effect data with the inheritance applied.

**Returns:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - A [IAlphaInverseEffectiveData](../com.aspose.slides/ialphainverseeffectivedata).
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


Determines whether the specified [AlphaInverse](../../com.aspose.slides/alphainverse) is equal to the current [AlphaInverse](../../com.aspose.slides/alphainverse).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaInverse](../com.aspose.slides/alphainverse) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
