---
title: AlphaFloor
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเอฟเฟกต์ Alpha Floor.
type: docs
url: /th/com.aspose.slides/alphafloor/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Alpha Floor ค่าความทึบ (opacity) ที่ต่ำกว่า 100% จะถูกเปลี่ยนเป็นศูนย์ กล่าวคือ สิ่งที่มีความโปร่งใสบางส่วนจะกลายเป็นโปร่งใสเต็มที่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟกต์ Alpha Floor ที่มีผลจากการสืบทอดที่ใช้. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [AlphaFloor](../../com.aspose.slides/alphafloor) ที่ระบุเท่ากับ [AlphaFloor](../../com.aspose.slides/alphafloor) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

ดึงข้อมูลเอฟเฟกต์ Alpha Floor ที่มีผลจากการสืบทอดที่ใช้.

**คืนค่า:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - เป็น [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าค่า [AlphaFloor](../../com.aspose.slides/alphafloor) ที่ระบุเท่ากับ [AlphaFloor](../../com.aspose.slides/alphafloor) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaFloor](../../com.aspose.slides/alphafloor) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากออบเจกต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด.

**คืนค่า:**
int - รหัสแฮชสำหรับออบเจกต์ปัจจุบัน.