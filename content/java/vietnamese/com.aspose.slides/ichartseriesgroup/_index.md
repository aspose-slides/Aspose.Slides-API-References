---
title: IChartSeriesGroup
second_title: Aspose.Slides cho Java Tham chiếu API
description: Đại diện cho nhóm chuỗi.
type: docs
url: /vi/com.aspose.slides/ichartseriesgroup/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Represents group of series.

--------------------

1) See summary and remarks for ChartSeriesGroupCollection class and CombinableSeriesTypesGroup enum. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về một kiểu của nhóm chuỗi này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết nếu chuỗi của nhóm này được vẽ trên trục phụ. |
| [getSeries()](#getSeries--) | Trả về một bộ sưu tập chỉ đọc của các chuỗi biểu đồ. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getUpDownBars()](#getUpDownBars--) | Cung cấp truy cập tới các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. |
| [setGapWidth(int value)](#setGapWidth-int-) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng của dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng của dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lấy hoặc đặt góc của phần bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lấy hoặc đặt góc của phần bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). |
| [isColorVaried()](#isColorVaried--) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Đúng nếu biểu đồ có các đường chuỗi. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Đúng nếu biểu đồ có các đường chuỗi. |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tách tùy chỉnh cho biểu đồ bánh trong bánh hoặc thanh trong bánh có chia tách tùy chỉnh. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 10 tới 90% kích thước khu vực vẽ). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 10 tới 90% kích thước khu vực vẽ). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Xác định định dạng HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. |

### getType() {#getType--}
```
public abstract int getType()
```

Trả về một kiểu của nhóm chuỗi này. Chỉ đọc [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Trả về:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Cho biết nếu chuỗi của nhóm này được vẽ trên trục phụ. Chỉ đọc boolean.

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

Lấy phần tử tại chỉ mục đã chỉ định.

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

Cung cấp truy cập tới các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Trả về:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. Đọc/ghi int.

**Trả về:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm độ rộng của thanh hoặc cột. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng của dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đọc/ghi int.

**Trả về:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng của dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Lấy hoặc đặt góc của phần bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). Đọc/ghi int.

**Trả về:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Lấy hoặc đặt góc của phần bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Trả về:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ cột chồng và OfPie. Đọc/ghi boolean.

**Trả về:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Đúng nếu biểu đồ có các đường chuỗi. Áp dụng cho biểu đồ cột chồng và OfPie. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh đặt cạnh nhau mà không chồng lấn hay có khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt chồng lấn thành 55%
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

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh đặt cạnh nhau mà không chồng lấn hay có khoảng cách. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là đọc/ghi byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Đặt chồng lấn thành 55%
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

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). Đọc/ghi int.

**Trả về:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Trả về:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Trả về:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc thanh trong bánh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ bánh trong bánh hoặc thanh trong bánh có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh. Chỉ đọc [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ donut (có thể từ 10 tới 90% kích thước khu vực vẽ). Đọc/ghi byte.

**Trả về:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Xác định kích thước lỗ trong biểu đồ donut (có thể từ 10 tới 90% kích thước khu vực vẽ). Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đọc/ghi int.

**Trả về:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đọc/ghi int.

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

Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Trả về:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |