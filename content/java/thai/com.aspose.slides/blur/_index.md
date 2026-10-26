---
title: Blur
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: แสดงถึงเอฟเฟกต์เบลอที่ถูกนำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน.
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

แสดงถึงเอฟเฟกต์เบลอที่ถูกนำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน ทั้งช่องสีทั้งหมดรวมถึงอัลฟาก็ได้รับผลกระทบ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | คืนค่า หรือกำหนดค่ารัศมีการเบลอ |
| [setRadius(double value)](#setRadius-double-) | คืนค่า หรือกำหนดค่ารัศมีการเบลอ |
| [getGrow()](#getGrow--) | กำหนดว่าขอบเขตของวัตถุควรขยายตามผลของการเบลอหรือไม่ |
| [setGrow(boolean value)](#setGrow-boolean-) | กำหนดว่าขอบเขตของวัตถุควรขยายตามผลของการเบลอหรือไม่ |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Blur ที่มีการสืบทอดที่ใช้ |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่ากลุ่ม [Blur](../../com.aspose.slides/blur) ที่ระบุเท่ากับ [Blur](../../com.aspose.slides/blur) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

คืนค่า หรือกำหนดค่ารัศมีการเบลอ การอ่าน/เขียน double.

**คืนค่า:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

คืนค่า หรือกำหนดค่ารัศมีการเบลอ การอ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

กำหนดว่าขอบเขตของวัตถุควรขยายตามผลของการเบลอหรือไม่ ค่าจริงหมายถึงขอบเขตถูกขยาย ส่วนค่าผิดหมายถึงไม่ขยาย การอ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

กำหนดว่าขอบเขตของวัตถุควรขยายตามผลของการเบลอหรือไม่ ค่าจริงหมายถึงขอบเขตถูกขยาย ส่วนค่าผิดหมายถึงไม่ขยาย การอ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Blur ที่มีการสืบทอดที่ใช้

**คืนค่า:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - หนึ่ง [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่ากลุ่ม [Blur](../../com.aspose.slides/blur) ที่ระบุเท่ากับ [Blur](../../com.aspose.slides/blur) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Blur](../../com.aspose.slides/blur) ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ

**คืนค่า:**
int - รหัสแฮชสำหรับวัตถุปัจจุบัน.