---
title: IChartSeriesGroup
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn nhóm các series.
type: docs
url: /vi/com.aspose.slides/ichartseriesgroup/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Biểu diễn nhóm các series.

--------------------

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm series chứa một số thuộc tính series chung cho mỗi series trong nhóm ("series group properties"). "Series group properties" trong lớp ChartSeriesGroup là đọc/ghi. Mỗi "series group properties" có thể có một phép chiếu chỉ đọc trong lớp ChartSeries.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về một kiểu của nhóm series này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết series của nhóm này có được vẽ trên trục thứ cấp hay không. |
| [getSeries()](#getSeries--) | Trả về một bộ sưu tập chỉ đọc của các series biểu đồ. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số được chỉ định. |
| [getUpDownBars()](#getUpDownBars--) | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Line hoặc Stock. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. |
| [setGapWidth(int value)](#setGapWidth-int-) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lấy hoặc đặt góc của lát bánh pie hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lấy hoặc đặt góc của lát bánh pie hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [isColorVaried()](#isColorVaried--) | Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | True nếu biểu đồ có đường series. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True nếu biểu đồ có đường series. |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng chéo của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Xác định mức độ chồng chéo của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của pie đầu tiên (có thể từ 5 đến 200 phần trăm). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Xác định kích thước của pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của pie đầu tiên (có thể từ 5 đến 200 phần trăm). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Xác định cách quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước của lỗ trong biểu đồ doughnut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Xác định kích thước của lỗ trong biểu đồ doughnut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bubble (có thể từ 0 đến 300 phần trăm kích thước mặc định). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Xác định hệ số tỷ lệ cho biểu đồ bubble (có thể từ 0 đến 300 phần trăm kích thước mặc định). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Xác định định dạng HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble. |

### getType() {#getType--}
```
public abstract int getType()
```

Trả về một kiểu của nhóm series này. Read-only [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Trả về:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Cho biết series của nhóm này có được vẽ trên trục thứ cấp hay không. Read-only boolean.

**Trả về:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Trả về một bộ sưu tập chỉ đọc của các series biểu đồ. Read-only [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Trả về:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Lấy phần tử tại chỉ số được chỉ định.

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

Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Line hoặc Stock. Read-only [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Trả về:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. Read/write int.

**Trả về:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. Read/write int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. Read/write int.

**Trả về:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. Read/write int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Lấy hoặc đặt góc của lát bánh pie hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Read/write int.

**Trả về:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Lấy hoặc đặt góc của lát bánh pie hoặc doughnut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Read/write int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. Read/write boolean.

**Trả về:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. Read/write boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

True nếu biểu đồ có đường series. Áp dụng cho stacked bar và OfPie charts. Read/write boolean.

**Trả về:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

True nếu biểu đồ có đường series. Áp dụng cho stacked bar và OfPie charts. Read/write boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Xác định mức độ chồng chéo của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách ra). - 0%: Các thanh đặt cạnh nhau mà không chồng chéo hay khoảng cách. - 100%: Chồng chéo tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt overlap thành 55%
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

Xác định mức độ chồng chéo của thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách ra). - 0%: Các thanh đặt cạnh nhau mà không chồng chéo hay khoảng cách. - 100%: Chồng chéo tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt overlap thành 55%
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

Xác định kích thước của pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của pie đầu tiên (có thể từ 5 đến 200 phần trăm). Read/write int.

**Trả về:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Xác định kích thước của pie hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của pie đầu tiên (có thể từ 5 đến 200 phần trăm). Read/write int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Read/write double.

**Trả về:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Read/write double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Trả về:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong pie hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Read/write [PieSplitType](../../com.aspose.slides/piesplittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong pie hoặc thanh thứ hai. Read-only [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Xác định kích thước của lỗ trong biểu đồ doughnut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). Read/write byte.

**Trả về:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Xác định kích thước của lỗ trong biểu đồ doughnut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). Read/write byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bubble (có thể từ 0 đến 300 phần trăm kích thước mặc định). Read/write int.

**Trả về:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Xác định hệ số tỷ lệ cho biểu đồ bubble (có thể từ 0 đến 300 phần trăm kích thước mặc định). Read/write int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose.

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Trả về:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble. Read/write [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |