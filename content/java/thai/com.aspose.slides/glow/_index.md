---
title: Glow
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนเอฟเฟกต์ Glow ซึ่งขอบสีที่เบลอจะถูกเพิ่มไว้ด้านนอกของวัตถุ
type: docs
url: /th/com.aspose.slides/glow/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

แทนเอฟเฟกต์ Glow ซึ่งขอบสีที่เบลอจะถูกเพิ่มไว้ด้านนอกของวัตถุ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | รัศมี. |
| [setRadius(double value)](#setRadius-double-) | รัศมี. |
| [getColor()](#getColor--) | รูปแบบสี. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Glow ที่มีผลจากการสืบทอด. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าระบุ [Glow](../../com.aspose.slides/glow) เทียบเท่ากับ [Glow](../../com.aspose.slides/glow) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


รัศมี. อ่าน/เขียน  double .

**คืนค่า:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


รัศมี. อ่าน/เขียน  double .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


รูปแบบสี. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์ Glow ที่มีผลจากการสืบทอด.

**คืนค่า:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - หนึ่ง [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


คืนค่าพาเรนต์ IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าระบุ [Glow](../../com.aspose.slides/glow) เท่ากับ [Glow](../../com.aspose.slides/glow) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) เพื่อเปรียบเทียบ |

**คืนค่า:**
boolean - true หากอ็อบเจ็กต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ.

**คืนค่า:**
int - แฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน.