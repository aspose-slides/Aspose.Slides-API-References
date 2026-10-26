---
title: Camera
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงกล้อง.
type: docs
url: /th/com.aspose.slides/camera/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทุก Interface ที่ Implemented:**
[com.aspose.slides.ICamera](../../com.aspose.slides/icamera)
```
public final class Camera extends PVIObject implements ICamera
```

แสดงถึงกล้อง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getCameraType()](#getCameraType--) | ประเภทกล้อง. |
| [setCameraType(int value)](#setCameraType-int-) | ประเภทกล้อง. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | มุมมองของกล้อง (0-180 องศา, field of View). |
| [setFieldOfViewAngle(float value)](#setFieldOfViewAngle-float-) | มุมมองของกล้อง (0-180 องศา, field of View). |
| [getZoom()](#getZoom--) | การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). |
| [setZoom(float value)](#setZoom-float-) | การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนตามพิกัด latitude และ longitude. |
| [getRotation()](#getRotation--) | การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนตามพิกัด latitude และ longitude. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getCameraType() {#getCameraType--}
```
public final int getCameraType()
```

ประเภทกล้อง. อ่าน/เขียน [CameraPresetType](../../com.aspose.slides/camerapresettype).

**คืนค่า:**
int
### setCameraType(int value) {#setCameraType-int-}
```
public final void setCameraType(int value)
```

ประเภทกล้อง. อ่าน/เขียน [CameraPresetType](../../com.aspose.slides/camerapresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public final float getFieldOfViewAngle()
```

มุมมองของกล้อง (0-180 องศา, field of View). อ่าน/เขียน float.

**คืนค่า:**
float
### setFieldOfViewAngle(float value) {#setFieldOfViewAngle-float-}
```
public final void setFieldOfViewAngle(float value)
```

มุมมองของกล้อง (0-180 องศา, field of View). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getZoom() {#getZoom--}
```
public final float getZoom()
```

การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). อ่าน/เขียน float.

**คืนค่า:**
float
### setZoom(float value) {#setZoom-float-}
```
public final void setZoom(float value)
```

การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนตามพิกัด latitude และ longitude. หากค่าใดเป็น Float.NaN, การหมุนทั้งหมดจะไม่มีการกำหนดค่า.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

การหมุนถูกกำหนดโดยการใช้พิกัด latitude, พิกัด longitude, และการหมุนรอบแกนตามพิกัด latitude และ longitude. องค์ประกอบแรกในอาร์เรย์ที่คืนค่า - latitude, ตัวที่สอง - longitude, ตัวที่สาม - revolution. คืนค่า null หากไม่มีการกำหนดการหมุน.

**คืนค่า:**
float[]