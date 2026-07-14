---
title: IDoubleChartValue
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นค่าดับเบิลที่สามารถเก็บไว้ในเอกสารพรีเซนเทชัน pptx ได้สองวิธี 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2) เป็นค่าตัวอักษรโดยตรง.
type: docs
url: /th/com.aspose.slides/idoublechartvalue/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

เป็นค่า double ที่สามารถเก็บไว้ในเอกสารพรีเซนเทชัน pptx ได้สองวิธี: 1) ในเซลล์/เซลล์ของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ; 2) เป็นค่าตัวอักษรโดยตรง.
## เมธอด

| Method | Description |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | คืนค่า或กำหนดค่าตัวเลข double โดยตรง หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | คืนค่า或กำหนดค่าตัวเลข double โดยตรง หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double. |
| [toDouble()](#toDouble--) | แปลงเป็น double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```


คืนค่า或กำหนดค่าตัวเลข double โดยตรง หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```


คืนค่า或กำหนดค่าตัวเลข double โดยตรง หาก DataSourceType = Charts.DataSourceType.DoubleLiterals. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


แปลงเป็น double.

**ผลลัพธ์:**
double - ค่า Double.