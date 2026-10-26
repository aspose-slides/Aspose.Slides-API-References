---
title: IDoubleChartValue
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn giá trị double có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1 trong ô/ô của workbook liên quan đến chart 2 dưới dạng giá trị literal.
type: docs
url: /vi/com.aspose.slides/idoublechartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISingleCellChartValue](../../com.aspose.slides/isinglecellchartvalue)
```
public interface IDoubleChartValue extends ISingleCellChartValue
```

Biểu diễn giá trị double có thể được lưu trong tài liệu trình chiếu pptx theo hai cách: 1) trong ô/ô của workbook liên quan đến chart; 2) dưới dạng giá trị literal.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Trả về hoặc đặt giá trị double literal nếu DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Trả về hoặc đặt giá trị double literal nếu DataSourceType = Charts.DataSourceType.DoubleLiterals. |
| [toDouble()](#toDouble--) | Chuyển đổi sang double. |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public abstract double getAsLiteralDouble()
```

Trả về hoặc đặt giá trị double literal nếu DataSourceType = Charts.DataSourceType.DoubleLiterals. Đọc/ghi double.

**Trả về:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public abstract void setAsLiteralDouble(double value)
```

Trả về hoặc đặt giá trị double literal nếu DataSourceType = Charts.DataSourceType.DoubleLiterals. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Chuyển đổi sang double.

**Trả về:**
double - giá trị Double.