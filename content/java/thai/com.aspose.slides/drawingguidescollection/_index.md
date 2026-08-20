---
title: DrawingGuidesCollection
second_title: Aspose.Slides สำหรับ Java – อ้างอิง API
description: เป็นคอลเลกชันของไกด์การวาดที่ปรับได้.
type: docs
url: /th/com.aspose.slides/drawingguidescollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

เป็นคอลเลกชันของไกด์การวาดที่ปรับได้.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าไกด์การวาดตามดัชนี. |
| [add(byte orientation, float position)](#add-byte-float-) | เพิ่มไกด์การวาดที่ตำสุดของคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบไกด์การวาดที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getCount()](#getCount--) | คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


คืนค่าไกด์การวาดตามดัชนี. อ่านอย่างเดียว [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


เพิ่มไกด์การวาดที่ตำสุดของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| orientation | byte | ทิศทางของไกด์การวาด. |
| position | float | ตำแหน่งของไกด์การวาดในหน่วยจุด. |

**คืนค่า:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบไกด์การวาดที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของไกด์การวาดที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบทุกองค์ประกอบจากคอลเลกชัน.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |