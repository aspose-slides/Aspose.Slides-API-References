---
title: ChartSeriesGroup
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho một nhóm series.
type: docs
url: /vi/com.aspose.slides/chartseriesgroup/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Biểu diễn một nhóm series.

--------------------

1) Xem tóm tắt và ghi chú cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm series chứa một số thuộc tính series mà chung cho mỗi series trong nhóm ("thuộc tính nhóm series"). "Thuộc tính nhóm series" trong lớp ChartSeriesGroup là đọc/ghi. Mỗi "thuộc tính nhóm series" có thể có một phần chiếu chỉ đọc trong lớp ChartSeries.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về một kiểu của nhóm series này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết series của nhóm này có được vẽ trên trục phụ không. |
| [getSeries()](#getSeries--) | Trả về một tập hợp các series. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [getUpDownBars()](#getUpDownBars--) | Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính theo phần trăm chiều rộng của thanh hoặc cột. |
| [setGapWidth(int value)](#setGapWidth-int-) | Xác định khoảng cách giữa các cụm thanh hoặc cột, tính theo phần trăm chiều rộng của thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc thiết lập khoảng cách, tính theo phần trăm rộng của dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | Trả về hoặc thiết lập khoảng cách, tính theo phần trăm rộng của dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lấy hoặc thiết lập góc của lát bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ hướng lên, từ 0 đến 360 độ). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lấy hoặc thiết lập góc của lát bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ hướng lên, từ 0 đến 360 độ). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 0 đến 90% kích thước của vùng vẽ). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Xác định kích thước lỗ trong biểu đồ donut (có thể từ 0 đến 90% kích thước của vùng vẽ). |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính theo phần trăm (từ -100% tới 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính theo phần trăm (từ -100% tới 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh thứ nhất (có thể từ 5% tới 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh thứ nhất (có thể từ 5% tới 200%). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được hiển thị trên biểu đồ bong bóng. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Xác định cách các giá trị kích thước bong bóng được hiển thị trên biểu đồ bong bóng. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | Xác định rằng mỗi dấu dữ liệu trong series có màu khác nhau. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Xác định rằng mỗi dấu dữ liệu trong series có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Đúng nếu biểu đồ có các đường series. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Đúng nếu biểu đồ có các đường series. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Xác định định dạng HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha của một FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Trả về một kiểu của nhóm series này. Chỉ đọc [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Trả về:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Cho biết series của nhóm này có được vẽ trên trục phụ hay không. Chỉ đọc boolean.

**Trả về:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Trả về một tập hợp các series. Chỉ đọc [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Trả về:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Cung cấp quyền truy cập vào các thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Trả về:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính theo phần trăm chiều rộng của thanh hoặc cột. Đọc/ghi int.

**Trả về:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính theo phần trăm chiều rộng của thanh hoặc cột. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Trả về hoặc thiết lập khoảng cách, tính theo phần trăm rộng của dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. Đọc/ghi int.

**Trả về:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Trả về hoặc thiết lập khoảng cách, tính theo phần trăm rộng của dấu đánh dấu, giữa các series dữ liệu trong biểu đồ 3D. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Lấy hoặc thiết lập góc của lát bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ hướng lên, từ 0 đến 360 độ). Đọc/ghi int.

**Trả về:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Lấy hoặc thiết lập góc của lát bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ hướng lên, từ 0 đến 360 độ). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ donut (có thể từ 0 tới 90% kích thước của vùng vẽ). Đọc/ghi byte.

**Trả về:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Xác định kích thước lỗ trong biểu đồ donut (có thể từ 0 tới 90% kích thước của vùng vẽ). Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính theo phần trăm (từ -100% tới 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hoặc cách nhau. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi byte.

**Trả về:**
byte

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


**Trả về:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2D, tính theo phần trăm (từ -100% tới 100%). - -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). - 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hoặc cách nhau. - 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

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


### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh thứ nhất (có thể từ 5% tới 200%). Đọc/ghi int.

**Trả về:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, tính theo phần trăm kích thước của bánh thứ nhất (có thể từ 5% tới 200%). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Trả về:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Trả về:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Trả về:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Xác định rằng mỗi dấu dữ liệu trong series có màu khác nhau. Đọc/ghi boolean.

**Trả về:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Xác định rằng mỗi dấu dữ liệu trong series có màu khác nhau. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Đúng nếu biểu đồ có các đường series. Áp dụng cho biểu đồ stacked bar và OfPie. Đọc/ghi boolean.

**Trả về:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Đúng nếu biểu đồ có các đường series. Áp dụng cho biểu đồ stacked bar và OfPie. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose.

**Trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đọc/ghi int.

**Trả về:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Chỉ đọc [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)

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

Trả về bản trình chiếu cha của một FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)