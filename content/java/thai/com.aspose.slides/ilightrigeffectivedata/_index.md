---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Java API Reference
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติเครื่องกำเนิดแสงที่มีผล.
type: docs
url: /th/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งบรรจุคุณสมบัติเครื่องกำเนิดแสงที่มีผล.

--------------------

อินเทอร์เฟซนี้ใช้เป็นส่วนหนึ่งของ [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางของแสง. |
| [getLightType()](#getLightType--) | แสดงถึงแสงตั้งต้นที่สามารถนำไปใช้กับรูปทรงได้. |
| [getRotation()](#getRotation--) | การหมุนจะถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```


ทิศทางของแสง. อ่านอย่างเดียว [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```


แสดงถึงแสงตั้งต้นที่สามารถนำไปใช้กับรูปทรงได้. โครงสร้างแสงแสดงถึงกลุ่มของแสงที่จัดทิศทางในลักษณะเฉพาะสัมพันธ์กับฉาก 3 มิติ. อ่านอย่างเดียว [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```


การหมุนจะถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. สมาชิกตัวแรกในอาเรย์ที่ส่งคืนคือละติจูด, ตัวที่สองคือลองจิจูด, ตัวที่สามคือการหมุน.

**Returns:**
float[] - พิกัดการหมุนเป็น float[]