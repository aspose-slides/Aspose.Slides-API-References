---
title: AlphaBiLevel
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงเอฟเฟกต์ Alpha Bi-Level
type: docs
url: /th/com.aspose.slides/alphabilevel/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

แสดงเอฟเฟกต์ Alpha Bi-Level ค่าความทึบ (Opacity) ที่น้อยกว่าค่าที่กำหนดจะถูกเปลี่ยนเป็น 0 (โปร่งใสเต็มที่) และค่าความทึบที่มากกว่าหรือเท่ากับค่าที่กำหนดจะถูกเปลี่ยนเป็น 100% (ทึบเต็มที่)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThreshold()](#getThreshold--) | ส่งคืนค่าเกณฑ์ของเอฟเฟกต์ |
| [setThreshold(float value)](#setThreshold-float-) | ส่งคืนค่าเกณฑ์ของเอฟเฟกต์ |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Alpha Bi-Level ที่มีการสืบทอดใช้งาน |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่ระบุเท่ากับ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


ส่งคืนค่าเกณฑ์ของเอฟเฟกต์ อ่าน/เขียน float.

**คืนค่า:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


ส่งคืนค่าเกณฑ์ของเอฟเฟกต์ อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์ Alpha Bi-Level ที่มีการสืบทอดใช้งาน

**คืนค่า:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - A [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าค่า [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่ระบุเท่ากับ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่จะเปรียบเทียบ |

**คืนค่า:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด

**คืนค่า:**
int - A hash code for the current object.