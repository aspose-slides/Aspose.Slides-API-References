---
title: RowCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันแถวตาราง.
type: docs
url: /th/com.aspose.slides/rowcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

เป็นตัวแทนของคอลเลกชันแถวตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนแถวที่อยู่จริงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าแถวที่ตำแหน่ง index ที่ระบุ |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ส่วนล่างของตาราง |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็น synchronized (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |

### size() {#size--}
```
public final int size()
```

รับจำนวนแถวที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

คืนค่าแถวที่ตำแหน่ง index ที่ระบุ. อ่านอย่างเดียว [Row](../../com.aspose.slides/row).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IRow](../../com.aspose.slides/irow)

### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ส่วนล่างของตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Row ที่ใช้เป็นเทมเพลต |
| withAttachedRows | boolean | True เพื่อคัดลอกแถวที่แนบกับแถวเทมเพลตทั้งหมดด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่เพิ่ม

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถวใหม่ |
| templ | [IRow](../../com.aspose.slides/irow) | Row ที่ใช้เป็นเทมเพลต |
| withAttachedRows | boolean | True เพื่อคัดลอกแถวที่แนบกับแถวเทมเพลตทั้งหมดด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่แทรก

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

ลบแถวที่ตำแหน่งที่ระบุออกจากตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstRowIndex | int | ดัชนีของแถวที่ต้องการลบ |
| withAttachedRows | boolean | True เพื่อลบแถวที่แนบทั้งหมดด้วย |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็น synchronized (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object