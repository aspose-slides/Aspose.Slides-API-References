---
title: GrayScale
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ระดับสีเทา.
type: docs
url: /th/com.aspose.slides/grayscale/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

แสดงถึงเอฟเฟกต์ระดับสีเทา (Gray Scale) แปลงค่าสีทั้งหมดของเอฟเฟกต์เป็นเฉดสีเทาตามความสว่างของมัน ค่าความโปร่งใส (alpha) ของเอฟเฟกต์ไม่ได้รับผลกระทบ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Gray Scale ที่มีการสืบทอดถูกนำไปใช้. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่ามี [GrayScale](../../com.aspose.slides/grayscale) ที่ระบุเท่ากับ [GrayScale](../../com.aspose.slides/grayscale) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทใดประเภทหนึ่ง. |
### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Gray Scale ที่มีการสืบทอดถูกนำไปใช้.

**คืนค่า:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่ามี [GrayScale](../../com.aspose.slides/grayscale) ที่ระบุเท่ากับ [GrayScale](../../com.aspose.slides/grayscale) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [GrayScale](../../com.aspose.slides/grayscale) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทใดประเภทหนึ่ง.

**คืนค่า:**
int - รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.