---
title: ILightRig
second_title: Aspose.Slides for Android via Java API Reference
description: แสดง LightRig.
type: docs
url: /th/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

แสดง LightRig.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDirection()](#getDirection--) | ทิศทางแสง. |
| [setDirection(int value)](#setDirection-int-) | ทิศทางแสง. |
| [getLightType()](#getLightType--) | แสดง light right ที่ตั้งไว้ล่วงหน้า ซึ่งสามารถใช้กับรูปร่างได้. |
| [setLightType(int value)](#setLightType-int-) | แสดง light right ที่ตั้งไว้ล่วงหน้า ซึ่งสามารถใช้กับรูปร่างได้. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการปฏิวัติเกี่ยวกับแกนเป็นพิกัดละติจูดและลองจิจูด. |
| [getRotation()](#getRotation--) | การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการปฏิวัติเกี่ยวกับแกนเป็นพิกัดละติจูดและลองจิจูด. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

ทิศทางแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**คืนค่า:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

ทิศทางแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

แสดง light right ที่ตั้งไว้ล่วงหน้า ซึ่งสามารถใช้กับรูปร่างได้. Light rig แสดงกลุ่มของแสงที่จัดแนวในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**คืนค่า:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

แสดง light right ที่ตั้งไว้ล่วงหน้า ซึ่งสามารถใช้กับรูปร่างได้. Light rig แสดงกลุ่มของแสงที่จัดแนวในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการปฏิวัติเกี่ยวกับแกนเป็นพิกัดละติจูดและลองจิจูด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| latitude | float | พิกัดละติจูดเป็น float |
| longitude | float | พิกัดลองจิจูดเป็น float |
| revolution | float | พิกัดการปฏิวัติเป็น float |
### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

การหมุนกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการปฏิวัติเกี่ยวกับแกนเป็นพิกัดละติจูดและลองจิจูด. องค์ประกอบแรกในอาร์เรย์ผลลัพธ์ - ละติจูด, องค์ประกอบที่สอง - ลองจิจูด, องค์ประกอบที่สาม - การปฏิวัติ.

**คืนค่า:**
float[] - พิกัดการหมุนเป็น float[]