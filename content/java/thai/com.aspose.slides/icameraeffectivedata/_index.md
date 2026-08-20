---
title: ICameraEffectiveData
second_title: Aspose.Slides for Java API Reference
description: อ็อบเจ็กต์ที่ไม่สามารถแก้ไขได้ซึ่งประกอบด้วยคุณสมบัติกล้องที่มีผล
type: docs
url: /th/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

อ็อบเจ็กต์ที่ไม่สามารถแก้ไขได้ซึ่งประกอบด้วยคุณสมบัติกล้องที่มีผล

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## เมธอด

| Method | Description |
| --- | --- |
| [getCameraType()](#getCameraType--) | ประเภทกล้อง. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | มุมมองของกล้อง (0-180 deg, field of View). |
| [getZoom()](#getZoom--) | การซูมของกล้อง (ค่าเป็นเปอร์เซ็นต์บวก). |
| [getRotation()](#getRotation--) | การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |

### getCameraType() {#getCameraType--}
```
public abstract int getCameraType()
```

ประเภทกล้อง. อ่านอย่างเดียว [CameraPresetType](../../com.aspose.slides/camerapresettype).

**คืนค่า:**
int

### getFieldOfViewAngle() {#getFieldOfViewAngle--}
```
public abstract float getFieldOfViewAngle()
```

มุมมองของกล้อง (0-180 deg, field of View). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

การซูมของกล้อง (ค่าเป็นเปอร์เซ็นต์บวก). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. องค์ประกอบแรกในอาร์เรย์ผลลัพธ์ - ละติจูด, องค์ประกอบที่สอง - ลองจิจูด, องค์ประกอบที่สาม - การหมุน. คืนค่า null หากไม่มีการกำหนดการหมุน.

**คืนค่า:**
float[] - Array of rotation values as float[].