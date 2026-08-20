---
title: IDoubleChartValue
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนค่าดับเบิลที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี 1 ใน cell/cells ของ workbook ที่เกี่ยวข้องกับ chart 2 เป็นค่า literal
type: docs
url: /th/com.aspose.slides/idoublechartvalue/
---
**Interfaces ที่ Implement ทั้งหมด:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

แทนค่าดับเบิลที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี: 1) ใน cell/cells ของ workbook ที่เกี่ยวข้องกับ chart; 2) เป็นค่า literal

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า หรือ ตั้งค่า literal double value หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า หรือ ตั้งค่า literal double value หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | แปลงเป็น double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


คืนค่า หรือ ตั้งค่า literal double value หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**คืนค่า:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


คืนค่า หรือ ตั้งค่า literal double value หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


แปลงเป็น double.

**คืนค่า:**
double - Double value.