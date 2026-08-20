---
title: FillFormatCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของรูปแบบการเติมสี.
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

แสดงถึงคอลเลกชันของรูปแบบการเติมสี.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [size()](#size--) | รับจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังแอเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันเป็น synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IFillFormat get_Item(int index)
```

รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - ตัว IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFillFormat> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFillFormat> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### size() {#size--}
```
public final int size()
```

รับจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังแอเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | แอเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในแอเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าคอลเลกชันเป็น synchronized (thread-safe). อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root. อ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object