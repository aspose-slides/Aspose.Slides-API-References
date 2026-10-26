---
title: IRotation3D
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนการหมุน 3D ของแผนภูมิ
type: docs
url: /th/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

เป็นตัวแทนการหมุน 3D ของแผนภูมิ
## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [getRotationX()](#getRotationX--) | คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน X, คือ |
| [setRotationX(byte value)](#setRotationX-byte-) | คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน X, คือ |
| [getRotationY()](#getRotationY--) | คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน Y, คือ |
| [setRotationY(int value)](#setRotationY-int-) | คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน Y, คือ |
| [getPerspective()](#getPerspective--) | คืนค่า หรือ ตั้งค่าค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) |
| [setPerspective(byte value)](#setPerspective-byte-) | คืนค่า หรือ ตั้งค่าค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) |
| [getRightAngleAxes()](#getRightAngleAxes--) | กำหนดว่ากราฟิกแกนของแผนภูมิมีมุมฉากหรือไม่, แทนที่การวาดในมุมมอง |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | กำหนดว่ากราฟิกแกนของแผนภูมิมีมุมฉากหรือไม่, แทนที่การวาดในมุมมอง |
| [getDepthPercents()](#getDepthPercents--) | คืนค่า หรือ ตั้งค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) |
| [setDepthPercents(int value)](#setDepthPercents-int-) | คืนค่า หรือ ตั้งค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) |
| [getHeightPercents()](#getHeightPercents--) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) |
| [setHeightPercents(int value)](#setHeightPercents-int-) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) |

### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน X, คือในทิศทาง Y สำหรับแผนภูมิ 3D (ระหว่าง -90 ถึง 90 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotX (X Rotation) ใน ECMA-376 และตัวเลือก "Y Rotation" ใน PowerPoint 2007+ อ่าน/เขียน byte.

**คืนค่า:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน X, คือในทิศทาง Y สำหรับแผนภูมิ 3D (ระหว่าง -90 ถึง 90 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotX (X Rotation) ใน ECMA-376 และตัวเลือก "Y Rotation" ใน PowerPoint 2007+ อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน Y, คือในทิศทาง X สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 360 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotY (Y Rotation) ใน ECMA-376 และตัวเลือก "X Rotation" ใน PowerPoint 2007+ อ่าน/เขียน int.

**คืนค่า:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

คืนค่า หรือ ตั้งค่ามุมการหมุนรอบแกน Y, คือในทิศทาง X สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 360 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotY (Y Rotation) ใน ECMA-376 และตัวเลือก "X Rotation" ใน PowerPoint 2007+ อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

คืนค่า หรือ ตั้งค่าค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) จะถูกละเว้นหากค่า property RightAngleAxes เป็น true อ่าน/เขียน byte.

**คืนค่า:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

คืนค่า หรือ ตั้งค่าค่ามุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) จะถูกละเว้นหากค่า property RightAngleAxes เป็น true อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

กำหนดว่ากราฟิกแกนของแผนภูมิมีมุมฉากหรือไม่, แทนที่การวาดในมุมมอง กล่าวคือกำหนดว่ามุมแกนของแผนภูมิเป็นอิสระจากการหมุนหรือการยกของแผนภูมิ อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

กำหนดว่ากราฟิกแกนของแผนภูมิมีมุมฉากหรือไม่, แทนที่การวาดในมุมมอง กล่าวคือกำหนดว่ามุมแกนของแผนภูมิเป็นอิสระจากการหมุนหรือการยกของแผนภูมิ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

คืนค่า หรือ ตั้งค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน/เขียน int.

**คืนค่า:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

คืนค่า หรือ ตั้งค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน/เขียน int.

**คืนค่า:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |