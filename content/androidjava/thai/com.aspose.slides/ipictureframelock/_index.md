---
title: IPictureFrameLock
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: กำหนดว่าการทำงานใดบ้างที่ถูกปิดการใช้งานบน PictureFrameEx พาเรนท์
type: docs
url: /th/com.aspose.slides/ipictureframelock/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IPictureFrameLock extends IBaseShapeLock
```

กำหนดว่าการทำงานใดบ้างที่ถูกปิดการใช้งานบนพาเรนท์ PictureFrameEx.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มเป็นสิ่งต้องห้ามหรือไม่ |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มเป็นสิ่งต้องห้ามหรือไม่ |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [getRotationLocked()](#getRotationLocked--) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปร่างนี้ต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่ |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปร่างนี้ต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่ |
| [getPositionLocked()](#getPositionLocked--) | กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [getEditPointsLocked()](#getEditPointsLocked--) | กำหนดว่าการเปลี่ยนรูปทรงโดยตรงของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | กำหนดว่าการเปลี่ยนรูปทรงโดยตรงของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่ |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | กำหนดว่าการเปลี่ยนค่าปรับแต่งเป็นสิ่งต้องห้ามหรือไม่ |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | กำหนดว่าการเปลี่ยนค่าปรับแต่งเป็นสิ่งต้องห้ามหรือไม่ |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | กำหนดว่าการเปลี่ยนหัวศรเป็นสิ่งต้องห้ามหรือไม่ |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | กำหนดว่าการเปลี่ยนหัวศรเป็นสิ่งต้องห้ามหรือไม่ |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างเป็นสิ่งต้องห้ามหรือไม่ |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างเป็นสิ่งต้องห้ามหรือไม่ |
| [getCropLocked()](#getCropLocked--) | กำหนดว่าการครอปภาพเป็นสิ่งต้องห้ามหรือไม่ |
| [setCropLocked(boolean value)](#setCropLocked-boolean-) | กำหนดว่าการครอปภาพเป็นสิ่งต้องห้ามหรือไม่ |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

กำหนดว่าการเลือกรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

กำหนดว่ารูปร่างนี้ต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

กำหนดว่ารูปร่างนี้ต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

กำหนดว่าการย้ายรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาดรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

กำหนดว่าการเปลี่ยนรูปทรงโดยตรงของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนรูปทรงโดยตรงของรูปร่างนี้เป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

กำหนดว่าการเปลี่ยนค่าปรับแต่งเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

กำหนดว่าการเปลี่ยนค่าปรับแต่งเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

กำหนดว่าการเปลี่ยนหัวศรเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนหัวศรเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getCropLocked() {#getCropLocked--}
```
public abstract boolean getCropLocked()
```

กำหนดว่าการครอปภาพเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setCropLocked(boolean value) {#setCropLocked-boolean-}
```
public abstract void setCropLocked(boolean value)
```

กำหนดว่าการครอปภาพเป็นสิ่งต้องห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |