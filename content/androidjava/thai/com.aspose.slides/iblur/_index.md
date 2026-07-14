---
title: IBlur
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ Blur ที่ใช้กับรูปร่างทั้งหมดรวมถึงการเติมสีของมัน
type: docs
url: /th/com.aspose.slides/iblur/
---
**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

แสดงถึงเอฟเฟกต์ Blur ที่ใช้กับรูปร่างทั้งหมดรวมถึงการเติมสีของมัน ทุกช่องสีรวมถึงอัลฟ่าก็ได้รับผลกระทบ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | คืนค่า หรือกำหนดค่ารัศมีของการเบลอ. |
| [setRadius(double value)](#setRadius-double-) | คืนค่า หรือกำหนดค่ารัศมีของการเบลอ. |
| [getGrow()](#getGrow--) | กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลจากการเบลอหรือไม่. |
| [setGrow(boolean value)](#setGrow-boolean-) | กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลจากการเบลอหรือไม่. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

คืนค่า หรือกำหนดค่ารัศมีของการเบลอ. อ่าน/เขียน double.

**คืนค่า:**
double

### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

คืนค่า หรือกำหนดค่ารัศมีของการเบลอ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลจากการเบลอหรือไม่. true แสดงว่าขอบเขตถูกขยาย ส่วน false แสดงว่าไม่ได้ขยาย. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลจากการเบลอหรือไม่. true แสดงว่าขอบเขตถูกขยาย ส่วน false แสดงว่าไม่ได้ขยาย. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |