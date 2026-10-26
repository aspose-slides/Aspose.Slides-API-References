---
title: IReflectionEffectiveData
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของเอฟเฟกต์การสะท้อน.
type: docs
url: /th/com.aspose.slides/ireflectioneffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IReflectionEffectiveData extends IEffectEffectiveData
```

Immutable object which represents a Reflection effect.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getStartPosAlpha()](#getStartPosAlpha--) | ระบุตำแหน่งเริ่มต้น (ตามแนวระดับสีกราเดียนต์อัลฟา) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). |
| [getEndPosAlpha()](#getEndPosAlpha--) | ระบุตำแหน่งสุดท้าย (ตามแนวระดับสีกราเดียนต์อัลฟา) ของค่าอัลฟ่าเป็นสุดท้าย (เปอร์เซ็นต์). |
| [getFadeDirection()](#getFadeDirection--) | ระบุทิศทางการยกเลื่อนการสะท้อน. |
| [getStartReflectionOpacity()](#getStartReflectionOpacity--) | ความทึบของการสะท้อนเริ่มต้น. |
| [getEndReflectionOpacity()](#getEndReflectionOpacity--) | ความทึบของการสะท้อนสุดท้าย. |
| [getBlurRadius()](#getBlurRadius--) | รัศมีการเบลอ. |
| [getDirection()](#getDirection--) | ทิศทางของการสะท้อน. |
| [getDistance()](#getDistance--) | ระยะทางการสะท้อน. |
| [getRectangleAlign()](#getRectangleAlign--) | การจัดตำแหน่งสี่เหลี่ยม. |
| [getSkewHorizontal()](#getSkewHorizontal--) | ระบุมุมบิดแนวนอน. |
| [getSkewVertical()](#getSkewVertical--) | ระบุมุมบิดแนวตั้ง. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | ระบุว่าการสะท้อนควรหมุนไปพร้อมกับรูปทรงหรือไม่หากรูปทรงถูกหมุน. |
| [getScaleHorizontal()](#getScaleHorizontal--) | ระบุอัตราการสเกลแนวนอน, การสเกลค่าติดลบทำให้เกิดการพลิก. |
| [getScaleVertical()](#getScaleVertical--) | ระบุอัตราการสเกลแนวตั้ง, การสเกลค่าติดลบทำให้เกิดการพลิก. |

### getStartPosAlpha() {#getStartPosAlpha--}
```
public abstract float getStartPosAlpha()
```

ระบุตำแหน่งเริ่มต้น (ตามแนวระดับสีกราเดียนต์อัลฟา) ของค่าอัลฟ่าเริ่มต้น (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getEndPosAlpha() {#getEndPosAlpha--}
```
public abstract float getEndPosAlpha()
```

ระบุตำแหน่งสุดท้าย (ตามแนวระดับสีกราเดียนต์อัลฟา) ของค่าอัลฟ่าเป็นสุดท้าย (เปอร์เซ็นต์). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getFadeDirection() {#getFadeDirection--}
```
public abstract float getFadeDirection()
```

ระบุทิศทางการยกเลื่อนการสะท้อน. (angle). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getStartReflectionOpacity() {#getStartReflectionOpacity--}
```
public abstract float getStartReflectionOpacity()
```

ความทึบของการสะท้อนเริ่มต้น. (percents). อ่านอย่างเดียว float.

**คืนค่า:**
float

### getEndReflectionOpacity() {#getEndReflectionOpacity--}
```
public abstract float getEndReflectionOpacity()
```

ความทึบของการสะท้อนสุดท้าย. (percents). อ่านอย่างเดียว float.

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

ระยะทางการสะท้อน. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

การจัดตำแหน่งสี่เหลี่ยม. อ่านอย่างเดียว [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**คืนค่า:**
byte

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

ระบุมุมบิดแนวนอน. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

ระบุมุมบิดแนวตั้ง. อ่านอย่างเดียว double.

**คืนค่า:**
double

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

ระบุว่าการสะท้อนควรหมุนไปพร้อมกับรูปทรงหรือไม่หากรูปทรงถูกหมุน. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

ระบุอัตราการสเกลแนวนอน, การสเกลค่าติดลบทำให้เกิดการพลิก. (percents) อ่านอย่างเดียว double.

**คืนค่า:**
double

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

ระบุอัตราการสเกลแนวตั้ง, การสเกลค่าติดลบทำให้เกิดการพลิก. (percents) อ่านอย่างเดียว double.

**คืนค่า:**
double