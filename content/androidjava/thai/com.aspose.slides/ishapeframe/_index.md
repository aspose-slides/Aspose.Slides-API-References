---
title: IShapeFrame
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคุณสมบัติของกรอบรูปร่าง.
type: docs
url: /th/com.aspose.slides/ishapeframe/
---
**อินเทอร์เฟซที่ทำการนำมาทั้งหมด:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

แสดงคุณสมบัติของกรอบรูปร่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getX()](#getX--) | ส่งคืนพิกัด X ของมุมซ้ายบนของกรอบ |
| [getY()](#getY--) | ส่งคืนพิกัด Y ของมุมซ้ายบนของกรอบ |
| [getWidth()](#getWidth--) | ส่งคืนความกว้างของกรอบ |
| [getHeight()](#getHeight--) | ส่งคืนความสูงของกรอบ |
| [getRotation()](#getRotation--) | ส่งคืนจำนวนองศาที่กรอบถูกหมุนรอบแกน z |
| [getCenterX()](#getCenterX--) | ส่งคืนพิกัด X ของจุดศูนย์กลางของกรอบ |
| [getCenterY()](#getCenterY--) | ส่งคืนพิกัด Y ของจุดศูนย์กลางของกรอบ |
| [getFlipH()](#getFlipH--) | กำหนดว่ากรอบถูกพลิกแนวนอนหรือไม่ |
| [getFlipV()](#getFlipV--) | กำหนดว่ากรอบถูกพลิกแนวตั้งหรือไม่ |
| [getRectangle()](#getRectangle--) | ส่งคืนพิกัดของกรอบ |
### getX() {#getX--}
```
public abstract float getX()
```


ส่งคืนพิกัด X ของมุมซ้ายบนของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getY() {#getY--}
```
public abstract float getY()
```


ส่งคืนพิกัด Y ของมุมซ้ายบนของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


ส่งคืนความกว้างของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


ส่งคืนความสูงของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


ส่งคืนจำนวนองศาที่กรอบถูกหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฏิกา. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


ส่งคืนพิกัด X ของจุดศูนย์กลางของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


ส่งคืนพิกัด Y ของจุดศูนย์กลางของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


กำหนดว่ากรอบถูกพลิกแนวนอนหรือไม่. อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


กำหนดว่ากรอบถูกพลิกแนวตั้งหรือไม่. อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### getRectangle() {#getRectangle--}
```
public abstract RectF getRectangle()
```


ส่งคืนพิกัดของกรอบ. อ่านอย่างเดียว android.graphics.RectF.

**คืนค่า:**
android.graphics.RectF