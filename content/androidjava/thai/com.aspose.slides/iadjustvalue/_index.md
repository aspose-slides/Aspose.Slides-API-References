---
title: IAdjustValue
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงค่าการปรับรูปทรงเรขาคณิต
type: docs
url: /th/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

เป็นค่าการปรับรูปทรงเรขาคณิต. ค่าต่าง ๆ เหล่านี้ส่งผลต่อรูปทรง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRawValue()](#getRawValue--) | คืนค่า หรือกำหนดค่าการปรับ "ตามที่เป็น". |
| [setRawValue(long value)](#setRawValue-long-) | คืนค่า หรือกำหนดค่าการปรับ "ตามที่เป็น". |
| [getAngleValue()](#getAngleValue--) | คืนค่า หรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. |
| [setAngleValue(float value)](#setAngleValue-float-) | คืนค่า หรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. |
| [getName()](#getName--) | คืนชื่อของค่าการปรับนี้. |
| [getType()](#getType--) | คืนประเภทของการปรับรูปทรง. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

คืนค่า หรือกำหนดค่าการปรับ "ตามที่เป็น". อ่าน/เขียน long.

**คืนค่า:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

คืนค่า หรือกำหนดค่าการปรับ "ตามที่เป็น". อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | long |  |
### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

คืนค่า หรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. อ่าน/เขียน float.

**คืนค่า:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

คืนค่า หรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |
### getName() {#getName--}
```
public abstract String getName()
```

คืนชื่อของค่าการปรับนี้. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

คืนประเภทของการปรับรูปทรง. อ่านอย่างเดียว [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**คืนค่า:**
int