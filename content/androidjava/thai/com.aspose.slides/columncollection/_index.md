---
title: ColumnCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคอลเลกชันของคอลัมน์ในตาราง.
type: docs
url: /th/com.aspose.slides/columncollection/
---
**Inheritance:**  
การสืบทอด: java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)  
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

แสดงคอลเลกชันของคอลัมน์ในตาราง.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | คืนจำนวนคอลัมน์ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคอลัมน์ที่ตำแหน่งที่ระบุ |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ด้านล่างของตาราง |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | สร้างสำเนาของคอลัมน์เทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |
### size() {#size--}
```
public final int size()
```

คืนจำนวนคอลัมน์ในคอลเลกชัน. อ่านอย่างเดียว int.

**Returns:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

คืนค่าคอลัมน์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Column](../../com.aspose.slides/column).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**  
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

สร้างสำเนาของแถวเทมเพลตที่ระบุและแทรกที่ด้านล่างของตาราง

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นเทมเพลต |
| withAttachedColumns | boolean | true หากต้องการคัดลอกคอลัมน์ที่แนบกับแถวเทมเพลตด้วย |

**Returns:**  
com.aspose.slides.IColumn[] - คอลัมน์ที่เพิ่ม
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

สร้างสำเนาของคอลัมน์เทมเพลตที่ระบุและแทรกที่ตำแหน่งที่ระบุในตาราง

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของคอลัมน์ใหม่ |
| templ | [IColumn](../../com.aspose.slides/icolumn) | คอลัมน์ที่ใช้เป็นเทมเพลต |
| withAttachedColumns | boolean | true หากต้องการคัดลอกคอลัมน์ที่แนบกับคอลัมน์เทมเพลตด้วย |

**Returns:**  
com.aspose.slides.IColumn[] - คอลัมน์ที่แทรก
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

ลบคอลัมน์ที่ตำแหน่งที่ระบุจากตาราง

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | ดัชนีของคอลัมน์ที่จะลบ |
| withAttachedRows | boolean | true หากต้องการลบคอลัมน์ที่แนบทั้งหมดด้วย |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - IGenericEnumerator ที่ใช้เพื่อวนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (thread-safe). อ่านอย่างเดียว boolean.

**Returns:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**Returns:**  
java.lang.Object