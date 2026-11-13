---
title: ChartDataPoint
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn điểm dữ liệu của series.
type: docs
url: /vi/com.aspose.slides/chartdatapoint/
---
**Kế thừa:**  
java.lang.Object

**Tất cả giao diện được triển khai:**  
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject  
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

Biểu diễn điểm dữ liệu của series.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | Returns the size value of chart data point. |
| [getColorValue()](#getColorValue--) | Returns the color value of chart data point. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Represents series error bars values in case of Custom value type. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | Specifies that the bubbles have a 3-D effect applied to them. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Specifies that the bubbles have a 3-D effect applied to them. |
| [getExplosion()](#getExplosion--) | Specifies the amount the data point shall be moved from the center of the pie. |
| [setExplosion(int value)](#setExplosion-int-) | Specifies the amount the data point shall be moved from the center of the pie. |
| [getFormat()](#getFormat--) | Represents the formatting properties. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Represents the formatting properties. |
| [getMarker()](#getMarker--) | Specifies a data marker. |
| [getSetAsTotal()](#getSetAsTotal--) | Sets data point as total. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Sets data point as total. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Properties of corresponding legend entry in case of chart type from this list: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | Removes DataPoint from chart series. |
| [getDataPointLevels()](#getDataPointLevels--) | Returns container of data point levels. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Returns an automatic color of data point based on series index, data point index, ParentSeriesGroup.IsColorVaried property and chart style. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Specifies the data point shall invert its colors if the value is negative. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Specifies the data point shall invert its colors if the value is negative. |
| [getCachedValue()](#getCachedValue--) | Gets the cached value of a chart data point. |
| [getCachedXValue()](#getCachedXValue--) | Gets the cached X value of a chart data point. |
| [getCachedYValue()](#getCachedYValue--) | Gets the cached Y value of a chart data point. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Gets the cached bubble size of a chart data point. |
| [getActualX()](#getActualX--) | Specifies actual x location (left) of the chart element relative to the left top corner of the chart. |
| [getActualY()](#getActualY--) | Specifies actual top of the chart element relative to the left top corner of the chart. |
| [getActualWidth()](#getActualWidth--) | Specifies actual width of the chart element. |
| [getActualHeight()](#getActualHeight--) | Specifies actual height of the chart element. |

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

Biểu diễn giá trị thanh lỗi của series trong trường hợp kiểu giá trị Custom. Chỉ đọc [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

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

Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. Đọc/ghi boolean.

**Trả về:**  
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. Đọc/ghi boolean.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm bánh răng. Đọc/ghi int.

**Trả về:**  
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Chỉ định lượng mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm bánh răng. Đọc/ghi int.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
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
| Tham số | Kiểu | Mô tả |
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

Đặt điểm dữ liệu làm tổng. Áp dụng chỉ cho loại series Waterfall.

**Trả về:**  
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

Đặt điểm dữ liệu làm tổng. Áp dụng chỉ cho loại series Waterfall.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ từ danh sách này: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

Xóa DataPoint khỏi series biểu đồ.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

Trả về container của các cấp độ điểm dữ liệu. Áp dụng cho series Treeamp và Sunburst. Chỉ mục cấp độ điểm dữ liệu bắt đầu từ 0.

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
public final Color getAutomaticDataPointColor()
```

Trả về một màu tự động của điểm dữ liệu dựa trên chỉ số series, chỉ số điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**  
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi boolean.

**Trả về:**  
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Chỉ định rằng điểm dữ liệu sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi boolean.

**Tham số:**  
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

Lấy giá trị đã lưu của một điểm dữ liệu biểu đồ. Chỉ đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In ra tất cả các giá trị đã lưu của series biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

Lấy giá trị đã lưu X của một điểm dữ liệu biểu đồ. Chỉ đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In ra tất cả các giá trị X đã lưu của series biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

Lấy giá trị đã lưu Y của một điểm dữ liệu biểu đồ. Chỉ đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In ra tất cả các giá trị Y đã lưu của series biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

Lấy kích thước bong bóng đã lưu của một điểm dữ liệu biểu đồ. Chỉ đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In ra tất cả các giá trị kích thước bong bóng đã lưu của series biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**  
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

Chỉ định vị trí x thực tế (trái) của phần tử biểu đồ so với góc trên-trái của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

**Trả về:**  
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

Chỉ định vị trí y thực tế của phần tử biểu đồ so với góc trên-trái của biểu đồ. Gọi phương thức IChart.ValidateChartLayout() trước để lấy giá trị thực tế. Đọc float.

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