---
title: Blur
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ Blur ที่ใช้กับรูปร่างทั้งหมดรวมถึงการเติมสีของมัน
type: docs
url: /th/com.aspose.slides/blur/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Blur ที่ใช้กับรูปร่างทั้งหมด รวมถึงการเติมสีด้วย ช่องสีทั้งหมดรวมถึงอัลฟาก็ได้รับผลกระทบเช่นกัน.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | คืนค่าหรือกำหนดรัศมีของเบลอร์ |
| [setRadius(double value)](#setRadius-double-) | คืนค่าหรือกำหนดรัศมีของเบลอร์ |
| [getGrow()](#getGrow--) | กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลมาจากการเบลอร์หรือไม่ |
| [setGrow(boolean value)](#setGrow-boolean-) | กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลมาจากการเบลอร์หรือไม่ |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Blur ที่มีการสืบทอดแล้ว |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่า [Blur](../../com.aspose.slides/blur) ที่ระบุนั้นเท่ากับ [Blur](../../com.aspose.slides/blur) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

คืนค่าหรือกำหนดรัศมีของเบลอร์. อ่าน/เขียน double.

**คืนค่า:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

คืนค่าหรือกำหนดรัศมีของเบลอร์. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลมาจากการเบลอร์หรือไม่. True แสดงว่าขอบเขตขยายขึ้นในขณะที่ false แสดงว่าไม่ขยาย. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

กำหนดว่าขอบเขตของวัตถุควรขยายเป็นผลมาจากการเบลอร์หรือไม่. True แสดงว่าขอบเขตขยายขึ้นในขณะที่ false แสดงว่าไม่ขยาย. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Blur ที่มีการสืบทอดแล้ว

**คืนค่า:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - หนึ่ง [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าที่ระบุ [Blur](../../com.aspose.slides/blur) เท่ากับ [Blur](../../com.aspose.slides/blur) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - true ถ้าอ็อบเจกต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ

**คืนค่า:**
int - แฮชโค้ดสำหรับวัตถุปัจจุบัน.