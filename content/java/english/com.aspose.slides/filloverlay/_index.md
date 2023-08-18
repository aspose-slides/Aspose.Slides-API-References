---
title: FillOverlay
second_title: Aspose.Slides for Java API Reference
description: Represents a Fill Overlay effect.
type: docs
weight: 192
url: /com.aspose.slides/filloverlay/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Represents a Fill Overlay effect. A fill overlay may be used to specify an additional fill for an object and blend the two fills together.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Fill format. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Read/write [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Returns:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Read/write [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Gets effective Fill Overlay effect data with the inheritance applied.

**Returns:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
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


Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [FillOverlay](../../com.aspose.slides/filloverlay) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
