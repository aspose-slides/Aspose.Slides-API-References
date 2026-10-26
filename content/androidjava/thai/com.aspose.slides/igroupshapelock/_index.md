---
title: IGroupShapeLock
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: กำหนดว่าการดำเนินการใดถูกปิดการใช้งานบน GroupShape พาเรนท์.
type: docs
url: /th/com.aspose.slides/igroupshapelock/
---
**ทั้งหมดของ Interface ที่ทำการ Implement:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGroupShapeLock extends IBaseShapeLock
```

กำหนดว่าการดำเนินการใดถูกปิดการใช้งานบน GroupShape พาเรนท์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่ม shape นี้ไปยัง group ถูกห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่ม shape นี้ไปยัง group ถูกห้ามหรือไม่. |
| [getUngroupingLocked()](#getUngroupingLocked--) | กำหนดว่าการแยก groupshape นี้ถูกห้ามหรือไม่. |
| [setUngroupingLocked(boolean value)](#setUngroupingLocked-boolean-) | กำหนดว่าการแยก groupshape นี้ถูกห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือก shape นี้ถูกห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือก shape นี้ถูกห้ามหรือไม่. |
| [getRotationLocked()](#getRotationLocked--) | กำหนดว่าการเปลี่ยนมุมการหมุนของ shape นี้ถูกห้ามหรือไม่. |
| [setRotationLocked(boolean value)](#setRotationLocked-boolean-) | กำหนดว่าการเปลี่ยนมุมการหมุนของ shape นี้ถูกห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่า shape ต้องรักษาอัตราส่วนภาพขณะปรับขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่า shape ต้องรักษาอัตราส่วนภาพขณะปรับขนาดหรือไม่. |
| [getPositionLocked()](#getPositionLocked--) | กำหนดว่าการย้าย shape นี้ถูกห้ามหรือไม่. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | กำหนดว่าการย้าย shape นี้ถูกห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาด shape นี้ถูกห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาด shape นี้ถูกห้ามหรือไม่. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

กำหนดว่าการเพิ่ม shape นี้ไปยัง group ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่ม shape นี้ไปยัง group ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getUngroupingLocked() {#getUngroupingLocked--}
```
public abstract boolean getUngroupingLocked()
```

กำหนดว่าการแยก groupshape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setUngroupingLocked(boolean value) {#setUngroupingLocked-boolean-}
```
public abstract void setUngroupingLocked(boolean value)
```

กำหนดว่าการแยก groupshape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

กำหนดว่าการเลือก shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

กำหนดว่าการเลือก shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getRotationLocked() {#getRotationLocked--}
```
public abstract boolean getRotationLocked()
```

กำหนดว่าการเปลี่ยนมุมการหมุนของ shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotationLocked(boolean value) {#setRotationLocked-boolean-}
```
public abstract void setRotationLocked(boolean value)
```

กำหนดว่าการเปลี่ยนมุมการหมุนของ shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

กำหนดว่า shape ต้องรักษาอัตราส่วนภาพขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

กำหนดว่า shape ต้องรักษาอัตราส่วนภาพขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

กำหนดว่าการย้าย shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

กำหนดว่าการย้าย shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

กำหนดว่าการปรับขนาด shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาด shape นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |