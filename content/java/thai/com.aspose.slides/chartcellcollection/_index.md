---
title: ChartCellCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคอลเลกชันของเซลล์ที่มีข้อมูล.
type: docs
url: /th/com.aspose.slides/chartcellcollection/
---
**สืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IChartCellCollection](../../com.aspose.slides/ichartcellcollection), com.aspose.slides.IDOMObject  
```
public class ChartCellCollection implements IChartCellCollection, IDOMObject
```

แสดงถึงคอลเลกชันของเซลล์ที่มีข้อมูล  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | คืนค่าที่อยู่ของชุดเซลล์ในเวิร์กบุ๊ก |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | สตริงการต่อจากค่าข้อความของเซลล์ทั้งหมด |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเซลล์ (IChartDataCell) ตามดัชนี |
| [add(IChartDataCell cell)](#add-com.aspose.slides.IChartDataCell-) | เพิ่มเซลล์ใหม่เข้าในคอลเลกชัน |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [ChartDataCell](../../com.aspose.slides/chartdatacell) จากค่าที่ระบุและเพิ่มเข้าในคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบเซลล์ออกจากคอลเลกชันตามดัชนี |
| [getCount()](#getCount--) | รับจำนวนเซลล์ในคอลเลกชัน |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getCellsAddress() {#getCellsAddress--}
```
public final String getCellsAddress()
```

คืนค่าที่อยู่ของชุดเซลล์ในเวิร์กบุ๊ก

**คืนค่า:**  
java.lang.String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public final String getConcatenatedValuesFromCells()
```

สตริงการต่อจากค่าข้อความของเซลล์ทั้งหมด

**คืนค่า:**  
java.lang.String
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataCell get_Item(int index)
```

คืนค่าเซลล์ (IChartDataCell) ตามดัชนี

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเซลล์ |

**คืนค่า:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - เซลล์ที่มีข้อมูล
### add(IChartDataCell cell) {#add-com.aspose.slides.IChartDataCell-}
```
public final void add(IChartDataCell cell)
```

เพิ่มเซลล์ใหม่เข้าในคอลเลกชัน

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ใหม่ที่จะเพิ่ม |
### add(Object value) {#add-java.lang.Object-}
```
public final void add(Object value)
```

สร้าง [ChartDataCell](../../com.aspose.slides/chartdatacell) จากค่าที่ระบุและเพิ่มเข้าในคอลเลกชัน

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่า |

--------------------

เมธอดนี้เพิ่มแผ่นงานด้วยชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงในนั้น หากคุณใช้ [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของ Cell โปรดแน่ใจว่าไม่ใช้แผ่นงานนี้ จำนวนค่าสูงสุดที่สามารถเพิ่มได้ด้วยเมธอดนี้ต้องไม่เกิน 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบเซลล์ออกจากคอลเลกชันตามดัชนี

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเซลล์ที่ต้องการลบ |
### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนเซลล์ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataCell> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataCell> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**  
com.aspose.slides.IDOMObject