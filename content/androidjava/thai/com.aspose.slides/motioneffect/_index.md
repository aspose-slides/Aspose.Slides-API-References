---
title: MotionEffect
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงพฤติกรรมของเอฟเฟกต์การเคลื่อนไหว
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

แสดงพฤติกรรมของเอฟเฟกต์การเคลื่อนไหวของเอฟเฟ็กต์
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MotionEffect()](#MotionEffect--) |  |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์) |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์) |
| [getTo()](#getTo--) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนไหว (เป็นเปอร์เซ็นต์) |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนไหว (เป็นเปอร์เซ็นต์) |
| [getBy()](#getBy--) | อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) |
| [getRotationCenter()](#getRotationCenter--) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนไหวด้วยมุม X |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนไหวด้วยมุม X |
| [getOrigin()](#getOrigin--) | ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น วิธีจัดเรียงของสไลด์ หรือพาเรนต์ |
| [setOrigin(int value)](#setOrigin-int-) | ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น วิธีจัดเรียงของสไลด์ หรือพาเรนต์ |
| [getPath()](#getPath--) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนไหว |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนไหว |
| [getPathEditMode()](#getPathEditMode--) | ระบุว่าการเคลื่อนที่ของเส้นทางการเคลื่อนไหวทำอย่างไรเมื่อรูปทรงถูกย้าย |
| [setPathEditMode(int value)](#setPathEditMode-int-) | ระบุว่าการเคลื่อนที่ของเส้นทางการเคลื่อนไหวทำอย่างไรเมื่อรูปทรงถูกย้าย |
| [getAngle()](#getAngle--) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนไหว |
| [setAngle(float value)](#setAngle-float-) | อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนไหว |
### MotionEffect() {#MotionEffect--}
```
public MotionEffect()
```

### getFrom() {#getFrom--}
```
public final PointF getFrom()
```

ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**  
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public final void setFrom(PointF value)
```

ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getTo() {#getTo--}
```
public final PointF getTo()
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**  
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public final void setTo(PointF value)
```

ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getBy() {#getBy--}
```
public final PointF getBy()
```

อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**  
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public final void setBy(PointF value)
```

อธิบายค่าการเยื้องเชิงสัมพันธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getRotationCenter() {#getRotationCenter--}
```
public final PointF getRotationCenter()
```

อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนไหวด้วยมุม X อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**  
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public final void setRotationCenter(PointF value)
```

อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนไหวด้วยมุม X อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |

### getOrigin() {#getOrigin--}
```
public final int getOrigin()
```

ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น วิธีจัดเรียงของสไลด์ หรือพาเรนต์ อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**คืนค่า:**  
int
### setOrigin(int value) {#setOrigin-int-}
```
public final void setOrigin(int value)
```

ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น วิธีจัดเรียงของสไลด์ หรือพาเรนต์ อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPath() {#getPath--}
```
public final IMotionPath getPath()
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนไหว อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**คืนค่า:**  
[IMotionPath](../../com.aspose.slides/imotionpath)
### setPath(IMotionPath value) {#setPath-com.aspose.slides.IMotionPath-}
```
public final void setPath(IMotionPath value)
```

ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนไหว อ่าน/เขียน [IMotionPath](../../com.aspose.slides/imotionpath).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |

### getPathEditMode() {#getPathEditMode--}
```
public final int getPathEditMode()
```

ระบุว่าการเคลื่อนที่ของเส้นทางการเคลื่อนไหวทำอย่างไรเมื่อรูปทรงถูกย้าย อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**คืนค่า:**  
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public final void setPathEditMode(int value)
```

ระบุว่าการเคลื่อนที่ของเส้นทางการเคลื่อนไหวทำอย่างไรเมื่อรูปทรงถูกย้าย อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนไหว อ่าน/เขียน float.

**คืนค่า:**  
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```

อธิบายมุมเชิงสัมพันธ์ของเส้นทางการเคลื่อนไหว อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |