---
title: Backdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
url: /com.aspose.slides/backdrop3dscene/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Defines a plane in which effects, such as glow and shadow, are applied in relation to the shape they are being applied to.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Read-only long.

**Returns:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```


Returns or sets a normal vector. To be more precise, this attribute defines a vector normal to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```


Returns or sets a normal vector. To be more precise, this attribute defines a vector normal to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```


Returns or sets a point in 3D space. This point is the point in space that anchors the backdrop plane. 3D point represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```


Returns or sets a point in 3D space. This point is the point in space that anchors the backdrop plane. 3D point represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```


Returns or sets a vector representing up. To be more precise, this attribute defines a vector representing up in relation to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```


Returns or sets a vector representing up. To be more precise, this attribute defines a vector representing up in relation to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

