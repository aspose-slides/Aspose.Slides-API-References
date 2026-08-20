---
title: TrendlineCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของ Trendline
type: docs
url: /th/com.aspose.slides/trendlinecollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)  
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Represents a collection of Trendline  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [add(int trendlineType)](#add-int-) | เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและคืนค่า. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | ลบค่าที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [getCount()](#getCount--) | ดึงจำนวนขององค์ประกอบที่จริงๆ แล้วอยู่ในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Trendline](../../com.aspose.slides/trendline).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```

เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและคืนค่า.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| trendlineType | int |  |

**ผลลัพธ์:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```

ลบค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```

คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```

ดึงจำนวนขององค์ประกอบที่จริงๆ แล้วอยู่ในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int