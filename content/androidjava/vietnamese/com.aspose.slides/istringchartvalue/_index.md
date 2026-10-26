---
title: IStringChartValue
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên thủy.
type: docs
url: /vi/com.aspose.slides/istringchartvalue/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Biểu diễn giá trị chuỗi có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến biểu đồ; 2) dưới dạng giá trị nguyên thủy.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Trả về hoặc đặt chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Trả về hoặc đặt chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [toString()](#toString--) | Trả về biểu diễn chuỗi. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Đặt giá trị từ ô được chỉ định. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong workbook đại diện cho dữ liệu chuỗi. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Trả về hoặc đặt chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Trả về:**  
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Trả về hoặc đặt chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Trả về biểu diễn chuỗi.

**Trả về:**  
java.lang.String - Biểu diễn chuỗi của một giá trị String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Đặt giá trị từ ô được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Nếu thuộc tính DataSourceType là DataSourceType.Worksheet thì phương thức này trả về địa chỉ của các ô trong workbook đại diện cho dữ liệu chuỗi. Nếu không, trả về chuỗi rỗng.

**Trả về:**  
java.lang.String - Giá trị chuỗi String