---
title: DoubleChartValue
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn giá trị double có thể được lưu trong tài liệu bản trình bày pptx theo hai cách: 1) trong ô/ô của bảng tính liên quan đến biểu đồ; 2) dưới dạng giá trị literal.
type: docs
url: /vi/com.aspose.slides/doublechartvalue/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Biểu diễn giá trị double có thể được lưu trong tài liệu bản trình bày pptx theo hai cách: 1) trong ô/ô của bảng tính liên quan đến biểu đồ; 2) dưới dạng giá trị literal.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAsCell()](#getAsCell--) | Trả về hoặc đặt ô dữ liệu biểu đồ. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Trả về hoặc đặt ô dữ liệu biểu đồ. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Trả về hoặc đặt giá trị dưới dạng literal double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Trả về hoặc đặt giá trị dưới dạng literal double. |
| [getData()](#getData--) | Trả về hoặc đặt đối tượng Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Trả về hoặc đặt đối tượng Data. |
| [toDouble()](#toDouble--) | Chuyển đổi sang double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Trả về hoặc đặt ô dữ liệu biểu đồ. Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Trả về:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Trả về hoặc đặt ô dữ liệu biểu đồ. Đọc/ghi [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Trả về hoặc đặt giá trị dưới dạng literal double. Đọc/ghi double.

**Trả về:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Trả về hoặc đặt giá trị dưới dạng literal double. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

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

### toDouble() {#toDouble--}
```
public final double toDouble()
```

Chuyển đổi sang double.

**Trả về:**
double - Trả về LiteralDouble nếu DataSourceType bằng DoubleLiterals. Nếu DataSourceType bằng Worksheet trả về giá trị ô đã được chuyển đổi thành double thành công, nếu không trả về NaN.