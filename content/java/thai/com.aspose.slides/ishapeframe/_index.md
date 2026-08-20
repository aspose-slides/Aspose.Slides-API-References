---
title: IShapeFrame
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงคุณสมบัติของเฟรมรูปทรง.
type: docs
url: /th/com.aspose.slides/ishapeframe/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCloneable
```
public interface IShapeFrame extends IGenericCloneable<IShapeFrame>
```

แสดงคุณสมบัติของเฟรมรูปทรง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getX()](#getX--) | ส่งคืนพิกัด X ของมุมซ้ายบนของเฟรม |
| [getY()](#getY--) | ส่งคืนพิกัด Y ของมุมซ้ายบนของเฟรม |
| [getWidth()](#getWidth--) | ส่งคืนความกว้างของเฟรม |
| [getHeight()](#getHeight--) | ส่งคืนความสูงของเฟรม |
| [getRotation()](#getRotation--) | ส่งคืนจำนวนองศาที่เฟรมหมุนรอบแกน Z |
| [getCenterX()](#getCenterX--) | ส่งคืนพิกัด X ของจุดศูนย์กลางของเฟรม |
| [getCenterY()](#getCenterY--) | ส่งคืนพิกัด Y ของจุดศูนย์กลางของเฟรม |
| [getFlipH()](#getFlipH--) | ตรวจสอบว่าเฟรมถูกพลิกแนวนอนหรือไม่ |
| [getFlipV()](#getFlipV--) | ตรวจสอบว่าเฟรมถูกพลิกแนวตั้งหรือไม่ |
| [getRectangle()](#getRectangle--) | ส่งคืนพิกัดของเฟรม |
### getX() {#getX--}
```
public abstract float getX()
```


ส่งคืนพิกัด X ของมุมซ้ายบนของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getY() {#getY--}
```
public abstract float getY()
```


ส่งคืนพิกัด Y ของมุมซ้ายบนของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getWidth() {#getWidth--}
```
public abstract float getWidth()
```


ส่งคืนความกว้างของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


ส่งคืนความสูงของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```


ส่งคืนจำนวนองศาที่เฟรมหมุนรอบแกน Z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่านอย่างเดียว float

**Returns:**
float
### getCenterX() {#getCenterX--}
```
public abstract float getCenterX()
```


ส่งคืนพิกัด X ของจุดศูนย์กลางของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getCenterY() {#getCenterY--}
```
public abstract float getCenterY()
```


ส่งคืนพิกัด Y ของจุดศูนย์กลางของเฟรม อ่านอย่างเดียว float

**Returns:**
float
### getFlipH() {#getFlipH--}
```
public abstract byte getFlipH()
```


ตรวจสอบว่าเฟรมถูกพลิกแนวนอนหรือไม่ อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool)

**Returns:**
byte
### getFlipV() {#getFlipV--}
```
public abstract byte getFlipV()
```


ตรวจสอบว่าเฟรมถูกพลิกแนวตั้งหรือไม่ อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool)

**Returns:**
byte
### getRectangle() {#getRectangle--}
```
public abstract Rectangle2D.Float getRectangle()
```


ส่งคืนพิกัดของเฟรม อ่านอย่างเดียว java.awt.geom.Rectangle2D.Float

**Returns:**
java.awt.geom.Rectangle2D.Float