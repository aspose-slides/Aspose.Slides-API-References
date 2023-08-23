---
title: SoftEdge
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a soft edge effect.
type: docs
url: /com.aspose.slides/softedge/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Represents a soft edge effect. The edges of the shape are blurred, while the fill is not affected.
## Methods

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Specifies the radius of blur to apply to the edges. |
| [setRadius(double value)](#setRadius-double-) | Specifies the radius of blur to apply to the edges. |
| [getEffective()](#getEffective--) | Gets effective Soft Edge effect data with the inheritance applied. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [SoftEdge](../../com.aspose.slides/softedge) is equal to the current [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Specifies the radius of blur to apply to the edges. Read/write double.

**Returns:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Specifies the radius of blur to apply to the edges. Read/write double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Gets effective Soft Edge effect data with the inheritance applied.

**Returns:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Returns parent IPresentationComponent. Read-only [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified [SoftEdge](../../com.aspose.slides/softedge) is equal to the current [SoftEdge](../../com.aspose.slides/softedge).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [SoftEdge](../../com.aspose.slides/softedge) to compare. |

**Returns:**
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a particular type.

**Returns:**
int - A hash code for the current object.
