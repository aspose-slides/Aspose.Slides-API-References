---
title: TrendlineCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของ Trendline
type: docs
url: /th/com.aspose.slides/trendlinecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

แสดงถึงคอลเลกชันของ Trendline
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(int trendlineType)](#add-int-) | Adds the new Trendline at the end of a collection and return it. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Removes the specified value. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [getCount()](#getCount--) | Gets the number of elements actually contained in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


รับองค์ประกอบที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Trendline](../../com.aspose.slides/trendline).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


เพิ่ม Trendline ใหม่ที่ส่วนท้ายของคอลเลกชันและคืนค่าให้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| trendlineType | int |  |

**คืนค่า:**
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


คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - IGenericEnumerator ที่สามารถใช้ในการวนผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### getCount() {#getCount--}
```
public final int getCount()
```


รับจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int