---
title: ChartSeriesGroup
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho nhóm chuỗi.
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

Đại diện cho nhóm chuỗi.

--------------------

1) Xem tóm tắt và chú thích cho lớp ChartSeriesGroupCollection và enum CombinableSeriesTypesGroup. 2) Nhóm chuỗi chứa một số thuộc tính chuỗi chung cho mỗi chuỗi trong nhóm ("thuộc tính nhóm chuỗi"). "Thuộc tính nhóm chuỗi" trong lớp ChartSeriesGroup là đọc/ghi. Mỗi "thuộc tính nhóm chuỗi" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getType()](#getType--) | Trả về kiểu của nhóm chuỗi này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết liệu chuỗi của nhóm này có được vẽ trên trục phụ hay không. |
| [getSeries()](#getSeries--) | Trả về một tập hợp các chuỗi. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [getUpDownBars()](#getUpDownBars--) | Cung cấp quyền truy cập vào thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. |
| [getGapWidth()](#getGapWidth--) | Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. |
| [setGapWidth(int value)](#setGapWidth-int-) | Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm của chiều rộng dấu đánh dấu. |
| [setGapDepth(int value)](#setGapDepth-int-) | Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm của chiều rộng dấu đánh dấu. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Lấy hoặc đặt góc của lát bánh hoặc vòng bánh đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Lấy hoặc đặt góc của lát bánh hoặc vòng bánh đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước lỗ trong biểu đồ vòng bánh (có thể từ 0 tới 90% kích thước vùng vẽ). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Xác định kích thước lỗ trong biểu đồ vòng bánh (có thể từ 0 tới 90% kích thước vùng vẽ). |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc bánh trong thanh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc bánh trong thanh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. |
| [isColorVaried()](#isColorVaried--) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Đúng nếu biểu đồ có đường chuỗi. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Đúng nếu biểu đồ có đường chuỗi. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Xác định định dạng HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin phân tách tùy chỉnh cho biểu đồ bánh trong bánh hoặc bánh trong thanh có phân tách tùy chỉnh. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getSlide()](#getSlide--) | Trả về slide cha của FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

Trả về kiểu của nhóm chuỗi này. Chỉ đọc [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Giá trị trả về:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Cho biết liệu chuỗi của nhóm này có được vẽ trên trục phụ hay không. Chỉ đọc boolean.

**Giá trị trả về:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Trả về một tập hợp các chuỗi. Chỉ đọc [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Giá trị trả về:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Cung cấp quyền truy cập vào thanh lên/xuống của biểu đồ Đường hoặc Cổ phiếu. Chỉ đọc [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Giá trị trả về:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. Giá trị phải nằm trong khoảng từ 0 tới 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi thuộc các loại sau: các kiểu phụ Bar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), các kiểu phụ Column (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Giá trị trả về:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Lấy hoặc đặt khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. Giá trị phải nằm trong khoảng từ 0 tới 500. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

--------------------

Thuộc tính này áp dụng cho các chuỗi thuộc các loại sau: các kiểu phụ Bar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)), các kiểu phụ Column (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-)), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm của chiều rộng dấu đánh dấu. Giá trị phải nằm trong khoảng từ 0 tới 500. Đọc/ghi int.

--------------------

Thuộc tính này áp dụng cho các chuỗi thuộc các loại sau: các kiểu phụ bar 3D và column 3D (xem thêm phương thức [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Giá trị trả về:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Lấy hoặc đặt khoảng cách giữa các chuỗi dữ liệu trong biểu đồ 3D, tính bằng phần trăm của chiều rộng dấu đánh dấu. Giá trị phải nằm trong khoảng từ 0 tới 500. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

--------------------

Thuộc tính này áp dụng cho các chuỗi thuộc các loại sau: các kiểu phụ bar 3D và column 3D (xem thêm phương thức [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-)), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Lấy hoặc đặt góc của lát bánh hoặc vòng bánh đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). Đọc/ghi int.

**Giá trị trả về:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Lấy hoặc đặt góc của lát bánh hoặc vòng bánh đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ vòng bánh (có thể từ 0 tới 90% kích thước vùng vẽ). Đọc/ghi byte.

**Giá trị trả về:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Xác định kích thước lỗ trong biểu đồ vòng bánh (có thể từ 0 tới 90% kích thước vùng vẽ). Đọc/ghi byte.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). -0%: Các thanh đặt cạnh nhau không chồng lấn hoặc có khoảng cách. 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi byte.

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


**Giá trị trả về:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). -0%: Các thanh đặt cạnh nhau không chồng lấn hoặc có khoảng cách. 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Thuộc tính này là Đọc/ghi byte.

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
public final int getSecondPieSize()
```

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc bánh trong thanh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). Đọc/ghi int.

**Giá trị trả về:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc bánh trong thanh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5 tới 200%). Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Giá trị trả về:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đọc/ghi [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Giá trị trả về:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Xác định một giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. Được sử dụng cùng với thuộc tính PieSplitBy. Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Giá trị trả về:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh trong bánh hoặc bánh trong thanh. Đọc/ghi [PieSplitType](../../com.aspose.slides/piesplittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Giá trị trả về:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Đúng nếu biểu đồ có đường chuỗi. Áp dụng cho các biểu đồ stacked bar và OfPie. Đọc/ghi boolean.

**Giá trị trả về:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Đúng nếu biểu đồ có đường chuỗi. Áp dụng cho các biểu đồ stacked bar và OfPie. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Xác định định dạng HiLowLines. HiLowLines được áp dụng với các loại biểu đồ HiLowClose, OpenHiLowClose, VolumeHiLowClose và VolumeOpenHiLowClose.

**Giá trị trả về:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đọc/ghi int.

**Giá trị trả về:**
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

Thông tin phân tách tùy chỉnh cho biểu đồ bánh trong bánh hoặc bánh trong thanh có phân tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai. Chỉ đọc [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Giá trị trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Giá trị trả về:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ đọc [IChart](../../com.aspose.slides/ichart).

**Giá trị trả về:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Giá trị trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình bày cha của FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Giá trị trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)