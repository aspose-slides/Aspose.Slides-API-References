---
title: ChartDataPoint
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn điểm dữ liệu của chuỗi.
type: docs
url: /vi/com.aspose.slides/chartdatapoint/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Biểu diễn điểm dữ liệu của chuỗi.
## Các phương thức

| Method | Description |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Trả về giá trị kích thước của điểm dữ liệu biểu đồ. |
| [getColorValue()](#getColorValue--) | Trả về giá trị màu của điểm dữ liệu biểu đồ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Biểu diễn giá trị thanh lỗi của chuỗi trong trường hợp kiểu giá trị Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng cho chúng. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng cho chúng. |
| [getExplosion()](#getExplosion--) | Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. |
| [setExplosion(int value)](#setExplosion-int-) | Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. |
| [getFormat()](#getFormat--) | Biểu diễn các thuộc tính định dạng. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn các thuộc tính định dạng. |
| [getMarker()](#getMarker--) | Chỉ định một dấu dữ liệu. |
| [getSetAsTotal()](#getSetAsTotal--) | Đặt điểm dữ liệu làm tổng. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Đặt điểm dữ liệu làm tổng. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Xóa DataPoint khỏi chuỗi biểu đồ. |
| [getDataPointLevels()](#getDataPointLevels--) | Trả về container của các mức điểm dữ liệu. |
| [getIndex()](#getIndex--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Trả về màu tự động của điểm dữ liệu dựa trên chỉ số chuỗi, chỉ số điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. |
| [getActualX()](#getActualX--) | Chỉ định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualY()](#getActualY--) | Chỉ định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. |
| [getActualWidth()](#getActualWidth--) | Chỉ định chiều rộng thực tế của phần tử biểu đồ. |
| [getActualHeight()](#getActualHeight--) | Chỉ định chiều cao thực tế của phần tử biểu đồ. |
### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```


XValue. Chỉ đọc [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Trả về:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```


YValue. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```


BubbleSize. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```


Value. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```


Trả về giá trị kích thước của điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Treemap và Sunburst. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```


Trả về giá trị màu của điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Map. Chỉ đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```


Biểu diễn giá trị thanh lỗi của chuỗi trong trường hợp kiểu giá trị Custom. Chỉ đọc [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Trả về:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```


Label. Chỉ đọc [IDataLabel](../../com.aspose.slides/idatalabel).

**Trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```


Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng cho chúng. Đọc/ghi boolean.

**Trả về:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```


Chỉ định rằng các bong bóng có hiệu ứng 3-D được áp dụng cho chúng. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```


Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. Đọc/ghi int.

**Trả về:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```


Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. Đọc/ghi int.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```


Biểu diễn các thuộc tính định dạng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```


Biểu diễn các thuộc tính định dạng. Đọc/ghi [IFormat](../../com.aspose.slides/iformat).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```


Chỉ định một dấu dữ liệu. Chỉ đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)
### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```


Đặt điểm dữ liệu làm tổng. Áp dụng chỉ cho loại chuỗi Waterfall.

**Trả về:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```


Đặt điểm dữ liệu làm tổng. Áp dụng chỉ cho loại chuỗi Waterfall.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```


Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### remove() {#remove--}
```
public final void remove()
```


Xóa DataPoint khỏi chuỗi biểu đồ.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```


Trả về container của các mức điểm dữ liệu. Áp dụng cho chuỗi Treeamp và Sunburst. Phân chỉ mục mức điểm dữ liệu bắt đầu từ 0.

**Trả về:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public final long getIndex()
```


  

**Trả về:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Integer getAutomaticDataPointColor()
```


Trả về màu tự động của điểm dữ liệu dựa trên chỉ số chuỗi, chỉ số điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. Màu này được dùng làm mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.lang.Integer
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```


Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. Đọc/ ghi boolean.

**Trả về:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```


Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. Đọc/ ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getActualX() {#getActualX--}
```
public final float getActualX()
```


Chỉ định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualY() {#getActualY--}
```
public final float getActualY()
```


Chỉ định vị trí trên thực tế của phần tử biểu đồ so với góc trái trên của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```


Chỉ định chiều rộng thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float
### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```


Chỉ định chiều cao thực tế của phần tử biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**
float