---
title: VbaModuleCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของโมดูล VBA Project
type: docs
url: /th/com.aspose.slides/vbamodulecollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการนำมาใช้งานทั้งหมด:**  
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)  
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Represents a collection of a VBA Project modules. → แสดงถึงคอลเลกชันของโมดูล VBA Project.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | เพิ่มโมดูลเปล่าใหม่ลงใน VBA Project. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root. |
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

ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | โมดูลที่ต้องการลบจากคอลเลกชัน. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```

เพิ่มโมดูลเปล่าใหม่ลงใน VBA Project.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของโมดูล |

**คืนค่า:**  
[IVbaModule](../../com.aspose.slides/ivbamodule) - โมดูลที่เพิ่ม.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root. อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object