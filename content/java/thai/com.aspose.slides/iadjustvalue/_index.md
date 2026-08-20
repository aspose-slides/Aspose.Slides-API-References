---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Represents a geometry shapes adjustment value.
type: docs
url: /th/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Represents a geometry shape's adjustment value. These values affect shape's form.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRawValue()](#getRawValue--) | ส่งคืนหรือกำหนดค่าการปรับ "as is". |
| [setRawValue(long value)](#setRawValue-long-) | ส่งคืนหรือกำหนดค่าการปรับ "as is". |
| [getAngleValue()](#getAngleValue--) | ส่งคืนหรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. |
| [setAngleValue(float value)](#setAngleValue-float-) | ส่งคืนหรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. |
| [getName()](#getName--) | ส่งคืนชื่อของค่าการปรับนี้. |
| [getType()](#getType--) | ส่งคืนประเภทของการปรับรูปทรง. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```

ส่งคืนหรือกำหนดค่าการปรับ "as is". อ่าน/เขียน long.

**คืนค่า:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```

ส่งคืนหรือกำหนดค่าการปรับ "as is". อ่าน/เขียน long.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```

ส่งคืนหรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. อ่าน/เขียน float.

**คืนค่า:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```

ส่งคืนหรือกำหนดค่าโดยตีความเป็นมุมในหน่วยองศา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```

ส่งคืนชื่อของค่าการปรับนี้. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```

ส่งคืนประเภทของการปรับรูปทรง. อ่านอย่างเดียว [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**คืนค่า:**
int