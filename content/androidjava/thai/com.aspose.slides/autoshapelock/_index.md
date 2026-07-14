---
title: AutoShapeLock
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดการใช้งานบน AutoshapeEx พาเรนต์
type: docs
url: /th/com.aspose.slides/autoshapelock/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseShapeLock](../../com.aspose.slides/baseshapelock)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
```
public class AutoShapeLock extends BaseShapeLock implements IAutoShapeLock
```

กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดการใช้งานบน AutoshapeEx พาเรนต์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มเป็นสิ่งต้องห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มเป็นสิ่งต้องห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [getRotateLocked()](#getRotateLocked--) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมเมื่อปรับขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมเมื่อปรับขนาดหรือไม่. |
| [getPositionLocked()](#getPositionLocked--) | กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. |
| [getEditPointsLocked()](#getEditPointsLocked--) | กำหนดว่าการเปลี่ยนเส้นขอบของรูปร่างนี้โดยตรงเป็นสิ่งต้องห้ามหรือไม่. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | กำหนดว่าการเปลี่ยนเส้นขอบของรูปร่างนี้โดยตรงเป็นสิ่งต้องห้ามหรือไม่. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | กำหนดว่าการเปลี่ยนค่าการปรับเป็นสิ่งต้องห้ามหรือไม่. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | กำหนดว่าการเปลี่ยนค่าการปรับเป็นสิ่งต้องห้ามหรือไม่. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | กำหนดว่าการเปลี่ยนหัวลูกศรเป็นสิ่งต้องห้ามหรือไม่. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | กำหนดว่าการเปลี่ยนหัวลูกศรเป็นสิ่งต้องห้ามหรือไม่. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | กำหนดว่าการเปลี่ยนประเภทรูปร่างเป็นสิ่งต้องห้ามหรือไม่. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | กำหนดว่าการเปลี่ยนประเภทรูปร่างเป็นสิ่งต้องห้ามหรือไม่. |
| [getTextLocked()](#getTextLocked--) | กำหนดว่าการแก้ไขข้อความเป็นสิ่งต้องห้ามหรือไม่. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | กำหนดว่าการแก้ไขข้อความเป็นสิ่งต้องห้ามหรือไม่. |
### getGroupingLocked() {#getGroupingLocked--}
```
public boolean getGroupingLocked()
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public boolean getSelectLocked()
```

กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public void setSelectLocked(boolean value)
```

กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRotateLocked() {#getRotateLocked--}
```
public boolean getRotateLocked()
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public void setRotateLocked(boolean value)
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public boolean getAspectRatioLocked()
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public void setAspectRatioLocked(boolean value)
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public boolean getPositionLocked()
```

กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public void setPositionLocked(boolean value)
```

กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public boolean getSizeLocked()
```

กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEditPointsLocked() {#getEditPointsLocked--}
```
public boolean getEditPointsLocked()
```

กำหนดว่าการเปลี่ยนเส้นขอบของรูปร่างนี้โดยตรงเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public void setEditPointsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนเส้นขอบของรูปร่างนี้โดยตรงเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public boolean getAdjustHandlesLocked()
```

กำหนดว่าการเปลี่ยนค่าการปรับเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public void setAdjustHandlesLocked(boolean value)
```

กำหนดว่าการเปลี่ยนค่าการปรับเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public boolean getArrowheadsLocked()
```

กำหนดว่าการเปลี่ยนหัวลูกศรเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public void setArrowheadsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนหัวลูกศรเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public boolean getShapeTypeLocked()
```

กำหนดว่าการเปลี่ยนประเภทรูปร่างเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public void setShapeTypeLocked(boolean value)
```

กำหนดว่าการเปลี่ยนประเภทรูปร่างเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getTextLocked() {#getTextLocked--}
```
public boolean getTextLocked()
```

กำหนดว่าการแก้ไขข้อความเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public void setTextLocked(boolean value)
```

กำหนดว่าการแก้ไขข้อความเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |