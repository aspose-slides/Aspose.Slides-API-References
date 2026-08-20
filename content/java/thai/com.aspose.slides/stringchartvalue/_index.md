---
title: StringChartValue
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงค่าข้อความที่สามารถจัดเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของสมุดงานที่เกี่ยวข้องกับแชาร์ต 2 เป็นค่าลิเทอรัล.
type: docs
url: /th/com.aspose.slides/stringchartvalue/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

แสดงค่าข้อความที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของสมุดงานที่เกี่ยวข้องกับแชาร์ต; 2) เป็นค่าลิเทอรัล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCells()](#getAsCells--) | ไม่อนุญาตให้กำหนดค่า null. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | ไม่อนุญาตให้กำหนดค่า null. |
| [getAsLiteralString()](#getAsLiteralString--) | คืนหรือตั้งค่าข้อมูลเป็นสตริงลิเทอรัล. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนหรือตั้งค่าข้อมูลเป็นสตริงลิเทอรัล. |
| [getData()](#getData--) | คืนหรือตั้งค่าอ็อบเจ็กต์ Data. |
| [setData(Object value)](#setData-java.lang.Object-) | คืนหรือตั้งค่าอ็อบเจ็กต์ Data. |
| [toString()](#toString--) | คืนข้อมูลค่าข้อความสตริง. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | ตั้งค่าจากเซลล์ที่ระบุ. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | หากคุณสมบัติ DataSourceType เป็น DataSourceType.Worksheet วิธีนี้จะคืนที่อยู่ของเซลล์ในสมุดงานที่แสดงข้อมูลสตริง. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

ไม่อนุญาตให้กำหนดค่า null. ค่าที่คืนจะไม่มีค่า null เสมอ. อ่าน/เขียน [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**คืนค่า:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

ไม่อนุญาตให้กำหนดค่า null. ค่าที่คืนจะไม่มีค่า null เสมอ. อ่าน/เขียน [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

คืนหรือตั้งค่าข้อมูลเป็นสตริงลิเทอรัล. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

คืนหรือตั้งค่าข้อมูลเป็นสตริงลิเทอรัล. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

คืนหรือตั้งค่าอ็อบเจ็กต์ Data. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

คืนหรือตั้งค่าอ็อบเจ็กต์ Data. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

คืนข้อมูลค่าข้อความสตริง. คืนค่า null หาก DataSourceType เป็น false และไม่มีการกำหนดค่าข้อความสตริง.

**คืนค่า:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

ตั้งค่าจากเซลล์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

หากคุณสมบัติ DataSourceType เป็น DataSourceType.Worksheet วิธีนี้จะคืนที่อยู่ของเซลล์ในสมุดงานที่แสดงข้อมูลสตริง. มิฉะนั้นจะคืนสตริงว่าง.

**คืนค่า:**
java.lang.String