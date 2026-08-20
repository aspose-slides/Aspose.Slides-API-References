---
title: AlphaBiLevel
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ Alpha Bi-Level.
type: docs
url: /th/com.aspose.slides/alphabilevel/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Interfaces ที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Alpha Bi-Level. ค่า Alpha (Opacity) ที่น้อยกว่าขีดจำกัดจะถูกเปลี่ยนเป็น 0 (โปร่งใสเต็ม) และค่า Alpha ที่มากกว่าหรือเท่ากับขีดจำกัดจะถูกเปลี่ยนเป็น 100% (ทึบเต็ม).
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getThreshold()](#getThreshold--) | คืนค่าเกณฑ์ของเอฟเฟกต์. |
| [setThreshold(float value)](#setThreshold-float-) | คืนค่าเกณฑ์ของเอฟเฟกต์. |
| [getEffective()](#getEffective--) | รับข้อมูลเอฟเฟกต์ Alpha Bi-Level ที่มีการสืบทอด. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่ระบุเท่ากับ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```


คืนค่าเกณฑ์ของเอฟเฟกต์. อ่าน/เขียน float.

**คืนค่า:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```


คืนค่าเกณฑ์ของเอฟเฟกต์. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```


รับข้อมูลเอฟเฟกต์ Alpha Bi-Level ที่มีการสืบทอด.

**คืนค่า:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - เป็น [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าค่า [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่ระบุเท่ากับ [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | ค่า [AlphaBiLevel](../../com.aspose.slides/alphabilevel) ที่จะเปรียบเทียบ. |

**คืนค่า:**
boolean - true หากอ็อบเจ็กต์เท่ากัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ.

**คืนค่า:**
int - แฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน.