---
title: ICamera
second_title: Aspose.Slides for Android via Java API Reference
description: Represents Camera.
type: docs
weight: 677
url: /androidjava/com.aspose.slides/icamera/
---```
public interface ICamera
```

Represents Camera.
## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (positive value in percentage) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


Camera type Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View) Read/write float.

**Returns:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, field of View) Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (positive value in percentage) Read/write float.

**Returns:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camera zoom (positive value in percentage) Read/write float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is Float.NaN, all rotation is undefined.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float | Latitude value float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined.

**Returns:**
float[] - Array of rotation values as float[].
