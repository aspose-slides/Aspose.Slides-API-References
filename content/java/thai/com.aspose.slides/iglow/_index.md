---
title: IGlow
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงเอฟเฟกต์ Glow ที่เพิ่มขอบสีเบลอรอบๆ วัตถุ
type: docs
url: /th/com.aspose.slides/iglow/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

แสดงเอฟเฟกต์ Glow ที่เพิ่มขอบสีเบลอรอบๆ วัตถุ

## เมธอด

| เมธอด | รายละเอียด |
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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

รูปแบบสี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)