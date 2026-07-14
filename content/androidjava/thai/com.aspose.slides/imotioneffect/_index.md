---
title: IMotionEffect
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนพฤติกรรมของเอฟเฟ็กต์การเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/imotioneffect/
---
**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IMotionEffect extends IBehavior
```

แทนพฤติกรรมของเอฟเฟ็กต์การเคลื่อนไหวของเอฟเฟ็กต์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFrom()](#getFrom--) | ระบุตำแหน่งพิกัด x/y ที่เริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [setFrom(PointF value)](#setFrom-android.graphics.PointF-) | ระบุตำแหน่งพิกัด x/y ที่เริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). |
| [getTo()](#getTo--) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวของการแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [setTo(PointF value)](#setTo-android.graphics.PointF-) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวของการแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [getBy()](#getBy--) | อธิบายค่าการเยื้องสัมพัทธ์สำหรับการแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [setBy(PointF value)](#setBy-android.graphics.PointF-) | อธิบายค่าการเยื้องสัมพัทธ์สำหรับการแอนิเมชัน (เป็นเปอร์เซ็นต์). |
| [getRotationCenter()](#getRotationCenter--) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. |
| [setRotationCenter(PointF value)](#setRotationCenter-android.graphics.PointF-) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. |
| [getOrigin()](#getOrigin--) | ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับอะไร เช่น การจัดวางของสไลด์หรือพาเรนต์. |
| [setOrigin(int value)](#setOrigin-int-) | ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับอะไร เช่น การจัดวางของสไลด์หรือพาเรนต์. |
| [getPath()](#getPath--) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. |
| [setPath(IMotionPath value)](#setPath-com.aspose.slides.IMotionPath-) | ระบุ primitive ของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน. |
| [getPathEditMode()](#getPathEditMode--) | ระบุว่าเส้นทางการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. |
| [setPathEditMode(int value)](#setPathEditMode-int-) | ระบุว่าเส้นทางการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. |
| [getAngle()](#getAngle--) | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่. |
| [setAngle(float value)](#setAngle-float-) | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่. |
### getFrom() {#getFrom--}
```
public abstract PointF getFrom()
```


ระบุตำแหน่งพิกัด x/y ที่เริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setFrom(PointF value) {#setFrom-android.graphics.PointF-}
```
public abstract void setFrom(PointF value)
```


ระบุตำแหน่งพิกัด x/y ที่เริ่มการเคลื่อนไหวจาก (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getTo() {#getTo--}
```
public abstract PointF getTo()
```


ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวของการแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setTo(PointF value) {#setTo-android.graphics.PointF-}
```
public abstract void setTo(PointF value)
```


ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวของการแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getBy() {#getBy--}
```
public abstract PointF getBy()
```


อธิบายค่าการเยื้องสัมพัทธ์สำหรับการแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setBy(PointF value) {#setBy-android.graphics.PointF-}
```
public abstract void setBy(PointF value)
```


อธิบายค่าการเยื้องสัมพัทธ์สำหรับการแอนิเมชัน (เป็นเปอร์เซ็นต์). อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getRotationCenter() {#getRotationCenter--}
```
public abstract PointF getRotationCenter()
```


อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. อ่าน/เขียน android.graphics.PointF.

**คืนค่า:**
android.graphics.PointF
### setRotationCenter(PointF value) {#setRotationCenter-android.graphics.PointF-}
```
public abstract void setRotationCenter(PointF value)
```


อธิบายจุดศูนย์กลางของการหมุนที่ใช้ในการหมุนเส้นทางการเคลื่อนที่โดยมุม X. อ่าน/เขียน android.graphics.PointF.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF |  |
### getOrigin() {#getOrigin--}
```
public abstract int getOrigin()
```


ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับอะไร เช่น การจัดวางของสไลด์หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**คืนค่า:**
int
### setOrigin(int value) {#setOrigin-int-}
```
public abstract void setOrigin(int value)
```


ระบุว่าต้นกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับอะไร เช่น การจัดวางของสไลด์หรือพาเรนต์. อ่าน/เขียน [MotionOriginType](../../com.aspose.slides/motionorigintype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IMotionPath](../../com.aspose.slides/imotionpath) |  |
### getPathEditMode() {#getPathEditMode--}
```
public abstract int getPathEditMode()
```


ระบุว่าเส้นทางการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**คืนค่า:**
int
### setPathEditMode(int value) {#setPathEditMode-int-}
```
public abstract void setPathEditMode(int value)
```


ระบุว่าเส้นทางการเคลื่อนที่จะเคลื่อนที่อย่างไรเมื่อรูปร่างถูกย้าย. อ่าน/เขียน [MotionPathEditMode](../../com.aspose.slides/motionpatheditmode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getAngle() {#getAngle--}
```
public abstract float getAngle()
```


อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**คืนค่า:**
float
### setAngle(float value) {#setAngle-float-}
```
public abstract void setAngle(float value)
```


อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |