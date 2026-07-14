---
title: ColorReplace
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของเอฟเฟกต์การแทนที่สี
type: docs
url: /th/com.aspose.slides/colorreplace/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable  
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

แทนที่เอฟเฟกต์การเปลี่ยนสี (Color Replacement) ทั้งหมด สีของเอฟเฟกต์จะถูกเปลี่ยนเป็นสีคงที่ ค่า Alpha จะไม่ได้รับผลกระทบ
## เมธอด

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | คืนค่าแบบฟอร์แมตสีที่จะใช้แทนสีของพิกเซลทุกพิกเซล |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟกต์การแทนที่สีที่มีผลพร้อมการสืบทอดที่นำไปใช้ |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าที่ระบุ [ColorReplace](../../com.aspose.slides/colorreplace) เท่ากับ [ColorReplace](../../com.aspose.slides/colorreplace) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

คืนค่าแบบฟอร์แมตสีที่จะใช้แทนสีของพิกเซลทุกพิกเซล อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

ดึงข้อมูลเอฟเฟกต์การแทนที่สีที่มีผลพร้อมการสืบทอดที่นำไปใช้

**คืนค่า:**  
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน อ่านอย่างเดียว long.

**คืนค่า:**  
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าที่ระบุ [ColorReplace](../../com.aspose.slides/colorreplace) เท่ากับ [ColorReplace](../../com.aspose.slides/colorreplace) ปัจจุบันหรือไม่

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The [ColorReplace](../../com.aspose.slides/colorreplace) to compare. |

**คืนค่า:**  
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง

**คืนค่า:**  
int - A hash code for the current object.