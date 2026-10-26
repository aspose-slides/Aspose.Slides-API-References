---
title: DrawingGuidesCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของแนวทางการวาดที่ปรับได้.
type: docs
url: /th/com.aspose.slides/drawingguidescollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

แสดงถึงคอลเลกชันของแนวทางการวาดที่ปรับได้.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนแนวทางการวาดตามดัชนี. |
| [add(byte orientation, float position)](#add-byte-float-) | เพิ่มแนวทางการวาดที่ส่วนท้ายของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบแนวทางการวาดที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนรอบคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getCount()](#getCount--) | คืนจำนวนขององค์ประกอบในคอลเลกชัน. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |

### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


คืนแนวทางการวาดตามดัชนี. อ่านอย่างเดียว [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


เพิ่มแนวทางการวาดที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| orientation | byte | ทิศทางของแนวทางการวาด. |
| position | float | ตำแหน่งของแนวทางการวาดเป็น points. |

**ค่าที่ส่งคืน:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบแนวทางการวาดที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแนวทางการวาดที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบทุกองค์ประกอบจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


คืนค่า enumerator ที่วนรอบคอลเลกชัน.

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - IGenericEnumerator ที่สามารถใช้เพื่อวนรอบคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### getCount() {#getCount--}
```
public final int getCount()
```


คืนจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |