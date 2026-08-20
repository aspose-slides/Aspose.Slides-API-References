---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: กำหนดระนาบที่เอฟเฟกต์ เช่นแสงเรืองและเงา จะถูกนำไปใช้สัมพันธ์กับรูปทรงที่นำเอฟเฟกต์ไปใช้
type: docs
url: /th/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

กำหนดระนาบที่เอฟเฟกต์ เช่นแสงเรืองและเงา จะถูกนำไปใช้สัมพันธ์กับรูปทรงที่นำเอฟเฟกต์ไปใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | คืนค่า หรือกำหนดเวกเตอร์ปกติ |
| [setNormalVector(float[] value)](#setNormalVector-float---) | คืนค่า หรือกำหนดเวกเตอร์ปกติ |
| [getAnchorPoint()](#getAnchorPoint--) | คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ |
| [getUpVector()](#getUpVector--) | คืนค่า หรือกำหนดเวกเตอร์ที่แสดงทิศขึ้น |
| [setUpVector(float[] value)](#setUpVector-float---) | คืนค่า หรือกำหนดเวกเตอร์ที่แสดงทิศขึ้น |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


**คืนค่า:**
float[]

คืนค่า หรือกำหนดเวกเตอร์ปกติ. เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


คืนค่า หรือกำหนดเวกเตอร์ปกติ. เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากต่อพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


**คืนค่า:**
float[]

คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดในอวกาศที่ทำหน้าที่เป็นจุดยึดของระนาบแบ็คดรอป. จุด 3 มิติแสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


คืนค่า หรือกำหนดจุดในพื้นที่ 3 มิติ จุดนี้เป็นจุดในอวกาศที่ทำหน้าที่เป็นจุดยึดของระนาบแบ็คดรอป. จุด 3 มิติแสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


**คืนค่า:**
float[]

คืนค่า หรือกำหนดเวกเตอร์ที่แสดงทิศขึ้น. เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศขึ้นสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


คืนค่า หรือกำหนดเวกเตอร์ที่แสดงทิศขึ้น. เพื่อให้ชัดเจนยิ่งขึ้น แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงทิศขึ้นสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป. เวกเตอร์แสดงด้วยอาเรย์ของค่า float 3 ตัว ซึ่งกำหนดพิกัด X, Y และ Z. อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |