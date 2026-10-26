---
title: Duotone
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงเอฟเฟ็กต์ Duotone.
type: docs
url: /th/com.aspose.slides/duotone/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

แสดงถึงเอฟเฟ็กต์ Duotone. สำหรับแต่ละพิกเซล จะผสม Color1 และ Color2 ผ่านการอินเตอร์พอเลชันเชิงเส้นเพื่อกำหนดสีใหม่สำหรับพิกเซลนั้น.

## วิธีการ

| วิธี | รายละเอียด |
| --- | --- |
| [getColor1()](#getColor1--) | คืนรูปแบบสีเป้าหมายสำหรับพิกเซลสีเข้ม |
| [getColor2()](#getColor2--) | คืนรูปแบบสีเป้าหมายสำหรับพิกเซลสีอ่อน |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟ็กต์ Duotone ที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้งาน |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวแปร [Duotone](../../com.aspose.slides/duotone) ที่ระบุเท่ากับ [Duotone](../../com.aspose.slides/duotone) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่ระบุ |

### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```

คืนรูปแบบสีเป้าหมายสำหรับพิกเซลสีเข้ม. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```

คืนรูปแบบสีเป้าหมายสำหรับพิกเซลสีอ่อน. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```

รับข้อมูลเอฟเฟ็กต์ Duotone ที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้งาน

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

กำหนดว่าตัวแปร [Duotone](../../com.aspose.slides/duotone) ที่ระบุเท่ากับ [Duotone](../../com.aspose.slides/duotone) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Duotone](../../com.aspose.slides/duotone) ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - true ถ้าอ็อบเจ็กต์เท่ากัน; มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่ระบุ

**คืนค่า:**
int - รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.