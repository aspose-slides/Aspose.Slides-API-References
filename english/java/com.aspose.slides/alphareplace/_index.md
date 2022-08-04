---
title: AlphaReplace
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents and Alpha Replace effect.
type: docs
weight: 18
url: /java/com.aspose.slides/alphareplace/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect
```
public class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

Represents and Alpha Replace effect. Effect alpha (opacity) values are replaced by a fixed alpha.
## Constructors

| Constructor | Description |
| --- | --- |
| [AlphaReplace(float alpha, IDOMObject parentImmediate)](#AlphaReplace-float-com.aspose.slides.IDOMObject-) | Alpha Replace effect constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Replace effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaReplace](../../com.aspose.slides/alphareplace) is equal to the current [AlphaReplace](../../com.aspose.slides/alphareplace). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### AlphaReplace(float alpha, IDOMObject parentImmediate) {#AlphaReplace-float-com.aspose.slides.IDOMObject-}
```
 AlphaReplace(float alpha, IDOMObject parentImmediate)
```


Alpha Replace effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | float |  |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```


Gets effective Alpha Replace effect data with the inheritance applied.

**Returns:**
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - A [IAlphaReplaceEffectiveData](../com.aspose.slides/ialphareplaceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaReplace](../../com.aspose.slides/alphareplace) is equal to the current [AlphaReplace](../../com.aspose.slides/alphareplace).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaReplace](../com.aspose.slides/alphareplace) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
