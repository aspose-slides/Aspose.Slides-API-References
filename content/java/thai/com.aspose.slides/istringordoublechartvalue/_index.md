---
title: IStringOrDoubleChartValue
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แทนค่าสตริงหรือค่าทศนิยมที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี 1 ในเซลล์/เซลล์ของสมุดงานที่เชื่อมโยงกับแผนภูมิ 2 เป็นค่าลิเทรัล
type: docs
url: /th/com.aspose.slides/istringordoublechartvalue/
---
**ทั้งหมดที่เป็นอินเทอร์เฟซที่ใช้งาน:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

แทนค่าสตริงหรือค่าทศนิยมที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของสมุดงานที่เชื่อมโยงกับแผนภูมิ; 2) เป็นค่าลิเทรัล
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | คืนค่า หรือกำหนดสตริงลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | คืนค่า หรือกำหนดสตริงลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือกำหนดค่าทศนิยมลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือกำหนดค่าทศนิยมลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double. |
| [toDouble()](#toDouble--) | แปลงค่าเป็น double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

คืนค่า หรือกำหนดสตริงลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

คืนค่า หรือกำหนดสตริงลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.StringLiterals. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

คืนค่า หรือกำหนดค่าทศนิยมลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**คืนค่า:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

คืนค่า หรือกำหนดค่าทศนิยมลิเทรัลหากคุณสมบัติ DataSourceType มีค่าเป็น DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

แปลงค่าเป็น double.

**คืนค่า:**
double - Double value double