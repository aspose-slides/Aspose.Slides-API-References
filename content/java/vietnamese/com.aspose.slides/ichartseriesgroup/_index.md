---
title: IChartSeriesGroup
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị nhóm các chuỗi.
type: docs
url: /vi/com.aspose.slides/ichartseriesgroup/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Biểu thị nhóm các chuỗi.

--------------------

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm các chuỗi chứa một số thuộc tính chuỗi mà chung cho mỗi chuỗi trong nhóm (“thuộc tính nhóm chuỗi”). “Thuộc tính nhóm chuỗi” trong lớp ChartSeriesGroup là đọc/ghi. Mỗi “thuộc tính nhóm chuỗi” có thể có một phiên bản chỉ đọc trong lớp ChartSeries.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về kiểu của nhóm chuỗi này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết liệu các chuỗi của nhóm này có được vẽ trên trục phụ hay không. |
| [getSeries()](#getSeries--) | Trả về một bộ sưu tập chỉ đọc của các chuỗi biểu đồ. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục xác định. |
| [getUpDownBars()](#getUpDownBars--) | Cung cấp quyền truy cập vào thanh tăng/giảm của biểu đồ Đường hoặc Cổ phiếu. |
| [getGapWidth()](#getGapWidth--) | Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. |
| [setGapWidth(int value)](#setGapWidth-int-) | Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của dấu đánh dấu. |
| [setGapDepth(int value)](#setGapDepth-int-) | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của dấu đánh dấu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lấy hoặc đặt góc của lát bánh hoặc vòng tròn đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lấy hoặc đặt góc của lát bánh hoặc vòng tròn đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [isColorVaried()](#isColorVaried--) | Chỉ định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Chỉ định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Đúng nếu biểu đồ có các đường chuỗi. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Đúng nếu biểu đồ có các đường chuỗi. |
| [getOverlap()](#getOverlap--) | Chỉ định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Chỉ định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Chỉ định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc thanh-con-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Chỉ định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc thanh-con-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Chỉ định giá trị được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Chỉ định giá trị được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. |
| [getPieSplitBy()](#getPieSplitBy--) | Chỉ định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Chỉ định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin tách tùy chỉnh cho biểu đồ bánh-con-bánh hoặc thanh-con-bánh có tách tùy chỉnh. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Chỉ định kích thước của lỗ trong biểu đồ vòng tròn (có thể từ 10 đến 90% kích thước vùng vẽ). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Chỉ định kích thước của lỗ trong biểu đồ vòng tròn (có thể từ 10 đến 90% kích thước vùng vẽ). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300% kích thước mặc định). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300% kích thước mặc định). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Chỉ định định dạng HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. |

### getType() {#getType--}
```
public abstract int getType()
```

Trả về kiểu của nhóm chuỗi này. Chỉ đọc [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Trả về:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Cho biết liệu các chuỗi của nhóm này có được vẽ trên trục phụ hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Trả về một bộ sưu tập chỉ đọc của các chuỗi biểu đồ. Chỉ đọc [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Trả về:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Lấy phần tử tại chỉ mục xác định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Cung cấp quyền truy cập vào thanh tăng/giảm của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Trả về:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi của các kiểu sau: Tất cả các kiểu con thanh và cột, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Trả về:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi của các kiểu sau: Tất cả các kiểu con thanh và cột, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của dấu đánh dấu. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi của các kiểu sau: Các kiểu con thanh và cột 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Trả về:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm độ rộng của dấu đánh dấu. Giá trị phải nằm trong khoảng từ 0 đến 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi của các kiểu sau: Các kiểu con thanh và cột 3D, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Lấy hoặc đặt góc của lát bánh hoặc vòng tròn đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi int.

**Trả về:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Lấy hoặc đặt góc của lát bánh hoặc vòng tròn đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Chỉ định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Trả về:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Chỉ định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ thanh xếp chồng và OfPie. Đọc/ghi boolean.

**Trả về:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ thanh xếp chồng và OfPie. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Chỉ định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hay khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt độ chồng lấn thành 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Chỉ định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hay khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt độ chồng lấn thành 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Chỉ định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc thanh-con-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200%). Đọc/ghi int.

**Trả về:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Chỉ định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh-con-bánh hoặc thanh-con-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200%). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Chỉ định giá trị được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Trả về:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Chỉ định giá trị được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Chỉ định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Trả về:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Chỉ định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-con-bánh hoặc thanh-con-bánh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin tách tùy chỉnh cho biểu đồ bánh-con-bánh hoặc thanh-con-bánh có tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai. Chỉ đọc [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Chỉ định kích thước của lỗ trong biểu đồ vòng tròn (có thể từ 10 đến 90% kích thước vùng vẽ). Đọc/ghi byte.

**Trả về:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Chỉ định kích thước của lỗ trong biểu đồ vòng tròn (có thể từ 10 đến 90% kích thước vùng vẽ). Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300% kích thước mặc định). Đọc/ghi int.

**Trả về:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300% kích thước mặc định). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Chỉ định định dạng HiLowLines. HiLowLines áp dụng cho các kiểu biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose.

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Trả về:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |