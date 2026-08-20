---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
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
| [getDirection()](#getDirection--) | ทิศทางของแสง. |
| [setDirection(int value)](#setDirection-int-) | ทิศทางของแสง. |
| [getLightType()](#getLightType--) | แสดงไฟตั้งล่วงหน้าที่สามารถนำไปใช้กับรูปทรง. |
| [setLightType(int value)](#setLightType-int-) | แสดงไฟตั้งล่วงหน้าที่สามารถนำไปใช้กับรูปทรง. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูดและการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |
| [getRotation()](#getRotation--) | การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูดและการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

ทิศทางของแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**คืนค่า:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

ทิศทางของแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

แสดงไฟตั้งล่วงหน้าที่สามารถนำไปใช้กับรูปทรง. Light rig แสดงกลุ่มไฟที่จัดวางในลักษณะเฉพาะสัมพันธ์กับฉาก 3 มิติ. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**คืนค่า:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

แสดงไฟตั้งล่วงหน้าที่สามารถนำไปใช้กับรูปทรง. Light rig แสดงกลุ่มไฟที่จัดวางในลักษณะเฉพาะสัมพันธ์กับฉาก 3 มิติ. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูดและการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| latitude | float | พิกัดละติจูดเป็น float |
| longitude | float | พิกัดลองจิจูดเป็น float |
| revolution | float | พิกัดการหมุนเป็น float |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูดและการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. องค์ประกอบแรกในอาเรย์ที่คืนค่า - ละติจูด, สอง - ลองจิจูด, สาม - การหมุน.

**คืนค่า:**
float[] - พิกัดการหมุนเป็น float[]