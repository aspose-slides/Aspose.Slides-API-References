---
title: Backdrop3DScene
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: กำหนดระนาบที่เอฟเฟกต์เช่นแสงสว่างและเงาถูกนำไปใช้สัมพันธ์กับรูปร่างที่เอฟเฟกต์นั้นถูกนำไปใช้
type: docs
url: /th/com.aspose.slides/backdrop3dscene/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

กำหนดระนาบที่เอฟเฟกต์เช่นแสงสว่างและเงาถูกนำไปใช้สัมพันธ์กับรูปร่างที่เอฟเฟกต์นั้นถูกนำไปใช้

## เมธอด

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | ส่งคืนหรือกำหนดเวกเตอร์ปกติ. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | ส่งคืนหรือกำหนดเวกเตอร์ปกติ. |
| [getAnchorPoint()](#getAnchorPoint--) | ส่งคืนหรือกำหนดจุดในพื้นที่ 3 มิติ. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | ส่งคืนหรือกำหนดจุดในพื้นที่ 3 มิติ. |
| [getUpVector()](#getUpVector--) | ส่งคืนหรือกำหนดเวกเตอร์ที่แสดงทิศทางขึ้น. |
| [setUpVector(float[] value)](#setUpVector-float---) | ส่งคืนหรือกำหนดเวกเตอร์ที่แสดงทิศทางขึ้น. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**ส่งคืน:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

ส่งคืนหรือกำหนดเวกเตอร์ปกติ. เพื่อความชัดเจนยิ่งขึ้น, แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบพื้นหลัง. เวกเตอร์แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**ส่งคืน:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

ส่งคืนหรือกำหนดเวกเตอร์ปกติ. เพื่อความชัดเจนยิ่งขึ้น, แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบพื้นหลัง. เวกเตอร์แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

ส่งคืนหรือกำหนดจุดในพื้นที่ 3 มิติ. จุดนี้คือจุดในอวกาศที่ทำหน้าที่เป็นจุดยึดของระนาบพื้นหลัง. 3D point แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**ส่งคืน:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

ส่งคืนหรือกำหนดจุดในพื้นที่ 3 มิติ. จุดนี้คือจุดในอวกาศที่ทำหน้าที่เป็นจุดยึดของระนาบพื้นหลัง. 3D point แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

ส่งคืนหรือกำหนดเวกเตอร์ที่แสดงทิศทางขึ้น. เพื่อความชัดเจนยิ่งขึ้น, แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศทางขึ้นสัมพันธ์กับพื้นผิวของระนาบพื้นหลัง. เวกเตอร์แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**ส่งคืน:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

ส่งคืนหรือกำหนดเวกเตอร์ที่แสดงทิศทางขึ้น. เพื่อความชัดเจนยิ่งขึ้น, แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศทางขึ้นสัมพันธ์กับพื้นผิวของระนาบพื้นหลัง. เวกเตอร์แสดงโดยอาร์เรย์ของค่า float 3 ตัวที่กำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |