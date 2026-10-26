---
title: BiLevel
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นเอฟเฟกต์ระดับสีสองระดับ (สีดำ/ขาว).
type: docs
url: /th/com.aspose.slides/bilevel/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟสที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

เป็นเอฟเฟกต์ระดับสีสองระดับ (สีดำ/ขาว) สีอินพุตที่ความสว่างน้อยกว่าค่าเกณฑ์ที่ระบุจะเปลี่ยนเป็นสีดำ สีอินพุตที่ความสว่างมากกว่าหรือเท่ากับค่าที่ระบุจะตั้งเป็นสีขาว ค่าผลกระทบของอัลฟ่าไม่ได้รับผลจากเอฟเฟกต์นี้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Bi-Level ที่มีการใช้การสืบทอด |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่า [BiLevel](../../com.aspose.slides/bilevel) ที่ระบุเท่ากับ [BiLevel](../../com.aspose.slides/bilevel) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Bi-Level ที่มีการใช้การสืบทอด

**คืนค่า:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่า [BiLevel](../../com.aspose.slides/bilevel) ที่ระบุเท่ากับ [BiLevel](../../com.aspose.slides/bilevel) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [BiLevel](../../com.aspose.slides/bilevel) เพื่อเปรียบเทียบ |

**คืนค่า:**
boolean - true หากอ็อบเจกต์เท่ากัน; มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ

**คืนค่า:**
int - ค่าฮะชสำหรับอ็อบเจกต์ปัจจุบัน.