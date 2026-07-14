---
title: StringOrDoubleChartValue
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงค่าแบบสตริงหรือดับเบิลที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2 เป็นค่าลิเทรัล.
type: docs
url: /th/com.aspose.slides/stringordoublechartvalue/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)  
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

แสดงค่าแบบสตริงหรือดับเบิลที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าลิเทรัล.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCell()](#getAsCell--) | คืนค่า หรือกำหนดเซลล์ข้อมูลแผนภูมิ. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือกำหนดเซลล์ข้อมูลแผนภูมิ. |
| [getAsLiteralString()](#getAsLiteralString--) | คืนค่า หรือกำหนดค่าเป็นสตริงลิเทรัล. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนค่า หรือกำหนดค่าเป็นสตริงลิเทรัล. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือกำหนดค่าเป็นดับเบิลลิเทรัล. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือกำหนดค่าเป็นดับเบิลลิเทรัล. |
| [getData()](#getData--) | คืนค่า หรือกำหนดอ็อบเจกต์ Data. |
| [setData(Object value)](#setData-java.lang.Object-) | คืนค่า หรือกำหนดอ็อบเจกต์ Data. |
| [toDouble()](#toDouble--) | แปลงเป็นดับเบิล. |

### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

คืนค่า หรือกำหนดเซลล์ข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**ผลลัพธ์:**  
[IChartDataCell](../../com.aspose.slides/ichartdatacell)

### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

คืนค่า หรือกำหนดเซลล์ข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

คืนค่า หรือกำหนดค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**ผลลัพธ์:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

คืนค่า หรือกำหนดค่าเป็นสตริงลิเทรัล. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

คืนค่า หรือกำหนดค่าเป็นดับเบิลลิเทรัล. อ่าน/เขียน double.

**ผลลัพธ์:**  
double

### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

คืนค่า หรือกำหนดค่าเป็นดับเบิลลิเทรัล. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```

คืนค่า หรือกำหนดอ็อบเจกต์ Data. อ่าน/เขียน Object.

**ผลลัพธ์:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

คืนค่า หรือกำหนดอ็อบเจกต์ Data. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDouble() {#toDouble--}
```
public final double toDouble()
```

แปลงเป็นดับเบิล.

**ผลลัพธ์:**  
double - ค่าดับเบิล.