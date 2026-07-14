---
title: IScaleEffect
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: แสดงถึงเอฟเฟกต์การปรับสเกลของแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/iscaleeffect/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IScaleEffect extends IBehavior
```

Represents animation scale effect.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getZoomContent()](#getZoomContent--) | กำหนดว่าควรซูมเนื้อหาหรือไม่. |
| [setZoomContent(byte value)](#setZoomContent-byte-) | กำหนดว่าควรซูมเนื้อหาหรือไม่. |
| [getFrom()](#getFrom--) | ระบุตำแหน่ง x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | ระบุตำแหน่ง x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [getTo()](#getTo--) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การปรับสเกลของการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การปรับสเกลของการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [getBy()](#getBy--) | อธิบายค่าการเลื่อนสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | อธิบายค่าการเลื่อนสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |

### getZoomContent() {#getZoomContent--}
```
public abstract byte getZoomContent()
```

กำหนดว่าควรซูมเนื้อหาหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setZoomContent(byte value) {#setZoomContent-byte-}
```
public abstract void setZoomContent(byte value)
```

กำหนดว่าควรซูมเนื้อหาหรือไม่ อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```

ระบุตำแหน่ง x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF

### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```

ระบุตำแหน่ง x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public abstract PointF getTo()
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การปรับสเกลของการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF

### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การปรับสเกลของการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public abstract PointF getBy()
```

อธิบายค่าการเลื่อนสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF

### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```

อธิบายค่าการเลื่อนสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |