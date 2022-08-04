---
title: IBackdrop3DScene
second_title: Aspose.Sildes for Java API Reference
description: p
 Defines a plane in which effects such as glow and shadow are applied in relation to the shape they are being applied to.
type: docs
weight: 647
url: /java/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Defines a plane in which effects, such as glow and shadow, are applied in relation to the shape they are being applied to.
## Methods

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Returns or sets a normal vector. To be more precise, this attribute defines a vector normal to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Returns or sets a normal vector. To be more precise, this attribute defines a vector normal to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Returns or sets a point in 3D space. This point is the point in space that anchors the backdrop plane. 3D point represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Returns or sets a point in 3D space. This point is the point in space that anchors the backdrop plane. 3D point represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Returns or sets a vector representing up. To be more precise, this attribute defines a vector representing up in relation to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Returns:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Returns or sets a vector representing up. To be more precise, this attribute defines a vector representing up in relation to the face of the backdrop plane. Vector represented by array of 3 float values which define X, Y and Z coordinates. Read/write float[].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

