---
title: ColorChange
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงเอฟเฟกต์การเปลี่ยนสี.
type: docs
url: /th/com.aspose.slides/colorchange/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect  
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

แสดงถึงเอฟเฟกต์การเปลี่ยนสี. อินสแตนซ์ของ FromColor จะถูกแทนที่ด้วยอินสแตนซ์ของ ToColor.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFromColor()](#getFromColor--) | สีที่จะแทนที่. |
| [getToColor()](#getToColor--) | สีที่จะแทนที่ด้วย. |
| [getEffective()](#getEffective--) | ดึงข้อมูลเอฟเฟกต์การเปลี่ยนสีที่มีผลโดยใช้การสืบทอด. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าค่า [ColorChange](../../com.aspose.slides/colorchange) ที่ระบุเท่ากับ [ColorChange](../../com.aspose.slides/colorchange) ปัจจุบันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง. |

### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

สีที่จะแทนที่. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

สีที่จะแทนที่ด้วย. อ่านอย่างเดียว [IColorFormat](../../com.aspose.slides/icolorformat).

**คืนค่า:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

ดึงข้อมูลเอฟเฟกต์การเปลี่ยนสีที่มีผลโดยใช้การสืบทอด.

**คืนค่า:**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).

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

กำหนดว่าค่า [ColorChange](../../com.aspose.slides/colorchange) ที่ระบุเท่ากับ [ColorChange](../../com.aspose.slides/colorchange) ปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | [ColorChange](../../com.aspose.slides/colorchange) ที่จะเปรียบเทียบ. |

**คืนค่า:**  
boolean - true หากอ็อบเจ็กต์เท่ากัน; หากไม่เท่าให้เป็น false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง.

**คืนค่า:**  
int - แฮชโค้ดสำหรับอ็อบเจ็กต์ปัจจุบัน.