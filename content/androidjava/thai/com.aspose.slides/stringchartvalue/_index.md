---
title: StringChartValue
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงค่าข้อความที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของ workbook ที่เกี่ยวข้องกับแผนภูมิ 2 เป็นค่าตรง
type: docs
url: /th/com.aspose.slides/stringchartvalue/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

แสดงค่าข้อความที่สามารถจัดเก็บในเอกสารนำเสนอ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของ workbook ที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าตรง

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCells()](#getAsCells--) | Null value assigning is not allowed. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Null value assigning is not allowed. |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets value as literal string. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets value as literal string. |
| [getData()](#getData--) | Returns or sets Data object. |
| [setData(Object value)](#setData-java.lang.Object-) | Returns or sets Data object. |
| [toString()](#toString--) | Returns string value data. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Sets value from specified cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

ไม่ได้อนุญาตให้กำหนดค่าเป็น null. ค่าที่ส่งกลับจะไม่เป็น null เสมอ. อ่าน/เขียน [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**การคืนค่า:**  
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

ไม่ได้อนุญาตให้กำหนดค่าเป็น null. ค่าที่ส่งกลับจะไม่เป็น null เสมอ. อ่าน/เขียน [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

คืนค่า หรือ กำหนดค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**การคืนค่า:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

คืนค่า หรือ กำหนดค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

คืนค่า หรือ กำหนดค่า Data object. อ่าน/เขียน Object.

**การคืนค่า:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

คืนค่า หรือ กำหนดค่า Data object. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

คืนค่าข้อมูลสตริง. คืนค่า null หาก DataSourceType เป็น false และไม่มีค่า string ที่กำหนด.

**การคืนค่า:**  
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

กำหนดค่า จากเซลล์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

หากคุณสมบัติ DataSourceType มีค่า DataSourceType.Worksheet วิธีนี้จะคืนที่อยู่ของเซลล์ใน workbook ที่เป็นตัวแทนข้อมูลสตริง. มิฉะนั้นจะคืนสตริงว่าง.

**การคืนค่า:**  
java.lang.String