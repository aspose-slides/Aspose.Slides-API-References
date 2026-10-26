---
title: Duotone
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ Duotone.
type: docs
url: /th/com.aspose.slides/duotone/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect  
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Duotone. สำหรับแต่ละพิกเซล, จะรวม Color1 และ Color2 ผ่านการประมาณเชิงเส้นเพื่อกำหนดสีใหม่สำหรับพิกเซลนั้น.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getColor1()](#getColor1--) | คืนค่าสำหรับรูปแบบสีเป้าหมายสำหรับพิกเซลสีเข้ม. |
| [getColor2()](#getColor2--) | คืนค่าสำหรับรูปแบบสีเป้าหมายสำหรับพิกเซลสีอ่อน. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Duotone ที่มีผลโดยใช้การสืบทอด. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่า [Duotone](../../com.aspose.slides/duotone) ที่ระบุนั้นเท่ากับ [Duotone](../../com.aspose.slides/duotone) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทโดยเฉพาะ. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

คืนค่าสำหรับรูปแบบสีเป้าหมายสำหรับพิกเซลสีเข้ม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

คืนค่าสำหรับรูปแบบสีเป้าหมายสำหรับพิกเซลสีอ่อน. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Duotone ที่มีผลโดยใช้การสืบทอด.

**คืนค่า:**  
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - A [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
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

กำหนดว่า [Duotone](../../com.aspose.slides/duotone) ที่ระบุนั้นเท่ากับ [Duotone](../../com.aspose.slides/duotone) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) ที่จะเปรียบเทียบ. |

**คืนค่า:**  
boolean - true หากออบเจ็กต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทโดยเฉพาะ.

**คืนค่า:**  
int - A hash code for the current object.