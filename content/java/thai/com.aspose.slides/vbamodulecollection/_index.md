---
title: VbaModuleCollection
second_title: Aspose.Slides สำหรับ Java - เอกสารอ้างอิง API
description: เป็นคอลเลกชันของโมดูล VBA Project.
type: docs
url: /th/com.aspose.slides/vbamodulecollection/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

แสดงถึงคอลเลกชันของโมดูล VBA Project.
## เมธอด

| Method | Description |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์เฉพาะจากคอลเลกชัน. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | เพิ่มโมดูลว่างใหม่ไปยัง VBA Project. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบประสาน (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากฐานการประสาน. |
### size() {#size--}
```
public final int size()
```


รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


ลบการเกิดขึ้นครั้งแรกของอ็อบเจ็กต์เฉพาะจากคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | โมดูลที่จะลบออกจากคอลเลกชัน. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


เพิ่มโมดูลว่างใหม่ไปยัง VBA Project.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | ชื่อของโมดูล |

**คืนค่า:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - โมดูลที่เพิ่มแล้ว.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันเป็นแบบประสาน (thread-safe). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากฐานการประสาน. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object