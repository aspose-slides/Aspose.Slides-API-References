---
title: SoftEdge
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ขอบอ่อนนุ่ม.
type: docs
url: /th/com.aspose.slides/softedge/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

แสดงถึงเอฟเฟกต์ขอบที่อ่อนนุ่ม การขอบของรูปร่างจะเบลอในขณะที่การเติมสีไม่ได้รับผลกระทบ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRadius()](#getRadius--) | ระบุรัศมีของการเบลอที่จะใช้กับขอบ. |
| [setRadius(double value)](#setRadius-double-) | ระบุรัศมีของการเบลอที่จะใช้กับขอบ. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ขอบที่อ่อนนุ่มที่มีผลการสืบทอดที่นำมาใช้แล้ว. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าบรรจุ [SoftEdge](../../com.aspose.slides/softedge) ที่ระบุเป็นเท่ากับ [SoftEdge](../../com.aspose.slides/softedge) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

ระบุรัศมีของการเบลอที่จะใช้กับขอบ. อ่าน/เขียน double.

**คืนค่า:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

ระบุรัศมีของการเบลอที่จะใช้กับขอบ. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ขอบที่อ่อนนุ่มที่มีผลการสืบทอดที่นำมาใช้แล้ว.

**คืนค่า:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - A [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

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

คืนค่า IPresentationComponent พาเรนท์. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**คืนค่า:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวแปร [SoftEdge](../../com.aspose.slides/softedge) ที่ระบุเป็นเท่ากับ [SoftEdge](../../com.aspose.slides/softedge) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากออบเจกต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ.

**คืนค่า:**
int - รหัสแฮชสำหรับออบเจกต์ปัจจุบัน.