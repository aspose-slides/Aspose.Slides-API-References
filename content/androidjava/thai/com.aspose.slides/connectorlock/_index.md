---
title: ConnectorLock
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: กำหนดว่าการดำเนินการใดบ้างถูกปิดการใช้งานบน Connector พาเรนต์
type: docs
url: /th/com.aspose.slides/connectorlock/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseShapeLock](../../com.aspose.slides/baseshapelock)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IConnectorLock](../../com.aspose.slides/iconnectorlock)
```
public class ConnectorLock extends BaseShapeLock implements IConnectorLock
```

กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดการใช้งานบน parent Connector.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่. |
| [getSelectLocked()](#getSelectLocked--) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. |
| [getRotateLocked()](#getRotateLocked--) | กำหนดว่าการเปลี่ยนแปลงมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | กำหนดว่าการเปลี่ยนแปลงมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | กำหนดว่ารูปร่างจะต้องรักษาอัตราส่วนขณะปรับขนาดหรือไม่. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | กำหนดว่ารูปร่างจะต้องรักษาอัตราส่วนขณะปรับขนาดหรือไม่. |
| [getPositionMove()](#getPositionMove--) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. |
| [getSizeLocked()](#getSizeLocked--) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. |
| [getEditPointsLocked()](#getEditPointsLocked--) | กำหนดว่าการเปลี่ยนรูปร่างเส้นขอบโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | กำหนดว่าการเปลี่ยนรูปร่างเส้นขอบโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | กำหนดว่าการปรับค่าปรับเปลี่ยนถูกห้ามหรือไม่. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | กำหนดว่าการปรับค่าปรับเปลี่ยนถูกห้ามหรือไม่. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. |
### getGroupingLocked() {#getGroupingLocked--}
```
public boolean getGroupingLocked()
```


กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public void setGroupingLocked(boolean value)
```


กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public boolean getSelectLocked()
```


กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public void setSelectLocked(boolean value)
```


กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public boolean getRotateLocked()
```


กำหนดว่าการเปลี่ยนแปลงมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public void setRotateLocked(boolean value)
```


กำหนดว่าการเปลี่ยนแปลงมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public boolean getAspectRatioLocked()
```


กำหนดว่ารูปร่างจะต้องรักษาอัตราส่วนขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public void setAspectRatioLocked(boolean value)
```


กำหนดว่ารูปร่างจะต้องรักษาอัตราส่วนขณะปรับขนาดหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public boolean getPositionMove()
```


กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public void setPositionMove(boolean value)
```


กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public boolean getSizeLocked()
```


กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public void setSizeLocked(boolean value)
```


กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public boolean getEditPointsLocked()
```


กำหนดว่าการเปลี่ยนรูปร่างเส้นขอบโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public void setEditPointsLocked(boolean value)
```


กำหนดว่าการเปลี่ยนรูปร่างเส้นขอบโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public boolean getAdjustHandlesLocked()
```


กำหนดว่าการปรับค่าปรับเปลี่ยนถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public void setAdjustHandlesLocked(boolean value)
```


กำหนดว่าการปรับค่าปรับเปลี่ยนถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public boolean getArrowheadsLocked()
```


กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public void setArrowheadsLocked(boolean value)
```


กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public boolean getShapeTypeLocked()
```


กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public void setShapeTypeLocked(boolean value)
```


กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |