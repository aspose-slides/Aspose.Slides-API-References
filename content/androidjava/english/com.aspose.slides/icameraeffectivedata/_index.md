---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective camera properties.
type: docs
url: /com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

Immutable object which contains effective camera properties.

--------------------

This interface is used as a part of [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | Camera type. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | Camera zoom (positive value in percentage). |
| [getRotation()](#getRotation--) | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


Camera type. Read-only [CameraPresetType](../../com.aspose.slides/camerapresettype).

**Returns:**
int
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View). Read-only float.

**Returns:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (positive value in percentage). Read-only float.

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined.

**Returns:**
float[] - Array of rotation values as float[].
