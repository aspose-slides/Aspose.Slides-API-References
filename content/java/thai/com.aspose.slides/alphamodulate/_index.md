---
title: AlphaModulate
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงเอฟเฟกต์ Alpha Modulate.
type: docs
url: /th/com.aspose.slides/alphamodulate/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
อินเทอร์เฟซที่นำไปใช้ทั้งหมด:  
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect  
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Alpha Modulate ค่าตัวอักษร (ความทึบ) ของเอฟเฟกต์จะถูกคูณด้วยเปอร์เซ็นต์คงที่ คอนเทนเนอร์ของเอฟเฟกต์ระบุเอฟเฟกต์ที่มีค่าตัวอักษรเพื่อทำการปรับโมเดล

## Methods

| Method | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

รับข้อมูลเอฟเฟกต์ Alpha Modulate ที่มีการสืบทอดนำไปใช้แล้ว

**Returns:**  
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - หนึ่ง [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

ตรวจสอบว่าที่ระบุ [AlphaModulate](../../com.aspose.slides/alphamodulate) เท่ากับ [AlphaModulate](../../com.aspose.slides/alphamodulate) ปัจจุบันหรือไม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | [AlphaModulate](../../com.aspose.slides/alphamodulate) ที่จะเปรียบเทียบ. |

**Returns:**  
boolean - true if objects are equal; otherwise, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ

**Returns:**  
int - A hash code for the current object.