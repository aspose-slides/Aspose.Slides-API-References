---
title: ChartSeries
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartseries/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Biểu thị một chuỗi biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getExplosion()](#getExplosion--) | Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. |
| [setExplosion(int value)](#setExplosion-int-) | Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. |
| [getSmooth()](#getSmooth--) | Biểu thị việc làm mượt đường cong. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Biểu thị việc làm mượt đường cong. |
| [getName()](#getName--) | Trả về tên chuỗi. |
| [getDataPoints()](#getDataPoints--) | Trả về tập hợp các điểm dữ liệu của chuỗi này. |
| [getType()](#getType--) | Trả về một kiểu của chuỗi này. |
| [setType(int value)](#setType-int-) | Trả về một kiểu của chuỗi này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết chuỗi này có được vẽ trên trục phụ hay không. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Cho biết chuỗi này có được vẽ trên trục phụ hay không. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Trả về định dạng của một chuỗi. |
| [getOrder()](#getOrder--) | Trả về thứ tự của một chuỗi. |
| [setOrder(int value)](#setOrder-int-) | Trả về thứ tự của một chuỗi. |
| [getLabels()](#getLabels--) | Trả về Nhãn của một chuỗi. |
| [getTrendLines()](#getTrendLines--) | Tập hợp các đường xu hướng của chuỗi. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Biểu thị ErrorBars của chuỗi với hướng X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Biểu thị ErrorBars của chuỗi với hướng Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Biểu thị mục chú giải liên quan đến chuỗi này Chỉ-đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Xác định hình dạng của một chuỗi trong biểu đồ thanh 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Xác định hình dạng của một chuỗi trong biểu đồ thanh 3-D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Xác định chuỗi thanh, cột hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Xác định chuỗi thanh, cột hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Xác định màu nền đặc đảo ngược cho chuỗi. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Biểu thị các điểm bên trong. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Biểu thị các điểm bên trong. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Biểu thị các điểm ngoại lệ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Biểu thị các điểm ngoại lệ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Biểu thị các dấu hiệu trung bình. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Biểu thị các dấu hiệu trung bình. |
| [getShowMeanLine()](#getShowMeanLine--) | Biểu thị đường trung bình. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Biểu thị đường trung bình. |
| [getQuartileMethod()](#getQuartileMethod--) | Biểu thị phương pháp tứ phân vị. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Biểu thị phương pháp tứ phân vị. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Biểu thị các đường nối. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Biểu thị các đường nối. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Biểu thị bố cục của nhãn danh mục cha. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Biểu thị bố cục của nhãn danh mục cha. |
| [hasUpDownBars()](#hasUpDownBars--) | Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm thanh hoặc cột, dưới dạng phần trăm của chiều rộng thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, dưới dạng phần trăm của chiều rộng dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Xác định góc của lát bánh hoặc vòng donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước của lỗ trong biểu đồ donut (có thể từ 10 đến 90 phần trăm kích thước của vùng vẽ). |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng lắp của các thanh và cột trên biểu đồ 2-D, dưới dạng phần trăm (từ -100% đến 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ pie-of-pie hoặc bar-of-pie, dưới dạng phần trăm kích thước của bánh đầu tiên (có thể từ 5 đến 200 phần trăm). |
| [hasSeriesLines()](#hasSeriesLines--) | Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định một giá trị sẽ được sử dụng để xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách xác định các điểm dữ liệu nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie với phân chia tùy chỉnh. |
| [isColorVaried()](#isColorVaried--) | Xác định mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỉ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 phần trăm kích thước mặc định). |
| [getSlide()](#getSlide--) | Trả về slide cha của một FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình bày cha của một FillFormat. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Trả về biểu đồ cha. Chỉ-đọc [IChart](../../com.aspose.slides/ichart).

**Trả về:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Trả về:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Biểu thị việc làm mượt đường cong. Đúng nếu việc làm mượt đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Áp dụng chỉ cho các biểu đồ đường và phân tán nối bằng đường. Đọc/ghi boolean.

**Trả về:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Biểu thị việc làm mượt đường cong. Đúng nếu việc làm mượt đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Áp dụng chỉ cho các biểu đồ đường và phân tán nối bằng đường. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Trả về tên chuỗi. Chỉ-đọc [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Trả về:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ-đọc [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Trả về:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Trả về một kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Trả về một kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Cho biết chuỗi này có được vẽ trên trục phụ hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Cho biết chuỗi này có được vẽ trên trục phụ hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Chỉ-đọc [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Trả về định dạng của một chuỗi. Chỉ-đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Trả về thứ tự của một chuỗi. Đọc/ghi int.

**Trả về:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Trả về thứ tự của một chuỗi. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Trả về Nhãn của một chuỗi. Chỉ-đọc [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Trả về:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Tập hợp các đường xu hướng của chuỗi. Chỉ-đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines có sẵn (không null) cho các chuỗi dữ liệu trong các biểu đồ khu vực, thanh, cột, đường, cổ phiếu, xy (phân tán) và bong bóng không chồng lớp 2-D. TrendLines không có sẵn cho các chuỗi dữ liệu trong bất kỳ loại biểu đồ nào được chồng lớp hoặc 3-D. TrendLines cũng không có sẵn cho các biểu đồ radar, bánh, bề mặt hoặc donut.

**Trả về:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Biểu thị ErrorBars của chuỗi với hướng X. Chỉ-đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng X có sẵn cho các chuỗi loại khu vực, thanh, phân tán và bong bóng. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Biểu thị ErrorBars của chuỗi với hướng Y. Chỉ-đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng Y có sẵn cho các chuỗi loại khu vực, thanh, đường, phân tán và bong bóng. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Biểu thị mục chú giải liên quan đến chuỗi này Chỉ-đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Đọc/ghi String.

**Trả về:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Đọc/ghi String.

**Trả về:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Đọc/ghi String.

**Trả về:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberFormatOfYValues(String value)
```

NumberFormatOfYValues. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Đọc/ghi String.

**Trả về:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Chỉ-đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Xác định hình dạng của một chuỗi trong biểu đồ thanh 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Trả về:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Xác định hình dạng của một chuỗi trong biểu đồ thanh 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Xác định chuỗi thanh, cột hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi boolean.

**Trả về:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Xác định chuỗi thanh, cột hoặc bong bóng sẽ đảo ngược màu nếu giá trị là âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Specifies invert solid color for series. To apply color setting set series format FillType to FillType.Solid. Đọc/ghi [ColorFormat](../../com.aspose.slides/colorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Trả về một màu tự động của series dựa trên chỉ mục series và kiểu chart. Màu này được sử dụng theo mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.awt.Color - Đối tượng java.awt.Color.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Biểu diễn các điểm nội bộ. Đúng nếu các điểm nội bộ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Biểu diễn các điểm nội bộ. Đúng nếu các điểm nội bộ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Biểu diễn các dấu trung bình. Đúng nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Biểu diễn các dấu trung bình. Đúng nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Biểu diễn đường trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Biểu diễn đường trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Biểu diễn phương pháp phần tư. Chỉ áp dụng cho biểu đồ BoxAndWhisker.

**Trả về:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Biểu diễn phương pháp phần tư. Chỉ áp dụng cho biểu đồ BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Biểu diễn các đường nối. Chỉ áp dụng cho biểu đồ Waterfall.

**Trả về:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Biểu diễn các đường nối. Chỉ áp dụng cho biểu đồ Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Biểu diễn bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Trả về:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Biểu diễn bố cục của các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Xác định liệu biểu đồ Line hoặc Stock có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars để đọc/ghi giá trị thay đổi. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng các thanh lên/xuống. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Trả về:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Xác định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm của chiều rộng thanh hoặc cột. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth để đọc/ghi giá trị thay đổi. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapWidth.

**Trả về:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm của chiều rộng marker, giữa các series dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth để đọc/ghi giá trị thay đổi. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapDepth.

**Trả về:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Xác định góc của lát cốt bánh hoặc bánh rác đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle để đọc/ghi giá trị thay đổi. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.FirstSliceAngle.

**Trả về:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ doughnut (có thể từ 10 đến 90 phần trăm kích thước vùng vẽ). Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize để đọc/ghi giá trị thay đổi. Chỉ đọc byte.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.DoughnutHoleSize.

**Trả về:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Xác định mức độ chồng lấn của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% đến 100%). Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup. Nó là phép chiếu của thuộc tính tương ứng trong ParentSeriesGroup, và do đó thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính ParentSeriesGroup.Overlap đọc/ghi. Chỉ đọc byte.

--------------------

Overlap xác định mức độ chồng lấn hoặc khoảng cách giữa các thanh và cột dưới dạng phần trăm của chiều rộng: -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). 0%: Các thanh được đặt cạnh nhau mà không chồng lấn hay khoảng cách. 100%: Chồng lấn tối đa (các thanh hoàn toàn chồng lên nhau). Đây là phép chiếu của thuộc tính ParentSeriesGroup.Overlap.

**Trả về:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Xác định kích thước của bánh hoặc thanh thứ hai của biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của bánh thứ nhất (có thể từ 5 đến 200 phần trăm). Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize để đọc/ghi giá trị thay đổi. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.SecondPieSize.

**Trả về:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Xác định liệu có các đường series cho series này và các series liên quan hay không. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines để đọc/ghi giá trị thay đổi. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng các đường series. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.HasSeriesLines.

**Trả về:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bubble. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation để đọc/ghi giá trị thay đổi.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.BubbleSizeRepresentation.

**Trả về:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Xác định một giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition để đọc/ghi giá trị thay đổi. Chỉ đọc double.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitPosition.

**Trả về:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Do đó thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy để đọc/ghi giá trị thay đổi. Chỉ đọc [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitBy. 2) Nếu giá trị thuộc tính là PieSplitType.Custom thì bạn có thể định nghĩa thông tin chia tách tùy chỉnh bằng thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie với chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của series này mà của tất cả các series trong ParentSeriesGroup - đây là phép chiếu của thuộc tính nhóm tương ứng. Chỉ đọc [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Specifies that each data marker in the series has a different color. This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.IsColorVaried read/write property for change value. Read-only boolean.

--------------------

This is the projection of the property ParentSeriesGroup.IsColorVaried.

**Trả về:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). This is the property not only of this series but of all series of parent series group - this is projection of appropriate group property. And so this property is read-only. Use ParentSeriesGroup property for access to parent series group. Use ParentSeriesGroup.BubbleSizeScale read/write property for change value.

--------------------

This is the projection of the property ParentSeriesGroup.BubbleSizeScale.

**Trả về:**
int
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returns the parent slide of a FillFormat. Read-only [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returns the parent presentation of a FillFormat. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)