---
title: AlphaModulateFixed
second_title: Aspose.Slides for Java API Reference
description: Represents an Alpha Modulate Fixed effect.
type: docs
url: /com.aspose.slides/alphamodulatefixed/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed), com.aspose.slides.IVisualEffect
```
public final class AlphaModulateFixed extends ImageTransformOperation implements IAlphaModulateFixed, IVisualEffect
```

Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage.
## Methods

| Method | Description |
| --- | --- |
| [getAmount()](#getAmount--) | Returns an amount of effect in percents. |
| [setAmount(float value)](#setAmount-float-) | Returns an amount of effect in percents. |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate Fixed effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) is equal to the current [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getAmount() {#getAmount--}
```
public final float getAmount()
```


Returns an amount of effect in percents. Read/write float.

**Returns:**
float
### setAmount(float value) {#setAmount-float-}
```
public final void setAmount(float value)
```


Returns an amount of effect in percents. Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaModulateFixedEffectiveData getEffective()
```


Gets effective Alpha Modulate Fixed effect data with the inheritance applied.

**Returns:**
[IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata) - A [IAlphaModulateFixedEffectiveData](../../com.aspose.slides/ialphamodulatefixedeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) is equal to the current [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [AlphaModulateFixed](../../com.aspose.slides/alphamodulatefixed) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
