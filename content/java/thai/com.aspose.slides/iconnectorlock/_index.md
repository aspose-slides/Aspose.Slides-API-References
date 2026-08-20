---
title: IConnectorLock
second_title: Aspose.Slides สำหรับ Java API Reference
description: กำหนดว่าการดำเนินการใดถูกปิดการทำงานบน Connector พาเรนต์
type: docs
url: /th/com.aspose.slides/iconnectorlock/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

กำหนดว่าการดำเนินการใดถูกปิดการทำงานบน Connector พาเรนต์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าในกลุ่มถูกห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าในกลุ่มถูกห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [getRotateLocked()](#getRotateLocked--) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปร่างต้องคงอัตราส่วนขณะปรับขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปร่างต้องคงอัตราส่วนขณะปรับขนาดหรือไม่. |
| [getPositionMove()](#getPositionMove--) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [getEditPointsLocked()](#getEditPointsLocked--) | กำหนดว่าการเปลี่ยนรูปร่างเส้นลายของรูปร่างนี้โดยตรงถูกห้ามหรือไม่. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | กำหนดว่าการเปลี่ยนรูปร่างเส้นลายของรูปร่างนี้โดยตรงถูกห้ามหรือไม่. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าในกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

กำหนดว่าการเพิ่มรูปร่างนี้เข้าในกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

กำหนดว่ารูปร่างต้องคงอัตราส่วนขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

กำหนดว่าการเปลี่ยนรูปร่างเส้นลายของรูปร่างนี้โดยตรงถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนรูปร่างเส้นลายของรูปร่างนี้โดยตรงถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |