---
title: FillFormatCollection
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของสไตล์การเติมสี.
type: docs
url: /th/com.aspose.slides/fillformatcollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IFillFormatCollection](../../com.aspose.slides/ifillformatcollection)  
```
public final class FillFormatCollection extends DomObject<FormatScheme> implements IFillFormatCollection
```

เป็นตัวแทนของคอลเลกชันของสไตล์การเติมสี.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่กำหนด. |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืน root การซิงโครไนซ์. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่กำหนด. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งกลับ:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**ค่าที่ส่งกลับ:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ค่าที่ส่งกลับ:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ค่าที่ส่งกลับ:**  
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ตำแหน่งเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**ค่าที่ส่งกลับ:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืน root การซิงโครไนซ์. อ่านอย่างเดียว Object.

**ค่าที่ส่งกลับ:**  
java.lang.Object