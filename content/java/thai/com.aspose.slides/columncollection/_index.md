---
title: ColumnCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/columncollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)  
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

เป็นตัวแทนของคอลเลกชันของคอลัมน์ในตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนคอลัมน์ในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคอลัมน์ที่ตำแหน่งดัชนีที่ระบุ. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกที่ด้านล่างของตาราง. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบประสาน (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการประสาน. |

### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนคอลัมน์ในคอลเลกชัน อ่านอย่างเดียว int.

**ผลลัพธ์:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

คืนค่าคอลัมน์ที่ตำแหน่งดัชนีที่ระบุ อ่านอย่างเดียว [Column](../../com.aspose.slides/column).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IColumn](../../com.aspose.slides/icolumn)

### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

สร้างสำเนาของแถวแม่แบบที่ระบุและแทรกที่ด้านล่างของตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับแถวแม่แบบด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่เพิ่ม.

### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

สร้างสำเนาของคอลัมน์แม่แบบที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์ใหม่. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นแม่แบบ. |
| withAttachedColumns | boolean | True เพื่อคัดลอกคอลัมน์ทั้งหมดที่แนบกับคอลัมน์แม่แบบด้วย. |

**ผลลัพธ์:**
com.aspose.slides.IColumn[] - คอลัมน์ที่แทรก.

### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| firstColumnIndex | int | ดัชนีของคอลัมน์ที่จะลบ. |
| withAttachedRows | boolean | True เพื่อทำการลบคอลัมน์ที่แนบด้วยทั้งหมด. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้เป็นแบบประสาน (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการประสาน. อ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object