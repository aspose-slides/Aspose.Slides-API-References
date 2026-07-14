---
title: AlphaModulate
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นการแทนเอฟเฟกต์ Alpha Modulate.
type: docs
url: /th/com.aspose.slides/alphamodulate/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

เป็นการแทน Alpha Modulate effect. ค่าความทึบ (opacity) ของ Effect alpha จะถูกคูณด้วยเปอร์เซ็นต์คงที่. ตัวคอนเทนเนอร์ของเอฟเฟกต์ระบุเอฟเฟกต์ที่มีค่าความทึบเพื่อทำการปรับ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | รับข้อมูล Alpha Modulate effect ที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้ |
| [equals(Object obj)](#equals-java.lang.Object-) | ตรวจสอบว่า [AlphaModulate](../../com.aspose.slides/alphamodulate) ที่ระบุเท่ากับ [AlphaModulate](../../com.aspose.slides/alphamodulate) ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

รับข้อมูล Alpha Modulate effect ที่มีประสิทธิภาพพร้อมการสืบทอดที่ใช้

**ผลลัพธ์:**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - หนึ่ง [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่า [AlphaModulate](../../com.aspose.slides/alphamodulate) ที่ระบุเท่ากับ [AlphaModulate](../../com.aspose.slides/alphamodulate) ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaModulate](../../com.aspose.slides/alphamodulate) ที่จะเปรียบเทียบ |

**ผลลัพธ์:**
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง

**ผลลัพธ์:**
int - รหัสแฮชสำหรับวัตถุปัจจุบัน.