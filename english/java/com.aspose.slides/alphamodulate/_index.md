---
title: AlphaModulate
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents an Alpha Modulate effect.
type: docs
weight: 16
url: /java/com.aspose.slides/alphamodulate/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

Represents an Alpha Modulate effect. Effect alpha (opacity) values are multiplied by a fixed percentage. The effect container specifies an effect containing alpha values to modulate.
## Constructors

| Constructor | Description |
| --- | --- |
| [AlphaModulate(IDOMObject parentImmediate)](#AlphaModulate-com.aspose.slides.IDOMObject-) | Alpha Modulate effect constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### AlphaModulate(IDOMObject parentImmediate) {#AlphaModulate-com.aspose.slides.IDOMObject-}
```
 AlphaModulate(IDOMObject parentImmediate)
```


Alpha Modulate effect constructor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```


Gets effective Alpha Modulate effect data with the inheritance applied.

**Returns:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - A [IAlphaModulateEffectiveData](../com.aspose.slides/ialphamodulateeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaModulate](../com.aspose.slides/alphamodulate) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
