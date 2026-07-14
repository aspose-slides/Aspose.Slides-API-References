---
title: IGlow
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นการแสดงเอฟเฟกต์ Glow ซึ่งเส้นขอบสีที่เบลอจะถูกเพิ่มออกนอกขอบของวัตถุ.
type: docs
url: /th/com.aspose.slides/iglow/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

เป็นการแสดงเอฟเฟกต์ Glow ซึ่งเส้นขอบสีที่เบลอจะถูกเพิ่มออกนอกขอบของวัตถุ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | รัศมี. |
| [setRadius(double value)](#setRadius-double-) | รัศมี. |
| [getColor()](#getColor--) | รูปแบบสี. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

รัศมี. อ่าน/เขียน double.

**คืนค่า:**  
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

รัศมี. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

รูปแบบสี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)