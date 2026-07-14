---
title: Backdrop3DScene
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: กำหนดระนาบที่เอฟเฟกต์ เช่น แสงเรืองแสงและเงา ถูกนำไปใช้สัมพันธ์กับรูปร่างที่นำเอฟเฟกต์ไปใช้
type: docs
url: /th/com.aspose.slides/backdrop3dscene/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

กำหนดระนาบที่เอฟเฟกต์ เช่น แสงเรืองแสงและเงา ถูกนำไปใช้สัมพันธ์กับรูปร่างที่นำเอฟเฟกต์ไปใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | คืนค่า หรือ กำหนดเวกเตอร์ปกติ |
| [setNormalVector(float[] value)](#setNormalVector-float---) | คืนค่า หรือ กำหนดเวกเตอร์ปกติ |
| [getAnchorPoint()](#getAnchorPoint--) | คืนค่า หรือ กำหนดจุดในอวกาศ 3D |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | คืนค่า หรือ กำหนดจุดในอวกาศ 3D |
| [getUpVector()](#getUpVector--) | คืนค่า หรือ กำหนดเวกเตอร์ที่แสดงด้านบน |
| [setUpVector(float[] value)](#setUpVector-float---) | คืนค่า หรือ กำหนดเวกเตอร์ที่แสดงด้านบน |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน อ่านอย่างเดียว long.

**คืนค่า:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

คืนค่า หรือ กำหนดเวกเตอร์ปกติ เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

คืนค่า หรือ กำหนดเวกเตอร์ปกติ เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่ตั้งฉากกับพื้นผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

คืนค่า หรือ กำหนดจุดในอวกาศ 3D จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอป 3D จุดแสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

คืนค่า หรือ กำหนดจุดในอวกาศ 3D จุดนี้เป็นจุดที่ยึดระนาบแบ็คดรอป 3D จุดแสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

คืนค่า หรือ กำหนดเวกเตอร์ที่แสดงด้านบน เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงด้านบนสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**คืนค่า:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

คืนค่า หรือ กำหนดเวกเตอร์ที่แสดงด้านบน เพื่อความชัดเจน แอตทริบิวต์นี้กำหนดเวกเตอร์ที่แสดงด้านบนสัมพันธ์กับพื้นผิวของระนาบแบ็คดรอป เวกเตอร์แสดงด้วยอาเรย์ของค่าจุดทศนิยม 3 ตัวที่กำหนดพิกัด X, Y และ Z อ่าน/เขียน float[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float[] |  |