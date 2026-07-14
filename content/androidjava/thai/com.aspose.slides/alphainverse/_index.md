---
title: AlphaInverse
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเอฟเฟกต์ Alpha Inverse.
type: docs
url: /th/com.aspose.slides/alphainverse/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Alpha Inverse ค่า Alpha (ความทึบ) จะถูกกลับโดยการลบจาก 100%.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Alpha Inverse ที่มีผลตามการสืบทอด |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่า [AlphaInverse](../../com.aspose.slides/alphainverse) ที่ระบุเท่ากับ [AlphaInverse](../../com.aspose.slides/alphainverse) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์ Alpha Inverse ที่มีผลตามการสืบทอด

**คืนค่า:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - เป็น [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
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


กำหนดว่า [AlphaInverse](../../com.aspose.slides/alphainverse) ที่ระบุเท่ากับ [AlphaInverse](../../com.aspose.slides/alphainverse) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaInverse](../../com.aspose.slides/alphainverse) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ

**คืนค่า:**
int - รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.