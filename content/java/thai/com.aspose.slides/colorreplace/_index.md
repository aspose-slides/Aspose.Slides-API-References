---
title: ColorReplace
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเอฟเฟกต์การแทนสี.
type: docs
url: /th/com.aspose.slides/colorreplace/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

แสดงถึงเอฟเฟกต์การแทนสี. สีของเอฟเฟกต์ทั้งหมดจะถูกเปลี่ยนเป็นสีคงที่. ค่าขนาดอัลฟ่าจะไม่เปลี่ยนแปลง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColor()](#getColor--) | ส่งกลับรูปแบบสีที่จะแทนที่สีของทุกพิกเซล. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์การแทนสีที่มีผลพร้อมกับการสืบทอดที่ใช้แล้ว. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [ColorReplace](../../com.aspose.slides/colorreplace) ที่ระบุเท่ากับ [ColorReplace](../../com.aspose.slides/colorreplace) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


ส่งกลับรูปแบบสีที่จะแทนที่สีของทุกพิกเซล. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์การแทนสีที่มีผลพร้อมกับการสืบทอดที่ใช้แล้ว.

**คืนค่า:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - หนึ่ง [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าค่า [ColorReplace](../../com.aspose.slides/colorreplace) ที่ระบุเท่ากับ [ColorReplace](../../com.aspose.slides/colorreplace) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | ค่า [ColorReplace](../../com.aspose.slides/colorreplace) เพื่อเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ.

**คืนค่า:**
int - หนึ่งรหัสแฮชสำหรับวัตถุปัจจุบัน.