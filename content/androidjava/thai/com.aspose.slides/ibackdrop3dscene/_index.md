---
title: IBackdrop3DScene
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: กำหนดระนาบที่เอฟเฟกต์เช่นแสงเรืองแสงและเงาจะถูกนำไปใช้สัมพันธ์กับรูปร่างที่นำไปใช้
type: docs
url: /th/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

กำหนดระนาบที่เอฟเฟกต์ เช่น แสงเรืองแสงและเงาจะถูกนำไปใช้สัมพันธ์กับรูปร่างที่นำไปใช้
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Returns or sets a normal vector. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Returns or sets a normal vector. |
| [getAnchorPoint()](#getAnchorPoint--) | Returns or sets a point in 3D space. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Returns or sets a point in 3D space. |
| [getUpVector()](#getUpVector--) | Returns or sets a vector representing up. |
| [setUpVector(float[] value)](#setUpVector-float---) | Returns or sets a vector representing up. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


คืนค่า หรือกำหนดเวกเตอร์ปกติ เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อหน้าผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


คืนค่า หรือกำหนดเวกเตอร์ปกติ เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อหน้าผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอป จุด 3 มิติแสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอป จุด 3 มิติแสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


คืนค่า หรือกำหนดเวกเตอร์ที่แสดงว่าขึ้น เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงว่าขึ้นสัมพันธ์กับหน้าผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


คืนค่า หรือกำหนดเวกเตอร์ที่แสดงว่าขึ้น เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงว่าขึ้นสัมพันธ์กับหน้าผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาร์เรย์ของค่า float 3 ตัวซึ่งกำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |