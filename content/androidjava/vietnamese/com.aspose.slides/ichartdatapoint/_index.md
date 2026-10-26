---
title: IChartDataPoint
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn điểm dữ liệu của series.
type: docs
url: /vi/com.aspose.slides/ichartdatapoint/
---
**Tất cả các giao diện đã thực hiện:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Biểu diễn điểm dữ liệu series.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXValue()](#getXValue--) | Trả về giá trị x của điểm dữ liệu biểu đồ. |
| [getYValue()](#getYValue--) | Trả về giá trị y của điểm dữ liệu biểu đồ. |
| [getBubbleSize()](#getBubbleSize--) | Trả về kích thước bong bóng của điểm dữ liệu biểu đồ. |
| [getValue()](#getValue--) | Trả về giá trị của điểm dữ liệu biểu đồ. |
| [getSizeValue()](#getSizeValue--) | Trả về giá trị kích thước của điểm dữ liệu biểu đồ. |
| [getColorValue()](#getColorValue--) | Trả về giá trị màu của điểm dữ liệu biểu đồ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Biểu diễn các giá trị thanh lỗi series trong trường hợp loại giá trị Tùy chỉnh. |
| [getLabel()](#getLabel--) | Biểu diễn nhãn của điểm dữ liệu biểu đồ. |
| [isBubble3D()](#isBubble3D--) | Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng. |
| [getExplosion()](#getExplosion--) | Chỉ định mức độ mà điểm dữ liệu sẽ được di chuyển ra khỏi trung tâm của bánh. |
| [setExplosion(int value)](#setExplosion-int-) | Chỉ định mức độ mà điểm dữ liệu sẽ được di chuyển ra khỏi trung tâm của bánh. |
| [getFormat()](#getFormat--) | Biểu diễn các thuộc tính định dạng. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn các thuộc tính định dạng. |
| [getMarker()](#getMarker--) | Chỉ định một dấu dữ liệu. |
| [remove()](#remove--) | Xóa DataPoint khỏi series biểu đồ. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Trả về màu tự động của điểm dữ liệu dựa trên chỉ mục series, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Các thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Đặt điểm dữ liệu là tổng. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Đặt điểm dữ liệu là tổng. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Chỉ định rằng điểm dữ liệu sẽ đảo màu nếu giá trị âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Chỉ định rằng điểm dữ liệu sẽ đảo màu nếu giá trị âm. |
| [getDataPointLevels()](#getDataPointLevels--) | Trả về container của các cấp độ điểm dữ liệu. |
| [getIndex()](#getIndex--) | Xác định bộ sưu tập con của cha mà điểm dữ liệu này áp dụng. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Trả về giá trị x của điểm dữ liệu biểu đồ. Chỉ đọc [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Trả về:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Trả về giá trị y của điểm dữ liệu biểu đồ. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Trả về kích thước bong bóng của điểm dữ liệu biểu đồ. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Trả về giá trị của điểm dữ liệu biểu đồ. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Trả về giá trị kích thước của điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Treemap và Sunburst. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Trả về giá trị màu của điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Map. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Biểu diễn các giá trị thanh lỗi series trong trường hợp loại giá trị Tùy chỉnh. Chỉ đọc [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Trả về:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Biểu diễn nhãn của điểm dữ liệu biểu đồ. Chỉ đọc [IDataLabel](../../com.aspose.slides/idatalabel).

**Trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng. Đọc/ghi boolean.

**Trả về:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Chỉ định mức độ mà điểm dữ liệu sẽ được di chuyển ra khỏi trung tâm của bánh. Đọc/ghi int.

**Trả về:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Chỉ định mức độ mà điểm dữ liệu sẽ được di chuyển ra khỏi trung tâm của bánh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Biểu diễn các thuộc tính định dạng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


Biểu diễn các thuộc tính định dạng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


Chỉ định một dấu dữ liệu. Chỉ đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Xóa DataPoint khỏi series biểu đồ.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Integer getAutomaticDataPointColor()
```


Trả về màu tự động của điểm dữ liệu dựa trên chỉ mục series, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.lang.Integer - Automatic color of data point java.lang.Integer
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Các thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Đặt điểm dữ liệu là tổng. Áp dụng cho loại series Waterfall chỉ.

**Trả về:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Đặt điểm dữ liệu là tổng. Áp dụng cho loại series Waterfall chỉ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Chỉ định rằng điểm dữ liệu sẽ đảo màu nếu giá trị âm. Đọc/ghi boolean.

**Trả về:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Chỉ định rằng điểm dữ liệu sẽ đảo màu nếu giá trị âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Trả về container của các cấp độ điểm dữ liệu. Áp dụng cho series Treeamp và Sunburst. Đánh số cấp độ điểm dữ liệu bắt đầu từ 0.

**Trả về:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Xác định bộ sưu tập con của cha mà điểm dữ liệu này áp dụng. Chỉ đọc long.