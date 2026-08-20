---
title: LightRig
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดง LightRig.
type: docs
url: /th/com.aspose.slides/lightrig/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

แสดง LightRig.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | ทิศทางแสง. |
| [setDirection(int value)](#setDirection-int-) | ทิศทางแสง. |
| [getLightType()](#getLightType--) | แสดง preset light right ที่สามารถใช้กับรูปทรงได้. |
| [setLightType(int value)](#setLightType-int-) | แสดง preset light right ที่สามารถใช้กับรูปทรงได้. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |
| [getRotation()](#getRotation--) | การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**Returns:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

ทิศทางแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**Returns:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```

ทิศทางแสง. อ่าน/เขียน [LightingDirection](../../com.aspose.slides/lightingdirection).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```

แสดง preset light right ที่สามารถใช้กับรูปทรงได้. Light rig แสดงกลุ่มแสงที่จัดเรียงในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Returns:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

แสดง preset light right ที่สามารถใช้กับรูปทรงได้. Light rig แสดงกลุ่มแสงที่จัดเรียงในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน/เขียน [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. หากค่าใดค่าหนึ่งเป็น Float.NaN การหมุนทั้งหมดจะไม่มีการกำหนด.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```

การหมุนกำหนดโดยใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนตามพิกัดละติจูดและลองจิจูด. องค์ประกอบแรกในอาเรย์ผลลัพธ์ - latitude, ที่สอง - longitude, ที่สาม - revolution. คืนค่า null หากไม่มีการกำหนดการหมุน.

**Returns:**
float[]