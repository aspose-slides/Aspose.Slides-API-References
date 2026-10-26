---
title: IReflectionEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: อ็อบเจ็กต์แบบไม่เปลี่ยนแปลงที่แสดงถึงเอฟเฟกต์การสะท้อน
type: docs
url: /th/com.aspose.slides/ireflectioneffectivedata/
---
**ส่วนต่อประสานทั้งหมดที่ใช้งาน:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

อ็อบเจ็กต์แบบไม่เปลี่ยนแปลงที่แสดงถึงเอฟเฟกต์การสะท้อน.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | ระบุตำแหน่งเริ่มต้น (ตามแนวรัศมีสีแอลฟ่า) ของค่าแอลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [getEndPosAlpha()](#getEndPosAlpha--) | ระบุตำแหน่งสุดท้าย (ตามแนวรัศมีสีแอลฟ่า) ของค่าแอลฟ่าในตอนสุดท้าย (เปอร์เซ็นต์). |
| [getFadeDirection()](#getFadeDirection--) | ระบุทิศทางเพื่อชดเชยการสะท้อน. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | ค่าความทึบเริ่มต้นของการสะท้อน. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | ค่าความทึบสุดท้ายของการสะท้อน. |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของการสะท้อน. |
| [getDistance()](#getDistance--) | ระยะของการสะท้อน. |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดแนวสี่เหลี่ยม. |
| [getSkewHorizontal()](#getSkewHorizontal--) | ระบุมุมเบี่ยงแนวนอน. |
| [getSkewVertical()](#getSkewVertical--) | ระบุมุมเบี่ยงแนวตั้ง. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | ระบุว่าการสะท้อนควรหมุนตามรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่. |
| [getScaleHorizontal()](#getScaleHorizontal--) | ระบุตัวคูณสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |
| [getScaleVertical()](#getScaleVertical--) | ระบุตัวคูณสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

ระบุตำแหน่งเริ่มต้น (ตามแนวรัศมีสีแอลฟ่า) ของค่าแอลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

ระบุตำแหน่งสุดท้าย (ตามแนวรัศมีสีแอลฟ่า) ของค่าแอลฟ่าในตอนสุดท้าย (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

ระบุทิศทางเพื่อชดเชยการสะท้อน (มุม). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

ค่าความทึบเริ่มต้นของการสะท้อน (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

ค่าความทึบสุดท้ายของการสะท้อน (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

รัศมีการเบลอ. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

ทิศทางของการสะท้อน. อ่านอย่างเดียว float.

**คืนค่า:**
float

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

ระยะของการสะท้อน. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

การจัดแนวสี่เหลี่ยม. อ่านอย่างเดียว [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**คืนค่า:**
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

ระบุมุมเบี่ยงแนวนอน. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

ระบุมุมเบี่ยงแนวตั้ง. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

ระบุว่าการสะท้อนควรหมุนตามรูปทรงเมื่อรูปทรงถูกหมุนหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

ระบุตัวคูณสเกลแนวนอน, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่านอย่างเดียว double.

**คืนค่า:**
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ระบุตัวคูณสเกลแนวตั้ง, การสเกลเป็นค่าลบทำให้เกิดการพลิก (เปอร์เซ็นต์). อ่านอย่างเดียว double.

**คืนค่า:**
double