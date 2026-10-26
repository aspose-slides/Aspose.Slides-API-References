---
title: ICamera
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทน Camera.
type: docs
url: /th/com.aspose.slides/icamera/
---```
public interface ICamera
```

แทน Camera.
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getCameraType()](#getCameraType--) | ประเภทของ Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [setCameraType(int value)](#setCameraType-int-) | ประเภทของ Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype). |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | Camera FOV (0-180 deg, field of View) Read/write float. |
| [getZoom()](#getZoom--) | Camera zoom (ค่าบวกเป็นเปอร์เซ็นต์) Read/write float. |
| [setZoom(float value)](#setZoom-float-) | Camera zoom (ค่าบวกเป็นเปอร์เซ็นต์) Read/write float. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนเป็นพิกัด latitude และ longitude. |
| [getRotation()](#getRotation--) | การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนเป็นพิกัด latitude และ longitude. |
### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```


ประเภทของ Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**คืนค่า:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public abstract void setCameraType(int value)
```


ประเภทของ Camera Read/write [CameraPresetType](../../com.aspose.slides/camerapresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```


Camera FOV (0-180 deg, field of View) Read/write float.

**คืนค่า:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public abstract void setFieldOfViewAngle(float value)
```


Camera FOV (0-180 deg, field of View) Read/write float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```


Camera zoom (ค่าบวกเป็นเปอร์เซ็นต์) Read/write float.

**คืนค่า:**
float
### setZoom(float value) {#setZoom-float-}
```
public abstract void setZoom(float value)
```


Camera zoom (ค่าบวกเป็นเปอร์เซ็นต์) Read/write float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```


การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนเป็นพิกัด latitude และ longitude. หากค่าพิกัดใดเป็น Float.NaN จะทำให้การหมุนทั้งหมดไม่มีการกำหนดค่า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| latitude | float | ค่า latitude float |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนเป็นพิกัด latitude และ longitude. สมาชิกแรกในอาร์เรย์ที่ส่งคืน - latitude, สอง - longitude, สาม - revolution. คืนค่า null หากไม่มีการกำหนดการหมุน.

**คืนค่า:**
float[] - อาร์เรย์ของค่าการหมุนเป็น float[].