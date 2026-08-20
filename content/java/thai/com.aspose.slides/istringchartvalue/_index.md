---
title: IStringChartValue
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงค่าสตริงที่สามารถจัดเก็บในเอกสารพรีเซนต์ pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2 เป็นค่าตัวอักษรโดยตรง.
type: docs
url: /th/com.aspose.slides/istringchartvalue/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

แสดงค่าสตริงที่สามารถจัดเก็บในเอกสารพรีเซนต์ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าตัวอักษรโดยตรง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | คืนค่า หรือ ตั้งค่าสตริงตามตัวอักษร หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนค่า หรือ ตั้งค่าสตริงตามตัวอักษร หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. |
| [toString()](#toString--) | คืนค่าการแสดงผลเป็นสตริง. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | ตั้งค่าจากเซลล์ที่ระบุ. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.Worksheet แล้วเมธอดนี้จะคืนค่าที่อยู่ของเซลล์ในเวิร์กบุ๊กที่แสดงข้อมูลสตริง. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


คืนค่า หรือ ตั้งค่าสตริงตามตัวอักษร หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


คืนค่า หรือ ตั้งค่าสตริงตามตัวอักษร หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


คืนค่าการแสดงผลเป็นสตริง.

**ผลลัพธ์:**
java.lang.String - การแสดงผลเป็นสตริงของค่า String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


ตั้งค่าจากเซลล์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.Worksheet แล้วเมธอดนี้จะคืนค่าที่อยู่ของเซลล์ในเวิร์กบุ๊กที่แสดงข้อมูลสตริง. หากไม่เป็นเช่นนั้น ให้คืนค่าว่าง.

**ผลลัพธ์:**
java.lang.String - ค่าสตริง String