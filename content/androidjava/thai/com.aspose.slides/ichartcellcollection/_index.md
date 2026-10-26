---
title: IChartCellCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นการแทนคอลเลกชันของเซลล์ที่มีข้อมูล.
type: docs
url: /th/com.aspose.slides/ichartcellcollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

เป็นการแทนชุดของเซลล์ที่มีข้อมูล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | ส่งคืนที่อยู่ของชุดเซลล์ใน workbook. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | สตริงที่ต่อเนื่องจากค่าสตริงของเซลล์ทั้งหมด. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนเซลล์ (IChartDataCell) ตามดัชนี. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | เพิ่มเซลล์ใหม่ลงในคอลเลกชัน. |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [IChartDataCell](../../com.aspose.slides/ichartdatacell) จากค่าที่ระบุและเพิ่มเข้าคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเซลล์ออกจากคอลเลกชันตามดัชนี. |
| [getCount()](#getCount--) | รับจำนวนเซลล์ในคอลเลกชัน. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```

ส่งคืนที่อยู่ของชุดเซลล์ใน workbook.

**คืนค่า:**
java.lang.String - ที่อยู่ของชุดเซลล์ใน workbook String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```

สตริงที่ต่อเนื่องจากค่าสตริงของเซลล์ทั้งหมด.

**คืนค่า:**
java.lang.String - สตริงผลลัพธ์ String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```

ส่งคืนเซลล์ (IChartDataCell) ตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเซลล์. |

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - เซลล์ที่มีข้อมูล.
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract void add(IChartDataCell chartDataCell)
```

เพิ่มเซลล์ใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ใหม่ที่จะเพิ่ม. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```

สร้าง [IChartDataCell](../../com.aspose.slides/ichartdatacell) จากค่าที่ระบุและเพิ่มเข้าคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่า. |

--------------------

วิธีนี้เพิ่ม worksheet ชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดที่นั่น หากคุณใช้ [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าเซลล์ โปรดแน่ใจว่าคุณไม่ได้ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มโดยวิธีนี้ต้องไม่เกิน 16711680 |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบเซลล์ออกจากคอลเลกชันตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเซลล์ที่จะลบ. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนเซลล์ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int