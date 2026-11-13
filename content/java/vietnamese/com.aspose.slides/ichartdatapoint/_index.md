---
title: IChartDataPoint
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn điểm dữ liệu chuỗi.
type: docs
url: /vi/com.aspose.slides/ichartdatapoint/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

Biểu diễn điểm dữ liệu chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getXValue()](#getXValue--) | Lấy giá trị x của một điểm dữ liệu biểu đồ. |
| [getYValue()](#getYValue--) | Lấy giá trị y của một điểm dữ liệu biểu đồ. |
| [getBubbleSize()](#getBubbleSize--) | Lấy kích thước bong bóng của một điểm dữ liệu biểu đồ. |
| [getValue()](#getValue--) | Lấy giá trị của một điểm dữ liệu biểu đồ. |
| [getCachedXValue()](#getCachedXValue--) | Lấy giá trị X đã lưu của một điểm dữ liệu biểu đồ. |
| [getCachedYValue()](#getCachedYValue--) | Lấy giá trị Y đã lưu của một điểm dữ liệu biểu đồ. |
| [getCachedValue()](#getCachedValue--) | Lấy giá trị đã lưu của một điểm dữ liệu biểu đồ. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | Lấy kích thước bong bóng đã lưu của một điểm dữ liệu biểu đồ. |
| [getSizeValue()](#getSizeValue--) | Lấy giá trị kích thước của một điểm dữ liệu biểu đồ. |
| [getColorValue()](#getColorValue--) | Lấy giá trị màu của một điểm dữ liệu biểu đồ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | Biểu diễn giá trị thanh lỗi chuỗi trong trường hợp loại giá trị Tùy chỉnh. |
| [getLabel()](#getLabel--) | Biểu diễn nhãn của điểm dữ liệu biểu đồ. |
| [isBubble3D()](#isBubble3D--) | Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. |
| [getExplosion()](#getExplosion--) | Chỉ định khoảng cách mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. |
| [setExplosion(int value)](#setExplosion-int-) | Chỉ định khoảng cách mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. |
| [getFormat()](#getFormat--) | Biểu diễn các thuộc tính định dạng. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Biểu diễn các thuộc tính định dạng. |
| [getMarker()](#getMarker--) | Chỉ định một dấu dữ liệu. |
| [remove()](#remove--) | Xóa DataPoint khỏi chuỗi biểu đồ. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | Trả về một màu tự động cho điểm dữ liệu dựa trên chỉ mục chuỗi, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | Đặt điểm dữ liệu là tổng. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | Đặt điểm dữ liệu là tổng. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Chỉ định điểm dữ liệu sẽ đảo ngược màu nếu giá trị âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Chỉ định điểm dữ liệu sẽ đảo ngược màu nếu giá trị âm. |
| [getDataPointLevels()](#getDataPointLevels--) | Trả về container của các cấp độ điểm dữ liệu. |
| [getIndex()](#getIndex--) | Xác định collection con nào của cha mà điểm dữ liệu này áp dụng. |
### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


Lấy giá trị x của một điểm dữ liệu biểu đồ. Chỉ-đọc [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**Trả về:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


Lấy giá trị y của một điểm dữ liệu biểu đồ. Chỉ-đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


Lấy kích thước bong bóng của một điểm dữ liệu biểu đồ. Chỉ-đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


Lấy giá trị của một điểm dữ liệu biểu đồ. Chỉ-đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


Lấy giá trị X đã lưu của một điểm dữ liệu biểu đồ. Chỉ-đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In tất cả các giá trị X đã lưu của chuỗi biểu đồ.
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
public abstract ICachedChartValue getCachedYValue()
```


Lấy giá trị Y đã lưu của một điểm dữ liệu biểu đồ. Chỉ-đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In tất cả các giá trị Y đã lưu của chuỗi biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Lấy giá trị đã lưu của một điểm dữ liệu biểu đồ. Chỉ-đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In tất cả các giá trị đã lưu của chuỗi biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


Lấy kích thước bong bóng đã lưu của một điểm dữ liệu biểu đồ. Chỉ-đọc [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // In tất cả các giá trị kích thước bong bóng đã lưu của chuỗi biểu đồ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


Lấy giá trị kích thước của một điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Treemap và Sunburst. Chỉ-đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


Lấy giá trị màu của một điểm dữ liệu biểu đồ. Được sử dụng với biểu đồ Map. Chỉ-đọc [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**Trả về:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


Biểu diễn giá trị thanh lỗi chuỗi trong trường hợp loại giá trị Tùy chỉnh. Chỉ-đọc [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**Trả về:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


Biểu diễn nhãn của điểm dữ liệu biểu đồ. Chỉ-đọc [IDataLabel](../../com.aspose.slides/idatalabel).

**Trả về:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. Đọc/ghi boolean.

**Trả về:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


Chỉ định rằng các bong bóng có hiệu ứng 3D được áp dụng. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


Chỉ định khoảng cách mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. Đọc/ghi int.

**Trả về:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


Chỉ định khoảng cách mà điểm dữ liệu sẽ được di chuyển khỏi trung tâm của biểu đồ tròn. Đọc/ghi int.

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


Chỉ định một dấu dữ liệu. Chỉ-đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


Xóa DataPoint khỏi chuỗi biểu đồ.
### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


Trả về một màu tự động cho điểm dữ liệu dựa trên chỉ mục chuỗi, chỉ mục điểm dữ liệu, thuộc tính ParentSeriesGroup.IsColorVaried và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


Thuộc tính của mục chú giải tương ứng trong trường hợp loại biểu đồ thuộc danh sách: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. Chỉ-đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


Đặt điểm dữ liệu là tổng. Áp dụng chỉ cho loại chuỗi Waterfall.

**Trả về:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


Đặt điểm dữ liệu là tổng. Áp dụng chỉ cho loại chuỗi Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


Chỉ định điểm dữ liệu sẽ đảo ngược màu nếu giá trị âm. Đọc/ghi boolean.

**Trả về:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


Chỉ định điểm dữ liệu sẽ đảo ngược màu nếu giá trị âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


Trả về container của các cấp độ điểm dữ liệu. Áp dụng cho chuỗi Treeamp và Sunburst. Đánh chỉ số cấp độ điểm dữ liệu bắt đầu từ 0.

**Trả về:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


Xác định collection con nào của cha mà điểm dữ liệu này áp dụng. Đọc long.

**Trả về:**
long