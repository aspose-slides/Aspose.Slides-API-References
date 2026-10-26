---
title: RowCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แทนคอลเลกชันของแถวตาราง.
type: docs
url: /th/com.aspose.slides/rowcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

แทนคอลเลกชันของแถวตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | รับจำนวนแถวที่จริงๆ แล้วอยู่ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าแถวที่ตำแหน่งที่ระบุ |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ด้านล่างของตาราง |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบแถวที่ตำแหน่งที่ระบุจากตาราง |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |

### size() {#size--}
```
public final int size()
```

รับจำนวนแถวที่จริงๆ แล้วอยู่ในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

คืนค่าแถวที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Row](../../com.aspose.slides/row).

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

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ด้านล่างของตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นเทมเพลต |
| withAttachedRows | boolean | true เพื่อคัดลอกแถวที่แนบกับเทมเพลตด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่เพิ่มเข้าไป

### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแถวใหม่ |
| templ | [IRow](../../com.aspose.slides/irow) | แถวที่ใช้เป็นเทมเพลต |
| withAttachedRows | boolean | true เพื่อคัดลอกแถวที่แนบกับเทมเพลตด้วย |

**คืนค่า:**
com.aspose.slides.IRow[] - แถวที่แทรกเข้าไป

### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

ลบแถวที่ตำแหน่งที่ระบุจากตาราง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstRowIndex | int | ดัชนีของแถวที่ต้องการลบ |
| withAttachedRows | boolean | true เพื่อลบแถวที่แนบทั้งหมดด้วย |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

คืนค่า enumerator ที่วนซ้ำคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - IGenericEnumerator ที่ใช้ในการวนซ้ำคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object