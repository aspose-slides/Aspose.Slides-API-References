---
title: Camera
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents Camera.
type: docs
weight: 66
url: /java/com.aspose.slides/camera/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public class Camera extends PVIObject implements ICamera
```

Represents Camera.
## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type. |
| [setCameraType(int value)](#setCameraType-int-) | Camera type. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage). |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```


Camera type. Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```


Camera type. Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View). Read/write float.

**Returns:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, field of View). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public final float getZoom()
```


Camera zoom (positive value in percentage). Read/write float.

**Returns:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```


Camera zoom (positive value in percentage). Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is Float.NaN, all rotation is undefined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined.

**Returns:**
float[]
