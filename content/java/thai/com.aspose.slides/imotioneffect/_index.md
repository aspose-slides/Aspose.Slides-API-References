---
title: IMotionEffect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงพฤติกรรมของเอฟเฟกต์การเคลื่อนที่.
type: docs
url: /th/com.aspose.slides/imotioneffect/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

แสดงพฤติกรรมของเอฟเฟกต์การเคลื่อนที่ของเอฟเฟ็กต์.
## เมธอด

| Method | Description |
| --- | --- |
| [getFrom()](#getFrom--) | ระบุพิกัด x/y เพื่อเริ่มแอนิเมชันจาก (เป็นเปอร์เซ็นต์). |
| [setFrom(Point2D.Float value)](#setFrom-java.awt.geom.Point2D.Float-) | ระบุพิกัด x/y เพื่อเริ่มแอนิเมชันจาก (เป็นเปอร์เซ็นต์). |
| [getTo()](#getTo--) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [setTo(Point2D.Float value)](#setTo-java.awt.geom.Point2D.Float-) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [getBy()](#getBy--) | อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [setBy(Point2D.Float value)](#setBy-java.awt.geom.Point2D.Float-) | อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [getRotationCenter()](#getRotationCenter--) | อธิบายจุดศูนย์กลางการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. |
| [setRotationCenter(Point2D.Float value)](#setRotationCenter-java.awt.geom.Point2D.Float-) | อธิบายจุดศูนย์กลางการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. |
| [getOrigin()](#getOrigin--) | ระบุตำแหล่งกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับ เช่น การจัดวางสไลด์ หรือพาเรนต์. |
| [setOrigin(int value)](#setOrigin-int-) | ระบุตำแหล่งกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับ เช่น การจัดวางสไลด์ หรือพาเรนต์. |
| [getPath()](#getPath--) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. |
| [getPathEditMode()](#getPathEditMode--) | ระบุวิธีที่เส้นทางการเคลื่อนที่เคลื่อนที่เมื่อรูปทรงถูกย้าย. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | ระบุวิธีที่เส้นทางการเคลื่อนที่เคลื่อนที่เมื่อรูปทรงถูกย้าย. |
| [getAngle()](#getAngle--) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. |
| [setAngle(float value)](#setAngle-float-) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. |

### getFrom() {#getFrom--}
```
public abstract Point2D.Float getFrom()
```

ระบุพิกัด x/y เพื่อเริ่มแอนิเมชันจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float

### setFrom(Point2D.Float value) {#setFrom-java.awt.geom.Point2D.Float-}
```
public abstract void setFrom(Point2D.Float value)
```

ระบุพิกัด x/y เพื่อเริ่มแอนิเมชันจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getTo() {#getTo--}
```
public abstract Point2D.Float getTo()
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float

### setTo(Point2D.Float value) {#setTo-java.awt.geom.Point2D.Float-}
```
public abstract void setTo(Point2D.Float value)
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getBy() {#getBy--}
```
public abstract Point2D.Float getBy()
```

อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float

### setBy(Point2D.Float value) {#setBy-java.awt.geom.Point2D.Float-}
```
public abstract void setBy(Point2D.Float value)
```

อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getRotationCenter() {#getRotationCenter--}
```
public abstract Point2D.Float getRotationCenter()
```

อธิบายจุดศูนย์กลางการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. อ่าน/เขียน java.awt.geom.Point2D.Float.

**คืนค่า:**
java.awt.geom.Point2D.Float

### setRotationCenter(Point2D.Float value) {#setRotationCenter-java.awt.geom.Point2D.Float-}
```
public abstract void setRotationCenter(Point2D.Float value)
```

อธิบายจุดศูนย์กลางการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. อ่าน/เขียน java.awt.geom.Point2D.Float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float |  |

### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```

ระบุตำแหล่งกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับ เช่น การจัดวางสไลด์ หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**คืนค่า:**
int

### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```

ระบุตำแหล่งกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับ เช่น การจัดวางสไลด์ หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public abstract IMotionPath getPath()
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**คืนค่า:**
[IMotionPath](../../com.aspose.slides/imotionpath)

### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public abstract void setPath(IMotionPath value)
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```

ระบุวิธีที่เส้นทางการเคลื่อนที่เคลื่อนที่เมื่อรูปทรงถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**คืนค่า:**
int

### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```

ระบุวิธีที่เส้นทางการเคลื่อนที่เคลื่อนที่เมื่อรูปทรงถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public abstract float getAngle()
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**คืนค่า:**
float

### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |