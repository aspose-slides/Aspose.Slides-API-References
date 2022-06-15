---
title: Camera
type: docs
weight: 0
url: /php-java/camera/
---

# Camera class

 Represents Camera.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCameraType](/slides/php-java/camera/getcameratype/)() | int | Camera type. Read/write CameraPresetType. |
| [getFieldOfViewAngle](/slides/php-java/camera/getfieldofviewangle/)() | float | Camera FOV (0-180 deg, field of View). Read/write float. |
| [getRotation](/slides/php-java/camera/getrotation/)() | float | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. first element in return array - latitude, second - longitude, third - revolution. Returns null if no rotation defined. |
| [getZoom](/slides/php-java/camera/getzoom/)() | float | Camera zoom (positive value in percentage). Read/write float. |
| [setCameraType](/slides/php-java/camera/setcameratype/)(int) | void | Camera type. Read/write CameraPresetType. |
| [setFieldOfViewAngle](/slides/php-java/camera/setfieldofviewangle/)(float) | void | Camera FOV (0-180 deg, field of View). Read/write float. |
| [setRotation](/slides/php-java/camera/setrotation/)(float, float, float) | void | A rotation is defined through the use of a latitude coordinate, a longitude coordinate, and a revolution about the axis as the latitude and longitude coordinates. If any of coordinate value is Float.NaN, all rotation is undefined. |
| [setZoom](/slides/php-java/camera/setzoom/)(float) | void | Camera zoom (positive value in percentage). Read/write float. |
