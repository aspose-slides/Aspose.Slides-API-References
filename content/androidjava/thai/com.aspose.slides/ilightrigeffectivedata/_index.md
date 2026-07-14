---
title: ILightRigEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งมีคุณสมบัติของ light rig ที่มีผล.
type: docs
url: /th/com.aspose.slides/ilightrigeffectivedata/
---```
public interface ILightRigEffectiveData
```

อ็อบเจ็กต์ที่ไม่สามารถเปลี่ยนแปลงได้ซึ่งมีคุณสมบัติของ light rig ที่มีผล.

--------------------

ส่วนต่อประสานนี้ใช้เป็นส่วนหนึ่งของ [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางของแสง. |
| [getLightType()](#getLightType--) | แสดงถึง preset light right ที่สามารถนำไปใช้กับรูปทรงได้. |
| [getRotation()](#getRotation--) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |

### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

ทิศทางของแสง. อ่านอย่างเดียว [LightingDirection](../../com.aspose.slides/lightingdirection).

**คืนค่า:**
int

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

แสดงถึง preset light right ที่สามารถนำไปใช้กับรูปทรงได้. light rig แสดงถึงกลุ่มแสงที่จัดวางในรูปแบบเฉพาะสัมพันธ์กับฉาก 3D. อ่านอย่างเดียว [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**คืนค่า:**
int

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. องค์ประกอบแรกในอาร์เรย์ผลลัพธ์ - ละติจูด, องค์ประกอบที่สอง - ลองจิจูด, องค์ประกอบที่สาม - การหมุน.

**คืนค่า:**
float[] - พิกัดการหมุนในรูปแบบ float[]