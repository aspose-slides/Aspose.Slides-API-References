---
title: MotionEffect
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงพฤติกรรมของเอฟเฟ็กต์การเคลื่อนที่
type: docs
url: /th/com.aspose.slides/motioneffect/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.Behavior](../../com.aspose.slides/behavior)

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**  
[com.aspose.slides.IMotionEffect](../../com.aspose.slides/imotioneffect)  
```
public class MotionEffect extends Behavior implements IMotionEffect
```

แสดงพฤติกรรมผลกระทบการเคลื่อนไหวของเอฟเฟ็กต์  
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [getTo()](#getTo--) | ระบุตำแหน่งเป้าหมายสำหรับผลกระทบการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | ระบุตำแหน่งเป้าหมายสำหรับผลกระทบการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [getBy()](#getBy--) | อธิบายค่าการเลื่อนเชิงสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | อธิบายค่าการเลื่อนเชิงสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์). |
| [getRotationCenter()](#getRotationCenter--) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่ตามมุม X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่ตามมุม X. |
| [getOrigin()](#getOrigin--) | ระบุตัวกำเนิดของเส้นทางการเคลื่อนที่ว่าอ้างอิง relative กับอะไร เช่น Layout ของสไลด์ หรือพาเรนต์. |
| [setOrigin(int value)](#setOrigin-int-) | ระบุตัวกำเนิดของเส้นทางการเคลื่อนที่ว่าอ้างอิง relative กับอะไร เช่น Layout ของสไลด์ หรือพาเรนต์. |
| [getPath()](#getPath--) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของอนิเมชัน. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของอนิเมชัน. |
| [getPathEditMode()](#getPathEditMode--) | ระบุว่ากราฟการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | ระบุว่ากราฟการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. |
| [getAngle()](#getAngle--) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. |
| [setAngle(float value)](#setAngle-float-) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final Point2D.Float getFrom()
```

ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float
### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public final void setFrom(Point2D.Float value)
```

ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public final Point2D.Float getTo()
```

ระบุตำแหน่งเป้าหมายสำหรับผลกระทบการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float
### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public final void setTo(Point2D.Float value)
```

ระบุตำแหน่งเป้าหมายสำหรับผลกระทบการเคลื่อนไหว (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public final Point2D.Float getBy()
```

อธิบายค่าการเลื่อนเชิงสัมพัทธ์สำหรับการเคลื่อนที่ (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float
### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public final void setBy(Point2D.Float value)
```

อธิบายค่าการเลื่อนเชิงสัมพัทธ์สำหรับการเคลื่อนที่ (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public final Point2D.Float getRotationCenter()
```

อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่ตามมุม X. อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float
### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public final void setRotationCenter(Point2D.Float value)
```

อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่ตามมุม X. อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

ระบุตัวกำเนิดของเส้นทางการเคลื่อนที่ว่าอ้างอิง relative กับอะไร เช่น Layout ของสไลด์ หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**คืนค่า:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

ระบุตัวกำเนิดของเส้นทางการเคลื่อนที่ว่าอ้างอิง relative กับอะไร เช่น Layout ของสไลด์ หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของอนิเมชัน. อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**คืนค่า:**
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของอนิเมชัน. อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

ระบุว่ากราฟการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**คืนค่า:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

ระบุว่ากราฟการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**คืนค่า:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |