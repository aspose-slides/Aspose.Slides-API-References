---
title: BiLevel
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ระดับสองสี (ดำ/ขาว).
type: docs
url: /th/com.aspose.slides/bilevel/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

แสดงถึงเอฟเฟกต์ระดับสองสี (ขาว/ดำ) อินพุตสีที่ความสว่างน้อยกว่าค่าขีดจำกัดที่ระบุจะถูกเปลี่ยนเป็นสีดำ อินพุตสีที่ความสว่างมากกว่าหรือเท่ากับค่าที่กำหนดจะถูกตั้งค่าเป็นสีขาว ค่าผลกระทบด้านอัลฟ่าจะไม่ถูกเปลี่ยนแปลงโดยเอฟเฟกต์นี้.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Bi-Level ที่มีการสืบทอดนำมาใช้. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่[BiLevel](../../com.aspose.slides/bilevel) ที่ระบุเท่ากับ [BiLevel](../../com.aspose.slides/bilevel) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่งๆ. |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Bi-Level ที่มีการสืบทอดนำมาใช้.

**ผลลัพธ์:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - หนึ่ง [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่[BiLevel](../../com.aspose.slides/bilevel) ที่ระบุเท่ากับ [BiLevel](../../com.aspose.slides/bilevel) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) ที่จะเปรียบเทียบ. |

**ผลลัพธ์:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่งๆ.

**ผลลัพธ์:**
int - รหัสแฮชสำหรับวัตถุปัจจุบัน.