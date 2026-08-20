---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: แสดงการกำหนดแนวทางการวาดที่ปรับได้
type: docs
url: /th/com.aspose.slides/idrawingguide/
---```csharp
public interface IDrawingGuide
```

แสดงการกำหนดแนวทางการวาดที่ปรับได้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOrientation()](#getOrientation--) | ส่งคืนหรือกำหนดทิศทางของแนวทางการวาด |
| [setOrientation(byte value)](#setOrientation-byte-) | ส่งคืนหรือกำหนดทิศทางของแนวทางการวาด |
| [getPosition()](#getPosition--) | ส่งคืนหรือกำหนดตำแหน่งของแนวทางการวาดในหน่วยจุดจากมุมบนซ้ายของสไลด์ |
| [setPosition(float value)](#setPosition-float-) | ส่งคืนหรือกำหนดตำแหน่งของแนวทางการวาดในหน่วยจุดจากมุมบนซ้ายของสไลด์ |
| [getColor()](#getColor--) | ส่งคืนหรือกำหนดสีของแนวทางการวาด |
| [setColor(Color value)](#setColor-java.awt.Color-) | ส่งคืนหรือกำหนดสีของแนวทางการวาด |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


ส่งคืนหรือกำหนดทิศทางของแนวทางการวาด อ่าน/เขียน [Orientation](../../com.aspose.slides/orientation).

**ส่งคืน:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


ส่งคืนหรือกำหนดทิศทางของแนวทางการวาด อ่าน/เขียน [Orientation](../../com.aspose.slides/orientation).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


ส่งคืนหรือกำหนดตำแหน่งของแนวทางการวาดในหน่วยจุดจากมุมบนซ้ายของสไลด์ อ่าน/เขียน float.

--------------------

ค่าช่วงทั่วไปอยู่ระหว่างศูนย์ถึงความสูงของสไลด์สำหรับแนวแนวนอนและศูนย์ถึงความกว้างของสไลด์สำหรับแนวตั้ง

**ส่งคืน:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


ส่งคืนหรือกำหนดตำแหน่งของแนวทางการวาดในหน่วยจุดจากมุมบนซ้ายของสไลด์ อ่าน/เขียน float.

--------------------

ค่าช่วงทั่วไปอยู่ระหว่างศูนย์ถึงความสูงของสไลด์สำหรับแนวแนวนอนและศูนย์ถึงความกว้างของสไลด์สำหรับแนวตั้ง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


ส่งคืนหรือกำหนดสีของแนวทางการวาด อ่าน/เขียน java.awt.Color.

**ส่งคืน:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


ส่งคืนหรือกำหนดสีของแนวทางการวาด อ่าน/เขียน java.awt.Color.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.awt.Color |  |