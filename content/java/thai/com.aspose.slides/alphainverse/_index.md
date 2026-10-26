---
title: AlphaInverse
second_title: Aspose.Slides สำหรับ Java การอ้างอิง API
description: เป็นการแทนเอฟเฟกต์ Alpha Inverse.
type: docs
url: /th/com.aspose.slides/alphainverse/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAlphaInverse](../../com.aspose.slides/ialphainverse), com.aspose.slides.IVisualEffect
```
public final class AlphaInverse extends ImageTransformOperation implements IAlphaInverse, IVisualEffect
```

เป็นเอฟเฟกต์ Alpha Inverse ค่าความทึบ (opacity) ของ Alpha จะถูกกลับโดยการลบจาก 100%.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Alpha Inverse ที่มีผลจากการสืบทอด. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่า [AlphaInverse](../../com.aspose.slides/alphainverse) ที่ระบุเท่ากับ [AlphaInverse](../../com.aspose.slides/alphainverse) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ. |
### getEffective() {#getEffective--}
```
public final IAlphaInverseEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์ Alpha Inverse ที่มีผลจากการสืบทอด.

**ผลลัพธ์:**
[IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata) - หนึ่ง [IAlphaInverseEffectiveData](../../com.aspose.slides/ialphainverseeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. อ่านอย่างเดียว long.

**ผลลัพธ์:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


ตรวจสอบว่า [AlphaInverse](../../com.aspose.slides/alphainverse) ที่ระบุเท่ากับ [AlphaInverse](../../com.aspose.slides/alphainverse) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaInverse](../../com.aspose.slides/alphainverse) เพื่อเปรียบเทียบ. |

**ผลลัพธ์:**
boolean - true หากวัตถุเท่ากัน; ไม่เช่นนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ.

**ผลลัพธ์:**
int - หนึ่ง รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.