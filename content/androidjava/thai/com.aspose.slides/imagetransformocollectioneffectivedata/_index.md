---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: อ็อบเจกต์ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของคอลเลกชันแบบอ่านอย่างเดียวของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ
type: docs
url: /th/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำไว้ทั้งหมด:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

อ็อบเจ็กต์ที่ไม่เปลี่ยนแปลงซึ่งเป็นตัวแทนของคอลเลกชันแบบอ่านอย่างเดียวของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ

--------------------

ชื่อ IImageTransformOperationCollectionEffectiveData ถูกตัดให้สั้นเป็น IImageTransformOCollectionEffectiveData เนื่องจากความยาวของชื่อ COM ไม่สามารถมากกว่า 39 ตัวอักษร
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนของเอฟเฟกต์ภาพในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบตามดัชนี |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าวัตถุที่ระบุเท่ากับวัตถุปัจจุบันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสำหรับการใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกรายการทั้งหมดจากคอลเลกชันลงในอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนของเอฟเฟกต์ภาพในคอลเลกชัน. แบบอ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

ส่งคืนองค์ประกอบตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**คืนค่า:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - The [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าวัตถุที่ระบุเท่ากับวัตถุปัจจุบันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | วัตถุเพื่อเปรียบเทียบกับวัตถุปัจจุบัน |

**คืนค่า:**
boolean - true หากวัตถุที่ระบุเท่ากับวัตถุปัจจุบัน; มิฉะนั้น false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสำหรับการใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช

**คืนค่า:**
int - รหัสแฮชสำหรับวัตถุปัจจุบัน
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันลงในอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่ต้องการเติม |
| index | int | ตำแหน่งเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). แบบอ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์. แบบอ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object