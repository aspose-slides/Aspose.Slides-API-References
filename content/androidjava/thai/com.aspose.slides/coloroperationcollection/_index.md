---
title: ColorOperationCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของการดำเนินการเปลี่ยนสี.
type: docs
url: /th/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

แสดงถึงคอลเลกชันของการดำเนินการเปลี่ยนสี
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนของการดำเนินการในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | ส่งคืนหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [add(int operation, float parameter)](#add-int-float-) | เพิ่มการดำเนินการใหม่ที่ท้ายคอลเลกชัน |
| [add(int operation)](#add-int-) | เพิ่มการดำเนินการใหม่ที่ท้ายคอลเลกชัน |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | แทรกการดำเนินการใหม่ลงในคอลเลกชัน |
| [insert(int position, int operation)](#insert-int-int-) | แทรกการดำเนินการใหม่ลงในคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบการดำเนินการสีออกจากคอลเลกชัน |
| [clear()](#clear--) | ลบการดำเนินการสีทั้งหมด |
| [iterator()](#iterator--) | ส่งคืนตัววนซ้ำที่ทำการวนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืนตัววนซ้ำของ Java สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการประสาน (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากฐานการประสาน |
| [deepClone()](#deepClone--) | สร้างสำเนาของคอลเลกชัน ColorOperationCollection |
| [cloneT()](#cloneT--) | สำเนาอ็อบเจ็กต์ปัจจุบัน |
### size() {#size--}
```
public final int size()
```


ส่งคืนจำนวนของการดำเนินการในคอลเลกชัน อ่านอย่างเดียว int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```


ส่งคืนหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [ColorOperation](../../com.aspose.slides/coloroperation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```


ส่งคืนหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ อ่าน/เขียน [ColorOperation](../../com.aspose.slides/coloroperation).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |
### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```


เพิ่มการดำเนินการใหม่ที่ท้ายคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```


เพิ่มการดำเนินการใหม่ที่ท้ายคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```


แทรกการดำเนินการใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```


แทรกการดำเนินการใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบการดำเนินการสีออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของการดำเนินการสีที่ต้องการลบ |
### clear() {#clear--}
```
public final void clear()
```


ลบการดำเนินการสีทั้งหมด
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```


ส่งคืนตัววนซ้ำที่ทำการวนผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - IGenericEnumerator ที่ใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```


ส่งคืนตัววนซ้ำของ Java สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันได้รับการประสาน (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ส่งคืนรากฐานการประสาน อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


สร้างสำเนาของคอลเลกชัน ColorOperationCollection

**Returns:**
java.lang.Object - คอลเลกชัน [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) ใหม่
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```


สำเนาอ็อบเจ็กต์ปัจจุบัน

**Returns:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - สำเนา