---
title: GrayScale
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของเอฟเฟกต์ Gray Scale.
type: docs
url: /th/com.aspose.slides/grayscale/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**ส่วนต่อประสานที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Gray Scale. แปลงค่าสีของเอฟเฟกต์ทั้งหมดให้เป็นเฉดสีเทา ตามความสว่างของมัน. ค่าอัลฟา (ความทึบ) ของเอฟเฟกต์ไม่ได้รับผลกระทบ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟกต์ Gray Scale ที่มีผลจากการสืบทอด |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่า [GrayScale](../../com.aspose.slides/grayscale) ที่ระบุเท่ากับ [GrayScale](../../com.aspose.slides/grayscale) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

ดึงข้อมูลเอฟเฟกต์ Gray Scale ที่มีผลจากการสืบทอด

**คืนค่า:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - หนึ่ง [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่า [GrayScale](../../com.aspose.slides/grayscale) ที่ระบุเท่ากับ [GrayScale](../../com.aspose.slides/grayscale) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [GrayScale](../../com.aspose.slides/grayscale) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากอ็อบเจ็กต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง

**คืนค่า:**
int - แฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน.