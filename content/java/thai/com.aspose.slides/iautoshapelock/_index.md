---
title: IAutoShapeLock
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดใช้งานบน AutoshapeEx พาเรนต์
type: docs
url: /th/com.aspose.slides/iautoshapelock/
---
**ส่วนต่อประสานที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IAutoShapeLock extends IBaseShapeLock
```

กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดใช้งานบน AutoshapeEx พาเรนต์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [getRotateLocked()](#getRotateLocked--) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อเปลี่ยนขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อเปลี่ยนขนาดหรือไม่. |
| [getPositionLocked()](#getPositionLocked--) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [getEditPointsLocked()](#getEditPointsLocked--) | กำหนดว่าการเปลี่ยนเส้นรอบรูปร่างนี้โดยตรงถูกห้ามหรือไม่. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | กำหนดว่าการเปลี่ยนเส้นรอบรูปร่างนี้โดยตรงถูกห้ามหรือไม่. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | กำหนดว่าการเปลี่ยนค่าการปรับถูกห้ามหรือไม่. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | กำหนดว่าการเปลี่ยนค่าการปรับถูกห้ามหรือไม่. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | กำหนดว่าการเปลี่ยนหัวศรถูกห้ามหรือไม่. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | กำหนดว่าการเปลี่ยนหัวศรถูกห้ามหรือไม่. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
| [getTextLocked()](#getTextLocked--) | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่. |
| [setTextLocked(boolean value)](#setTextLocked-boolean-) | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อเปลี่ยนขนาดหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อเปลี่ยนขนาดหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

กำหนดว่าการเปลี่ยนเส้นรอบรูปร่างนี้โดยตรงถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนเส้นรอบรูปร่างนี้โดยตรงถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

กำหนดว่าการเปลี่ยนค่าการปรับถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

กำหนดว่าการเปลี่ยนค่าการปรับถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

กำหนดว่าการเปลี่ยนหัวศรถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนหัวศรถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getTextLocked() {#getTextLocked--}
```
public abstract boolean getTextLocked()
```

กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**คืนค่า:**
boolean
### setTextLocked(boolean value) {#setTextLocked-boolean-}
```
public abstract void setTextLocked(boolean value)
```

กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่. บูลีนแบบอ่าน-เขียน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |