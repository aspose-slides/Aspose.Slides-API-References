---
title: IStringChartValue
second_title: Tham khảo API Aspose.Slides cho Java
description: Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô hoặc các ô của sổ làm việc liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên văn.
type: docs
url: /vi/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/các ô của sổ làm việc liên quan tới biểu đồ; 2) dưới dạng giá trị nguyên văn.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Trả về hoặc đặt chuỗi nguyên văn nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Trả về hoặc đặt chuỗi nguyên văn nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [toString()](#toString--) | Trả về biểu diễn chuỗi. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Đặt giá trị từ ô đã chỉ định. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong sổ làm việc đại diện cho dữ liệu chuỗi. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Trả về hoặc đặt chuỗi nguyên văn nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Returns:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Trả về hoặc đặt chuỗi nguyên văn nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Trả về biểu diễn chuỗi.

**Returns:**
java.lang.String - String representation of a value String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Đặt giá trị từ ô đã chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Ô. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong sổ làm việc đại diện cho dữ liệu chuỗi. Nếu không, trả về chuỗi rỗng.

**Returns:**
java.lang.String - giá trị String