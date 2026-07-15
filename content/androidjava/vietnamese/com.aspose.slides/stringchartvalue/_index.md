---
title: StringChartValue
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên văn.
type: docs
url: /vi/com.aspose.slides/stringchartvalue/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu bài thuyết trình pptx theo hai cách: 1) trong ô/ô của bảng tính liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên văn.
## Phương thức

| Phương thức | Mô tả |
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

Không cho phép gán giá trị null. Giá trị trả về luôn không phải null. Đọc/ghi [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Trả về:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Không cho phép gán giá trị null. Giá trị trả về luôn không phải null. Đọc/ghi [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |
### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên văn. Đọc/ghi String.

**Trả về:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên văn. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getData() {#getData--}
```
public Object getData()
```

Trả về hoặc đặt đối tượng Data. Đọc/ghi Object.

**Trả về:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Trả về hoặc đặt đối tượng Data. Đọc/ghi Object.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.Object |  |
### toString() {#toString--}
```
public String toString()
```

Trả về dữ liệu giá trị chuỗi. Trả về null nếu DataSourceType là false và không có giá trị chuỗi nào được gán.

**Trả về:**
java.lang.String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Đặt giá trị từ ô được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |
### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong workbook đại diện cho dữ liệu chuỗi. Ngược lại trả về chuỗi rỗng.

**Trả về:**
java.lang.String