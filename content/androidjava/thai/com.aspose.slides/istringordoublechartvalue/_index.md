---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงค่าข้อความหรือค่าทศนิยมที่สามารถจัดเก็บในเอกสารการพรีเซนต์ pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของ workbook ที่เกี่ยวข้องกับแผนภูมิ 2 เป็นค่าตัวอักษรตามจริง.
type: docs
url: /th/com.aspose.slides/istringordoublechartvalue/
---
**ทั้งหมดที่ทำตาม Interface:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

แสดงค่าข้อความหรือจำนวนจริงที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของ workbook ที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าตัวอักษรตามจริง.
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | คืนค่า หรือ ตั้งค่าข้อความตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนค่า หรือ ตั้งค่าข้อความตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือ ตั้งค่าค่าทศนิยมตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือ ตั้งค่าค่าทศนิยมตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | แปลงค่าเป็น double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

คืนค่า หรือ ตั้งค่าข้อความตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

คืนค่า หรือ ตั้งค่าข้อความตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

คืนค่า หรือ ตั้งค่าค่าทศนิยมตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**คืนค่า:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

คืนค่า หรือ ตั้งค่าค่าทศนิยมตามจริง หากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

แปลงค่าเป็น double.

**คืนค่า:**
double - ค่า double