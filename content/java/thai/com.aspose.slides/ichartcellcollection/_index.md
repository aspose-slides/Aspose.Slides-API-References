---
title: IChartCellCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของเซลล์ที่มีข้อมูล.
type: docs
url: /th/com.aspose.slides/ichartcellcollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IChartCellCollection extends System.Collections.Generic.IGenericEnumerable<IChartDataCell>
```

เป็นการแสดงถึงคอลเลกชันของเซลล์พร้อมข้อมูล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCellsAddress()](#getCellsAddress--) | คืนค่าที่อยู่ของชุดเซลล์ในสมุดงาน. |
| [getConcatenatedValuesFromCells()](#getConcatenatedValuesFromCells--) | สตริงการเชื่อมต่อจากค่าข้อความของเซลล์ทั้งหมด. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าเซลล์ (IChartDataCell) ตามดัชนี. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | เพิ่มเซลล์ใหม่เข้าคอลเลกชัน. |
| [add(Object value)](#add-java.lang.Object-) | สร้าง [IChartDataCell](../../com.aspose.slides/ichartdatacell) จากค่าที่ระบุและเพิ่มเข้าไปในคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเซลล์ออกจากคอลเลกชันตามดัชนี. |
| [getCount()](#getCount--) | รับจำนวนเซลล์ในคอลเลกชัน. |
### getCellsAddress() {#getCellsAddress--}
```
public abstract String getCellsAddress()
```


คืนค่าที่อยู่ของชุดเซลล์ในสมุดงาน.

**คืนค่า:**
java.lang.String - ที่อยู่ของชุดเซลล์ในสมุดงาน String
### getConcatenatedValuesFromCells() {#getConcatenatedValuesFromCells--}
```
public abstract String getConcatenatedValuesFromCells()
```


สตริงการเชื่อมต่อจากค่าข้อความของเซลล์ทั้งหมด.

**คืนค่า:**
java.lang.String - สตริงผลลัพธ์ String
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int index)
```


คืนค่าเซลล์ (IChartDataCell) ตามดัชนี.

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


เพิ่มเซลล์ใหม่เข้าคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ใหม่ที่จะเพิ่ม. |

### add(Object value) {#add-java.lang.Object-}
```
public abstract void add(Object value)
```


สร้าง [IChartDataCell](../../com.aspose.slides/ichartdatacell) จากค่าที่ระบุและเพิ่มเข้าไปในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object | ค่าที่ระบุ.

--------------------

วิธีการนี้เพิ่ม worksheet ที่มีชื่อ AUTO_DATA และเพิ่มค่าทั้งหมดลงที่นั่น หากคุณใช้ [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) เพื่อเพิ่มหรือแก้ไขค่าของ Cell โปรดตรวจสอบว่าคุณไม่ได้ใช้ worksheet นี้ จำนวนค่าสูงสุดที่เพิ่มโดยใช้วิธีการนี้ต้องไม่เกิน 16711680 |

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