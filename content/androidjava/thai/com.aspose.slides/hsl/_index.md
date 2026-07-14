---
title: HSL
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงเอฟเฟกต์ Hue/Saturation/Luminance
type: docs
url: /th/com.aspose.slides/hsl/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect  
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

แสดงถึงเอฟเฟกต์ Hue/Saturation/Luminance โดยค่า hue, saturation, และ luminance สามารถปรับได้ตามค่าปัจจุบันของแต่ละตัว  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Hue/Saturation/Luminance effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [HSL](../../com.aspose.slides/hsl) is equal to the current [HSL](../../com.aspose.slides/hsl). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Gets effective Hue/Saturation/Luminance effect data with the inheritance applied.

**คืนค่า:**  
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - A [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determines whether the specified [HSL](../../com.aspose.slides/hsl) is equal to the current [HSL](../../com.aspose.slides/hsl).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | วัตถุ [HSL](../../com.aspose.slides/hsl) เพื่อเปรียบเทียบ. |

**คืนค่า:**  
boolean - true หากวัตถุเท่ากัน; มิฉะนั้น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Serves as a hash function for a particular type.

**คืนค่า:**  
int - รหัสแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน.