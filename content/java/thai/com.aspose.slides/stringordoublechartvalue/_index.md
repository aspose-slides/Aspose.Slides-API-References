---
title: StringOrDoubleChartValue
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงค่า string หรือ double ที่สามารถจัดเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี 1 ในเซล/เซลส์ของ workbook ที่เกี่ยวกับแผนภูมิ 2 ในรูปแบบค่าลิเทรัล
type: docs
url: /th/com.aspose.slides/stringordoublechartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

เป็นตัวแทนของค่า string หรือ double ที่สามารถจัดเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี: 1) ในเซล/เซลส์ของ workbook ที่เกี่ยวกับแผนภูมิ; 2) เป็นค่าลิเทรัล
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCell()](#getAsCell--) | คืนค่า หรือ กำหนด เซลข้อมูลแผนภูมิ. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือ กำหนด เซลข้อมูลแผนภูมิ. |
| [getAsLiteralString()](#getAsLiteralString--) | คืนค่า หรือ กำหนด ค่าเป็นสตริงลิเทรัล. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนค่า หรือ กำหนด ค่าเป็นสตริงลิเทรัล. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือ กำหนด ค่าเป็น double ลิเทรัล. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือ กำหนด ค่าเป็น double ลิเทรัล. |
| [getData()](#getData--) | คืนค่า หรือ กำหนด วัตถุ Data. |
| [setData(Object value)](#setData-java.lang.Object-) | คืนค่า หรือ กำหนด วัตถุ Data. |
| [toDouble()](#toDouble--) | แปลงเป็น double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

คืนค่า หรือ กำหนด เซลข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

คืนค่า หรือ กำหนด เซลข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

คืนค่า หรือ กำหนด ค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

คืนค่า หรือ กำหนด ค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

คืนค่า หรือ กำหนด ค่าเป็น double ลิเทรัล. อ่าน/เขียน double.

**คืนค่า:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

คืนค่า หรือ กำหนด ค่าเป็น double ลิเทรัล. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

คืนค่า หรือ กำหนด วัตถุ Data. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

คืนค่า หรือ กำหนด วัตถุ Data. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

แปลงเป็น double.

**คืนค่า:**
double - Double value.