---
title: IErrorBarsFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho các thanh lỗi của chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/ierrorbarsformat/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IErrorBarsFormat extends IChartComponent
```

Đại diện cho các thanh lỗi của chuỗi biểu đồ. Các giá trị tùy chỉnh của ErrorBars nằm trong IChartDataPointCollection (trong thuộc tính [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Lấy hoặc đặt loại thanh lỗi. |
| [setType(int value)](#setType-int-) | Lấy hoặc đặt loại thanh lỗi. |
| [getValueType()](#getValueType--) | Biểu diễn các cách có thể để xác định độ dài của thanh lỗi. |
| [setValueType(int value)](#setValueType-int-) | Biểu diễn các cách có thể để xác định độ dài của thanh lỗi. |
| [hasEndCap()](#hasEndCap--) | Chỉ định một end cap không được vẽ trên thanh lỗi. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Chỉ định một end cap không được vẽ trên thanh lỗi. |
| [getValue()](#getValue--) | Lấy hoặc đặt giá trị được sử dụng với các kiểu giá trị Fixed, Percentage và StandardDeviation để xác định độ dài của thanh lỗi. |
| [setValue(float value)](#setValue-float-) | Lấy hoặc đặt giá trị được sử dụng với các kiểu giá trị Fixed, Percentage và StandardDeviation để xác định độ dài của thanh lỗi. |
| [getFormat()](#getFormat--) | Biểu diễn định dạng của thanh lỗi. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn định dạng của thanh lỗi. |
| [isVisible()](#isVisible--) | Lấy hoặc đặt khả năng hiển thị của Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Lấy hoặc đặt khả năng hiển thị của Error Bars. |

### getType() {#getType--}
```
public abstract int getType()
```

Lấy hoặc đặt loại thanh lỗi. Đọc/ghi [ErrorBarType](../../com.aspose.slides/errorbartype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Lấy hoặc đặt loại thanh lỗi. Đọc/ghi [ErrorBarType](../../com.aspose.slides/errorbartype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Biểu diễn các cách có thể để xác định độ dài của thanh lỗi. Trong trường hợp kiểu giá trị tùy chỉnh để chỉ định giá trị, sử dụng thuộc tính [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) của điểm dữ liệu cụ thể trong bộ sưu tập DataPoints của chuỗi. Đọc/ghi [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Trả về:**
int

### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Biểu diễn các cách có thể để xác định độ dài của thanh lỗi. Trong trường hợp kiểu giá trị tùy chỉnh để chỉ định giá trị, sử dụng thuộc tính [IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues) của điểm dữ liệu cụ thể trong bộ sưu tập DataPoints của chuỗi. Đọc/ghi [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public abstract boolean hasEndCap()
```

Chỉ định một end cap không được vẽ trên thanh lỗi. Đọc/ghi boolean.

**Trả về:**
boolean

### setEndCap(boolean value) {#setEndCap-boolean-}
```
public abstract void setEndCap(boolean value)
```

Chỉ định một end cap không được vẽ trên thanh lỗi. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public abstract float getValue()
```

Lấy hoặc đặt giá trị được sử dụng với các kiểu giá trị Fixed, Percentage và StandardDeviation để xác định độ dài của thanh lỗi. Đọc/ghi float.

**Trả về:**
float

### setValue(float value) {#setValue-float-}
```
public abstract void setValue(float value)
```

Lấy hoặc đặt giá trị được sử dụng với các kiểu giá trị Fixed, Percentage và StandardDeviation để xác định độ dài của thanh lỗi. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Biểu diễn định dạng của thanh lỗi. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Biểu diễn định dạng của thanh lỗi. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Lấy hoặc đặt khả năng hiển thị của Error Bars. Đọc/ghi boolean.

**Trả về:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Lấy hoặc đặt khả năng hiển thị của Error Bars. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |