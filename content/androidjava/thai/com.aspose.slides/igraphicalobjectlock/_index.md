---
title: IGraphicalObjectLock
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: กำหนดว่าการดำเนินการใดถูกปิดใช้งานบน GraphicalObject พาเรนต์
type: docs
url: /th/com.aspose.slides/igraphicalobjectlock/
---
**ส่วนต่อประสานที่ทำทั้งหมด:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IGraphicalObjectLock extends IBaseShapeLock
```

กำหนดว่าการดำเนินการใดถูกปิดใช้งานบน GraphicalObject พาเรนต์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปนี้ลงในกลุ่มถูกห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปนี้ลงในกลุ่มถูกห้ามหรือไม่. |
| [getDrilldownLocked()](#getDrilldownLocked--) | กำหนดว่าการเลือกรูปย่อยของอ็อบเจ็กต์นี้ถูกห้ามหรือไม่. |
| [setDrilldownLocked(boolean value)](#setDrilldownLocked-boolean-) | กำหนดว่าการเลือกรูปย่อยของอ็อบเจ็กต์นี้ถูกห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. |
| [getPositionLocked()](#getPositionLocked--) | กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. |
| [setPositionLocked(boolean value)](#setPositionLocked-boolean-) | กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

กำหนดว่าการเพิ่มรูปนี้ลงในกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่มรูปนี้ลงในกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDrilldownLocked() {#getDrilldownLocked--}
```
public abstract boolean getDrilldownLocked()
```

กำหนดว่าการเลือกรูปย่อยของอ็อบเจ็กต์นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setDrilldownLocked(boolean value) {#setDrilldownLocked-boolean-}
```
public abstract void setDrilldownLocked(boolean value)
```

กำหนดว่าการเลือกรูปย่อยของอ็อบเจ็กต์นี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

กำหนดว่ารูปต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

กำหนดว่ารูปต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPositionLocked() {#getPositionLocked--}
```
public abstract boolean getPositionLocked()
```

กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setPositionLocked(boolean value) {#setPositionLocked-boolean-}
```
public abstract void setPositionLocked(boolean value)
```

กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |