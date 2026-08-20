---
title: DoubleChartValue
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงค่าตัวเลข double ที่สามารถเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2) เป็นค่าลิเทรัล.
type: docs
url: /th/com.aspose.slides/doublechartvalue/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**ทั้งหมดของอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

แสดงค่าตัวเลข double ที่สามารถเก็บในเอกสารพรีเซนเทชัน pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าลิเทรัล.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsCell()](#getAsCell--) | คืนค่า หรือ ตั้งค่า cell ของข้อมูลแผนภูมิ. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | คืนค่า หรือ ตั้งค่า cell ของข้อมูลแผนภูมิ. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือ ตั้งค่าค่าเป็น double ลิเทรัล. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือ ตั้งค่าค่าเป็น double ลิเทรัล. |
| [getData()](#getData--) | คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ Data. |
| [setData(Object value)](#setData-java.lang.Object-) | คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ Data. |
| [toDouble()](#toDouble--) | แปลงเป็น double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


คืนค่า หรือ ตั้งค่า cell ของข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


คืนค่า หรือ ตั้งค่า cell ของข้อมูลแผนภูมิ. อ่าน/เขียน [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


คืนค่า หรือ ตั้งค่าค่าเป็น double ลิเทรัล. อ่าน/เขียน double.

**คืนค่า:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


คืนค่า หรือ ตั้งค่าค่าเป็น double ลิเทรัล. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ Data. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


คืนค่า หรือ ตั้งค่าอ็อบเจ็กต์ Data. อ่าน/เขียน Object.

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
double - คืนค่า LiteralDouble หาก DataSourceType เท่ากับ DoubleLiterals. หาก DataSourceType เท่ากับ Worksheet จะคืนค่าที่แปลงสำเร็จเป็นค่าเซลล์ double, มิฉะนั้นจะคืนค่า NaN.