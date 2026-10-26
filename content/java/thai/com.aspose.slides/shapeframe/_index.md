---
title: ShapeFrame
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงคุณสมบัติของกรอบรูปร่าง.
type: docs
url: /th/com.aspose.slides/shapeframe/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำมาใช้งานทั้งหมด:**
[com.aspose.slides.IShapeFrame](../../com.aspose.slides/ishapeframe)
```
public class ShapeFrame implements IShapeFrame
```

แสดงคุณสมบัติของกรอบรูปร่าง.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)](#ShapeFrame-float-float-float-float-byte-byte-float-) | สร้างคุณสมบัติของกรอบรูปร่างใหม่. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getX()](#getX--) | คืนค่าพิกัด X ของมุมบนซ้ายของกรอบ. |
| [getY()](#getY--) | คืนค่าพิกัด Y ของมุมบนซ้ายของกรอบ. |
| [getWidth()](#getWidth--) | คืนค่าความกว้างของกรอบ. |
| [getHeight()](#getHeight--) | คืนค่าความสูงของกรอบ. |
| [getRotation()](#getRotation--) | คืนค่าจำนวนองศาที่กรอบหมุนรอบแกน Z. |
| [getCenterX()](#getCenterX--) | คืนค่าพิกัด X ของศูนย์กลางกรอบ. |
| [getCenterY()](#getCenterY--) | คืนค่าพิกัด Y ของศูนย์กลางกรอบ. |
| [getFlipH()](#getFlipH--) | ตรวจสอบว่ากรอบถูกพลิกแนวนอนหรือไม่. |
| [getFlipV()](#getFlipV--) | ตรวจสอบว่ากรอบถูกพลิกแนวตั้งหรือไม่. |
| [getRectangle()](#getRectangle--) | คืนค่าพิกัดของกรอบ. |
| [deepClone()](#deepClone--) | ทำสำเนา |
| [cloneT()](#cloneT--) | ทำสำเนา. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | คืนค่าที่บ่งบอกว่าตัวอย่างนี้เท่ากับอ็อบเจกต์ที่ระบุหรือไม่. |
| [equals(ShapeFrame value)](#equals-com.aspose.slides.ShapeFrame-) | คืนค่าที่บ่งบอกว่าตัวอย่างนี้เท่ากับอ็อบเจกต์ที่ระบุหรือไม่. |
### ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle) {#ShapeFrame-float-float-float-float-byte-byte-float-}
```
public ShapeFrame(float x, float y, float width, float height, byte flipH, byte flipV, float rotationAngle)
```

สร้างคุณสมบัติของกรอบรูปร่างใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| x | float | พิกัด X ของกรอบ. |
| y | float | พิกัด Y ของกรอบ. |
| width | float | ความกว้างของกรอบ. |
| height | float | ความสูงของกรอบ. |
| flipH | byte | จริงหากกรอบถูกพลิกแนวนอน. |
| flipV | byte | จริงหากกรอบถูกพลิกแนวตั้ง. |
| rotationAngle | float | จำนวนองศาที่กรอบหมุน. |

### getX() {#getX--}
```
public final float getX()
```

คืนค่าพิกัด X ของมุมบนซ้ายของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getY() {#getY--}
```
public final float getY()
```

คืนค่าพิกัด Y ของมุมบนซ้ายของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getWidth() {#getWidth--}
```
public final float getWidth()
```

คืนค่าความกว้างของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getHeight() {#getHeight--}
```
public final float getHeight()
```

คืนค่าความสูงของกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getRotation() {#getRotation--}
```
public final float getRotation()
```

คืนค่าจำนวนองศาที่กรอบหมุนรอบแกน Z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```

คืนค่าพิกัด X ของศูนย์กลางกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```

คืนค่าพิกัด Y ของศูนย์กลางกรอบ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### getFlipH() {#getFlipH--}
```
public final byte getFlipH()
```

ตรวจสอบว่ากรอบถูกพลิกแนวนอนหรือไม่. อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### getFlipV() {#getFlipV--}
```
public final byte getFlipV()
```

ตรวจสอบว่ากรอบถูกพลิกแนวตั้งหรือไม่. อ่านอย่างเดียว [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte
### getRectangle() {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

คืนค่าพิกัดของกรอบ. อ่านอย่างเดียว java.awt.geom.Rectangle2D.Float.

**คืนค่า:**
java.awt.geom.Rectangle2D.Float
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

ทำสำเนา

**คืนค่า:**
java.lang.Object - กรอบรูปร่างที่ทำสำเนา.
### cloneT() {#cloneT--}
```
public final IShapeFrame cloneT()
```

ทำสำเนา.

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe) - กรอบรูปร่างที่ทำสำเนา.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**คืนค่า:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

คืนค่าที่บ่งบอกว่าตัวอย่างนี้เท่ากับอ็อบเจกต์ที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจกต์ที่จะเปรียบเทียบกับตัวอย่างนี้. |

**คืนค่า:**
boolean - **true** หาก obj เป็น ShapeFrame ที่มีค่าเท่ากับตัวอย่างนี้; มิฉะนั้น **false**.
### equals(ShapeFrame value) {#equals-com.aspose.slides.ShapeFrame-}
```
public final boolean equals(ShapeFrame value)
```

คืนค่าที่บ่งบอกว่าตัวอย่างนี้เท่ากับอ็อบเจกต์ที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ShapeFrame](../../com.aspose.slides/shapeframe) | ShapeFRameEx ที่จะเปรียบเทียบกับตัวอย่างนี้. |

**คืนค่า:**
boolean - **true** หาก value เป็น ShapeFrame ที่มีค่าเท่ากับตัวอย่างนี้; มิฉะนั้น **false**.