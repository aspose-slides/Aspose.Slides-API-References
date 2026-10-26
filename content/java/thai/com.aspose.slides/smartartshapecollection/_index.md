---
title: SmartArtShapeCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของรูปร่าง SmartArt
type: docs
url: /th/com.aspose.slides/smartartshapecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
```
public class SmartArtShapeCollection implements ISmartArtShapeCollection
```

แทนชุดของรูปร่าง SmartArt
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | ได้รับจำนวนรายการที่มีอยู่จริงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ได้รับรายการที่ตำแหน่งที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าแสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนส์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่าตัวรากของการซิงโครไนส์ |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### size() {#size--}
```
public final int size()
```

รับจำนวนรายการที่มีอยู่จริงในคอลเลกชัน อ่านอย่างเดียว int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ISmartArtShape get_Item(int index)
```

รับรายการที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [SmartArtShape](../../com.aspose.slides/smartartshape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของรูปร่าง |

**Returns:**
[ISmartArtShape](../../com.aspose.slides/ismartartshape) - รูปร่าง SmartArt
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าแสดงว่าการเข้าถึงคอลเลกชันถูกซิงโครไนส์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่าตัวรากของการซิงโครไนส์ อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iterator()
```

คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - IGenericEnumerator ที่ใช้ในการวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISmartArtShape> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISmartArtShape> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด