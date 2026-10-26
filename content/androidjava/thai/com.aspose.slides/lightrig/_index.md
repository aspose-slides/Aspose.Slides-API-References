---
title: LightRig
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดง LightRig.
type: docs
url: /th/com.aspose.slides/lightrig/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

Represents LightRig.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | ทิศทางของแสง. |
| [setDirection(int value)](#setDirection-int-) | ทิศทางของแสง. |
| [getLightType()](#getLightType--) | แสดงไฟตั้งต้นด้านขวาที่สามารถใช้กับรูปทรงได้. |
| [setLightType(int value)](#setLightType-int-) | แสดงไฟตั้งต้นด้านขวาที่สามารถใช้กับรูปทรงได้. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. |
| [getRotation()](#getRotation--) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

ทิศทางของแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**คืนค่า:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

ทิศทางของแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getLightType() {#getLightType--}
```
public final int getLightType()
```

แสดงไฟตั้งต้นด้านขวาที่สามารถใช้กับรูปทรงได้. Light rig แสดงกลุ่มไฟที่จัดวางในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**คืนค่า:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

แสดงไฟตั้งต้นด้านขวาที่สามารถใช้กับรูปทรงได้. Light rig แสดงกลุ่มไฟที่จัดวางในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. หากค่าพิกัดใดเป็น Float.NaN, การหมุนทั้งหมดจะไม่ได้กำหนด.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |
### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. สมาชิกแรกในอาเรย์ผลลัพธ์ - ละติจูด, สมาชิกที่สอง - ลองจิจูด, สมาชิกที่สาม - การหมุน. คืนค่า null หากไม่มีการกำหนดการหมุน.

**คืนค่า:**
float[]