---
title: ColorOperationCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคอลเลกชันของการดำเนินการแปลงสี.
type: docs
url: /th/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**  
การสืบทอด:

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Represents a collection of color transform operations.  
แสดงชุดของการดำเนินการแปลงสี.

## Methods  
## เมธอด

| Method | Description |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนการดำเนินการในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ |
| [add(int operation, float parameter)](#add-int-float-) | เพิ่มการดำเนินการใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [add(int operation)](#add-int-) | เพิ่มการดำเนินการใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | แทรกการดำเนินการใหม่ลงในคอลเลกชัน |
| [insert(int position, int operation)](#insert-int-int-) | แทรกการดำเนินการใหม่ลงในคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบการดำเนินการสีจากคอลเลกชัน |
| [clear()](#clear--) | ลบการดำเนินการสีทั้งหมด |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |
| [deepClone()](#deepClone--) | สร้างสำเนาของคอลเลกชัน ColorOperationCollection |
| [cloneT()](#cloneT--) | ทำการโคลนอ็อบเจกต์ปัจจุบัน |

### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนการดำเนินการในคอลเลกชัน. **อ่านอย่างเดียว** int.

**คืนค่า:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ. **อ่าน/เขียน** [ColorOperation](../../com.aspose.slides/coloroperation).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

คืนค่าหรือกำหนดการดำเนินการที่ตำแหน่งที่ระบุ. **อ่าน/เขียน** [ColorOperation](../../com.aspose.slides/coloroperation).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

เพิ่มการดำเนินการใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

เพิ่มการดำเนินการใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่เพิ่ม

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

แทรกการดำเนินการใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์ของการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

แทรกการดำเนินการใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | ดัชนีที่การดำเนินการจะถูกแทรก |
| operation | int | ประเภทการดำเนินการ |

**คืนค่า:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - การดำเนินการที่แทรก

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบการดำเนินการสีจากคอลเลกชัน.

**พารามิเตอร์:**
| Parameter | Type | Description |
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

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันได้รับการซิงโครไนซ์ (thread-safe). **อ่านอย่างเดียว** boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์. **อ่านอย่างเดียว** Object.

**คืนค่า:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

สร้างสำเนาของคอลเลกชัน ColorOperationCollection

**คืนค่า:**
java.lang.Object - คอลเลกชัน [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) ใหม่

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

ทำการโคลนอ็อบเจกต์ปัจจุบัน

**คืนค่า:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - โคลน