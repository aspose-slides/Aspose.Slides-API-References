---
title: IStringOrDoubleChartValue
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn giá trị chuỗi hoặc số thực có thể được lưu trong tài liệu trình chiếu pptx theo hai cách 1) trong ô/ô của workbook liên quan đến chart 2) dưới dạng giá trị nguyên thủy.
type: docs
url: /vi/com.aspose.slides/istringordoublechartvalue/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IStringOrDoubleChartValue extends ISingleCellChartValue
```

Biểu diễn giá trị chuỗi hoặc số thực có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến chart; 2) dưới dạng giá trị nguyên thủy.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Trả về hoặc thiết lập chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Trả về hoặc thiết lập chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Trả về hoặc thiết lập số thực nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Trả về hoặc thiết lập số thực nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Chuyển đổi giá trị thành double. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Trả về hoặc thiết lập chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Trả về:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Trả về hoặc thiết lập chuỗi nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.StringLiterals. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Trả về hoặc thiết lập số thực nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.DoubleLiterals. Đọc/ghi double.

**Trả về:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Trả về hoặc thiết lập số thực nguyên thủy nếu thuộc tính DataSourceType là DataSourceType.DoubleLiterals. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Chuyển đổi giá trị thành double.

**Trả về:**
double - Giá trị double