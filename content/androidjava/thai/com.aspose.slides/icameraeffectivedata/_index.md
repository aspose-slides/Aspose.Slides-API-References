---
title: ICameraEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติกล้องที่มีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/icameraeffectivedata/
---```
public interface ICameraEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติกล้องที่มีประสิทธิภาพ.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCameraType()](#getCameraType--) | ประเภทกล้อง. |
| [getFieldOfViewAngle()](#getFieldOfViewAngle--) | มุมมองกล้อง (FOV) (0-180 องศา, มุมมองของสนามมองเห็น). |
| [getZoom()](#getZoom--) | การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). |
| [getRotation()](#getRotation--) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |

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

มุมมองกล้อง (FOV) (0-180 องศา, มุมมองของสนามมองเห็น). อ่านอย่างเดียว float.

**คืนค่า:**
float
### getZoom() {#getZoom--}
```
public abstract float getZoom()
```

การซูมของกล้อง (ค่าบวกเป็นเปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. ตัวแรกในอาร์เรย์ผลลัพธ์คือ ละติจูด, ตัวที่สองคือ ลองจิจูด, ตัวที่สามคือ การหมุน. คืนค่า null หากไม่มีการกำหนดการหมุน.

**คืนค่า:**
float[] - อาร์เรย์ของค่าการหมุนในรูปแบบ float[] .