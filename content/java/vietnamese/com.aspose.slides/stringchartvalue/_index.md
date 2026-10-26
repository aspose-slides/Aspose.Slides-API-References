---
title: StringChartValue
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên thủy.
type: docs
url: /vi/com.aspose.slides/stringchartvalue/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**All Implemented Interfaces:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên thủy.
## Phương thức

| Method | Description |
| --- | --- |
| [getAsCells()](#getAsCells--) | Không được phép gán giá trị null. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Không được phép gán giá trị null. |
| [getAsLiteralString()](#getAsLiteralString--) | Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên thủy. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên thủy. |
| [getData()](#getData--) | Trả về hoặc đặt đối tượng Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Trả về hoặc đặt đối tượng Data. |
| [toString()](#toString--) | Trả về dữ liệu giá trị chuỗi. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Đặt giá trị từ ô đã chỉ định. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong workbook đại diện cho dữ liệu chuỗi. |
### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```


Không được phép gán giá trị null. Giá trị trả về luôn không phải null. Đọc/ghi [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Trả về:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```


Không được phép gán giá trị null. Giá trị trả về luôn không phải null. Đọc/ghi [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên thủy. Đọc/ghi String.

**Trả về:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Trả về hoặc đặt giá trị dưới dạng chuỗi nguyên thủy. Đọc/ghi String.

**Tham số:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
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


Đặt giá trị từ ô đã chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```


Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong workbook đại diện cho dữ liệu chuỗi. Nếu không, trả về chuỗi rỗng.

**Trả về:**
java.lang.String