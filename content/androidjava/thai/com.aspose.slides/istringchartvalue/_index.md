---
title: IStringChartValue
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนค่าสตริงที่สามารถจัดเก็บในเอกสารการนำเสนอ pptx ได้สองวิธี 1 ในเซลหรือเซลของเวิร์กบุ๊กที่เกี่ยวข้องกับแผนภูมิ 2 เป็นค่าลิทเทอรัล
type: docs
url: /th/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value.

## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Returns or sets the literal string if DataSourceType property is DataSourceType.StringLiterals. |
| [toString()](#toString--) | Returns string representation. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Sets value from specified cell. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

คืนค่า หรือ ตั้งค่าสตริงเชิงอักษรถ้า property DataSourceType มีค่าเป็น DataSourceType.StringLiterals. Read/write String.

**Returns:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

คืนค่า หรือ ตั้งค่าสตริงเชิงอักษรถ้า property DataSourceType มีค่าเป็น DataSourceType.StringLiterals. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

คืนค่าการแสดงผลในรูปแบบสตริง.

**Returns:**
java.lang.String - String representation of a value String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

ตั้งค่าจากเซลที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซล. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

If DataSourceType property is DataSourceType.Worksheet then this method returns address of the cells in workbook which represent the string data. Otherwise return empty string.

**Returns:**
java.lang.String - String value String