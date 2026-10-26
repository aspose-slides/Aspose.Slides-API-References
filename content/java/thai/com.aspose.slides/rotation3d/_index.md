---
title: Rotation3D
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงการหมุน 3 มิติของแผนภูมิ
type: docs
url: /th/com.aspose.slides/rotation3d/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการอิมพลีเมนต์ทั้งหมด:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

แสดงการหมุน 3 มิติของแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRotationX()](#getRotationX--) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน X, คือ |
| [setRotationX(byte value)](#setRotationX-byte-) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน X, คือ |
| [getRotationY()](#getRotationY--) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน Y, คือ |
| [setRotationY(int value)](#setRotationY-int-) | คืนค่า หรือกำหนดองศาการหมุนรอบแกน Y, คือ |
| [getPerspective()](#getPerspective--) | คืนค่า หรือกำหนดค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 240) |
| [setPerspective(byte value)](#setPerspective-byte-) | คืนค่า หรือกำหนดค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 240) |
| [getRightAngleAxes()](#getRightAngleAxes--) | กำหนดว่าแกนของแผนภูมิเป็นมุมฉากหรือไม่, แทนการวาดในมุมมองเชิงลึก |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | กำหนดว่าแกนของแผนภูมิเป็นมุมฉากหรือไม่, แทนการวาดในมุมมองเชิงลึก |
| [getDepthPercents()](#getDepthPercents--) | คืนค่า หรือกำหนดความลึกของแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) |
| [setDepthPercents(int value)](#setDepthPercents-int-) | คืนค่า หรือกำหนดความลึกของแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) |
| [getHeightPercents()](#getHeightPercents--) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) |
| [setHeightPercents(int value)](#setHeightPercents-int-) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

คืนค่า หรือกำหนดองศาการหมุนรอบแกน X, คือในทิศทาง Y สำหรับแผนภูมิ 3 มิติ (ระหว่าง -90 ถึง 90 องศา) คุณสมบัตินี้ตรงกับรายการ 21.2.2.157 rotX (X Rotation) ใน ECMA-376 และกับตัวเลือก "Y Rotation" ใน PowerPoint 2007+ อ่าน/เขียน byte.

**คืนค่า:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

คืนค่า หรือกำหนดองศาการหมุนรอบแกน X, คือในทิศทาง Y สำหรับแผนภูมิ 3 มิติ (ระหว่าง -90 ถึง 90 องศา) คุณสมบัตินี้ตรงกับรายการ 21.2.2.157 rotX (X Rotation) ใน ECMA-376 และกับตัวเลือก "Y Rotation" ใน PowerPoint 2007+ อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

คืนค่า หรือกำหนดองศาการหมุนรอบแกน Y, คือในทิศทาง X สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 360 องศา) คุณสมบัตินี้ตรงกับรายการ 21.2.2.158 rotY (Y Rotation) ใน ECMA-376 และกับตัวเลือก "X Rotation" ใน PowerPoint 2007+ อ่าน/เขียน int.

**คืนค่า:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

คืนค่า หรือกำหนดองศาการหมุนรอบแกน Y, คือในทิศทาง X สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 360 องศา) คุณสมบัตินี้ตรงกับรายการ 21.2.2.158 rotY (Y Rotation) ใน ECMA-376 และกับตัวเลือก "X Rotation" ใน PowerPoint 2007+ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

คืนค่า หรือกำหนดค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 240) จะถูกละเลยหากคุณสมบัติ RightAngleAxes มีค่า true อ่าน/เขียน byte.

**คืนค่า:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

คืนค่า หรือกำหนดค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3 มิติ (ระหว่าง 0 ถึง 240) จะถูกละเลยหากคุณสมบัติ RightAngleAxes มีค่า true อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

กำหนดว่าแกนของแผนภูมิเป็นมุมฉากหรือไม่, แทนการวาดในมุมมองเชิงลึก. อีกนัยหนึ่งมันกำหนดว่ามุมของแกนแผนภูมิมีอิสระจากการหมุนหรือการยกของแผนภูมิหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

กำหนดว่าแกนของแผนภูมิเป็นมุมฉากหรือไม่, แทนการวาดในมุมมองเชิงลึก. อีกนัยหนึ่งมันกำหนดว่ามุมของแกนแผนภูมิมีอิสระจากการหมุนหรือการยกของแผนภูมิหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

คืนค่า หรือกำหนดความลึกของแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน/เขียน int.

**คืนค่า:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

คืนค่า หรือกำหนดความลึกของแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน/เขียน int.

**คืนค่า:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject