---
title: AlphaFloor
second_title: Aspose.Slides for Java API Reference
description: Represents an Alpha Floor effect.
type: docs
weight: 14
url: /com.aspose.slides/alphafloor/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Represents an Alpha Floor effect. Alpha (opacity) values less than 100% are changed to zero. In other words, anything partially transparent becomes fully transparent.
## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Gets effective Alpha Floor effect data with the inheritance applied.

**Returns:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaFloor](../../com.aspose.slides/alphafloor) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
