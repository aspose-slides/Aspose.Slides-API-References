---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides สำหรับ Java API อ้างอิง
description: อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของคอลเลกชันแบบอ่านอย่างเดียวของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ.
type: docs
url: /th/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของคอลเลกชันแบบอ่านอย่างเดียวของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ

--------------------

ชื่อ IImageTransformOperationCollectionEffectiveData ถูกตัดให้สั้นเป็น IImageTransformOCollectionEffectiveData เนื่องจากความยาวของชื่อ COM ต้องไม่เกิน 39 ตัวอักษร
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนเอฟเฟกต์ภาพในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าอิลเมนต์ตามดัชนี |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าอ็อบเจ็กต์ที่ระบุเท่ากับอ็อบเจ็กต์ปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะที่เหมาะสำหรับใช้ในอัลกอริธึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า iterator ของ Java สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกอิลเมนต์ทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


คืนค่าจำนวนเอฟเฟกต์ภาพในคอลเลกชัน เป็น int แบบอ่านอย่างเดียว

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


คืนค่าอิลเมนต์ตามดัชนี

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของอิลเมนต์ |

**คืนค่า:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) อ็อบเจ็กต์
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าอ็อบเจ็กต์ที่ระบุเท่ากับอ็อบเจ็กต์ปัจจุบันหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | อ็อบเจ็กต์ที่เปรียบเทียบกับอ็อบเจ็กต์ปัจจุบัน |

**คืนค่า:**
boolean - true หากอ็อบเจ็กต์ที่ระบุเท่ากับอ็อบเจ็กต์ปัจจุบัน; มิฉะนั้น false
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะที่เหมาะสำหรับใช้ในอัลกอริธึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช

**คืนค่า:**
int - โค้ดแฮชสำหรับอ็อบเจ็กต์ปัจจุบัน
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


คืนค่า enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


คืนค่า iterator ของ Java สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกอิลเมนต์ทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่จะเติม |
| index | int | ตำแหน่งเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ เป็น boolean แบบอ่านอย่างเดียว

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่า synchronization root เป็น Object แบบอ่านอย่างเดียว

**คืนค่า:**
java.lang.Object