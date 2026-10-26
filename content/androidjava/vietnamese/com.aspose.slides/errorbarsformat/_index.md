---
title: ErrorBarsFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn các error bars của chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/errorbarsformat/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
```
public class ErrorBarsFormat extends DomObject<ChartSeries> implements IErrorBarsFormat
```

Biểu diễn các error bars của chuỗi biểu đồ. Giá trị tùy chỉnh của ErrorBars nằm trong IChartDataPointCollection (trong thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Lấy hoặc đặt loại của error bars. |
| [setType(int value)](#setType-int-) | Lấy hoặc đặt loại của error bars. |
| [getValueType()](#getValueType--) | Biểu diễn các cách có thể để xác định độ dài của error bars. |
| [setValueType(int value)](#setValueType-int-) | Biểu diễn các cách có thể để xác định độ dài của error bars. |
| [hasEndCap()](#hasEndCap--) | Chỉ định một end cap không được vẽ trên error bars. |
| [setEndCap(boolean value)](#setEndCap-boolean-) | Chỉ định một end cap không được vẽ trên error bars. |
| [getValue()](#getValue--) | Lấy hoặc đặt giá trị được sử dụng với các kiểu Fixed, Percentage và StandardDeviation để xác định độ dài của error bars. |
| [setValue(float value)](#setValue-float-) | Lấy hoặc đặt giá trị được sử dụng với các kiểu Fixed, Percentage và StandardDeviation để xác định độ dài của error bars. |
| [getFormat()](#getFormat--) | Biểu diễn định dạng của error bars. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn định dạng của error bars. |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [isVisible()](#isVisible--) | Lấy hoặc đặt khả năng hiển thị của Error Bars. |
| [setVisible(boolean value)](#setVisible-boolean-) | Lấy hoặc đặt khả năng hiển thị của Error Bars. |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một FillFormat. |
### getType() {#getType--}
```
public final int getType()
```

Lấy hoặc đặt loại của error bars. Đọc/ghi [ErrorBarType](../../com.aspose.slides/errorbartype).

**Trả về:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Lấy hoặc đặt loại của error bars. Đọc/ghi [ErrorBarType](../../com.aspose.slides/errorbartype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getValueType() {#getValueType--}
```
public final int getValueType()
```

Biểu diễn các cách có thể để xác định độ dài của error bars. Trong trường hợp kiểu giá trị tùy chỉnh, để chỉ định giá trị sử dụng thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) của điểm dữ liệu cụ thể trong bộ sưu tập DataPoints của series. Trong trường hợp kiểu giá trị Fixed, Percentage hoặc StandardDeviation, sử dụng thuộc tính Value để chỉ định giá trị. Đọc/ghi [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Trả về:**
int
### setValueType(int value) {#setValueType-int-}
```
public final void setValueType(int value)
```

Biểu diễn các cách có thể để xác định độ dài của error bars. Trong trường hợp kiểu giá trị tùy chỉnh, để chỉ định giá trị sử dụng thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) của điểm dữ liệu cụ thể trong bộ sưu tập DataPoints của series. Trong trường hợp kiểu giá trị Fixed, Percentage hoặc StandardDeviation, sử dụng thuộc tính Value để chỉ định giá trị. Đọc/ghi [ErrorBarValueType](../../com.aspose.slides/errorbarvaluetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### hasEndCap() {#hasEndCap--}
```
public final boolean hasEndCap()
```

Chỉ định một end cap không được vẽ trên error bars. Đọc/ghi boolean.

**Trả về:**
boolean
### setEndCap(boolean value) {#setEndCap-boolean-}
```
public final void setEndCap(boolean value)
```

Chỉ định một end cap không được vẽ trên error bars. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getValue() {#getValue--}
```
public final float getValue()
```

Lấy hoặc đặt giá trị được sử dụng với các kiểu Fixed, Percentage và StandardDeviation để xác định độ dài của error bars. Trong bất kỳ trường hợp nào khác sẽ trả về NaN. Đọc/ghi float.

**Trả về:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```

Lấy hoặc đặt giá trị được sử dụng với các kiểu Fixed, Percentage và StandardDeviation để xác định độ dài của error bars. Trong bất kỳ trường hợp nào khác sẽ trả về NaN. Đọc/ghi float.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Biểu diễn định dạng của error bars. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Biểu diễn định dạng của error bars. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Lấy hoặc đặt khả năng hiển thị của Error Bars. Đọc/ghi boolean.

**Trả về:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Lấy hoặc đặt khả năng hiển thị của Error Bars. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của một FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của một FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)