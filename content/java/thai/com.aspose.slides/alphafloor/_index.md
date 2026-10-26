---
title: AlphaFloor
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของเอฟเฟกต์ Alpha Floor
type: docs
url: /th/com.aspose.slides/alphafloor/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Alpha Floor ค่า Alpha (ความทึบ) ที่น้อยกว่า 100% จะถูกเปลี่ยนเป็นศูนย์ กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นโปร่งใสเต็มที่
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Alpha Floor ที่ได้จากการสืบทอด |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวแปร [AlphaFloor](../../com.aspose.slides/alphafloor) ที่ระบุเท่ากับ [AlphaFloor](../../com.aspose.slides/alphafloor) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Alpha Floor ที่ได้จากการสืบทอด

**ส่งคืน:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวแปร [AlphaFloor](../../com.aspose.slides/alphafloor) ที่ระบุเท่ากับ [AlphaFloor](../../com.aspose.slides/alphafloor) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) ที่จะเปรียบเทียบ |

**ส่งคืน:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง

**ส่งคืน:**
int - แฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน.