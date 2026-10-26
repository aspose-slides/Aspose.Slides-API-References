---
title: ChartSeries
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/chartseries/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Biểu diễn một chuỗi biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Trả về biểu đồ cha. |
| [getExplosion()](#getExplosion--) | Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh tròn được biểu diễn dưới dạng phần trăm của đường kính bánh. |
| [setExplosion(int value)](#setExplosion-int-) | Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh tròn được biểu diễn dưới dạng phần trăm của đường kính bánh. |
| [getSmooth()](#getSmooth--) | Biểu diễn làm mượt đường cong. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Biểu diễn làm mượt đường cong. |
| [getName()](#getName--) | Trả về tên chuỗi. |
| [getDataPoints()](#getDataPoints--) | Trả về tập hợp các điểm dữ liệu của chuỗi này. |
| [getType()](#getType--) | Trả về kiểu của chuỗi này. |
| [setType(int value)](#setType-int-) | Trả về kiểu của chuỗi này. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết chuỗi này có được vẽ trên trục phụ hay không. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Cho biết chuỗi này có được vẽ trên trục phụ hay không. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Trả về định dạng của một chuỗi. |
| [getOrder()](#getOrder--) | Trả về thứ tự của một chuỗi. |
| [setOrder(int value)](#setOrder-int-) | Trả về thứ tự của một chuỗi. |
| [getLabels()](#getLabels--) | Trả về Nhãn của một chuỗi. |
| [getTrendLines()](#getTrendLines--) | Tập hợp các đường xu hướng của chuỗi. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Biểu diễn ErrorBars của chuỗi với hướng X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Biểu diễn ErrorBars của chuỗi với hướng Y. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Biểu diễn mục chú giải liên quan tới chuỗi này Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Xác định chuỗi cột, thanh hoặc bong bóng sẽ đảo màu nếu giá trị là âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Xác định chuỗi cột, thanh hoặc bong bóng sẽ đảo màu nếu giá trị là âm. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Xác định màu đặc đảo cho chuỗi. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Biểu diễn các điểm bên trong. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Biểu diễn các điểm bên trong. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Biểu diễn các điểm ngoại lệ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Biểu diễn các điểm ngoại lệ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Biểu diễn các dấu trung bình. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Biểu diễn các dấu trung bình. |
| [getShowMeanLine()](#getShowMeanLine--) | Biểu diễn đường trung bình. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Biểu diễn đường trung bình. |
| [getQuartileMethod()](#getQuartileMethod--) | Biểu diễn phương pháp phần tư. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Biểu diễn phương pháp phần tư. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Biểu diễn các đường nối. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Biểu diễn các đường nối. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Biểu diễn bố trí các nhãn danh mục cha. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Biểu diễn bố trí các nhãn danh mục cha. |
| [hasUpDownBars()](#hasUpDownBars--) | Xác định biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm cột hoặc thanh, dưới dạng phần trăm của độ rộng cột hoặc thanh. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, dưới dạng phần trăm của độ rộng dấu hiệu, giữa các chuỗi dữ liệu trong biểu đồ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Xác định góc của lát bánh tròn hoặc bánh vòng đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước lỗ trong biểu đồ bánh vòng (có thể từ 10% đến 90% kích thước vùng vẽ). |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng lấn của các cột và thanh trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh tròn hoặc thanh thứ hai trong biểu đồ bánh-in-bánh hoặc thanh-in-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5% đến 200%). |
| [hasSeriesLines()](#hasSeriesLines--) | Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-in-bánh hoặc thanh-in-bánh. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-in-bánh hoặc thanh-in-bánh. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin phân tách tùy chỉnh cho biểu đồ bánh-in-bánh hoặc thanh-in-bánh có phân tách tùy chỉnh. |
| [isColorVaried()](#isColorVaried--) | Xác định mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0% đến 300% kích thước mặc định). |
| [getSlide()](#getSlide--) | Trả về slide cha của FillFormat. |
| [getPresentation()](#getPresentation--) | Trả về bản trình chiếu cha của FillFormat. |

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

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh tròn được biểu diễn dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Trả về:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Khoảng cách của một lát bánh pie mở từ trung tâm của biểu đồ bánh tròn được biểu diễn dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Biểu diễn làm mượt đường cong. True nếu làm mượt đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Chỉ áp dụng cho biểu đồ đường và biểu đồ phân tán được nối bằng đường. Đọc/ghi boolean.

**Trả về:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Biểu diễn làm mượt đường cong. True nếu làm mượt đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Chỉ áp dụng cho biểu đồ đường và biểu đồ phân tán được nối bằng đường. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Trả về tên chuỗi. Chỉ đọc [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Trả về:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ đọc [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Trả về:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public final int getType()
```

Trả về kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Trả về kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

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

ParentSeriesGroup. Chỉ đọc [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Trả về định dạng của một chuỗi. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

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

Trả về Nhãn của một chuỗi. Chỉ đọc [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Trả về:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Tập hợp các đường xu hướng của chuỗi. Chỉ đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines khả dụng (không null) cho các chuỗi dữ liệu trong các biểu đồ khu vực 2-D không chồng, cột, thanh, đường, cổ phiếu, xy (phân tán) và bong bóng. Trendline không khả dụng cho các chuỗi dữ liệu trong bất kỳ loại biểu đồ nào được chồng hoặc 3-D. Trendlines cũng không khả dụng cho các biểu đồ radar, pie, surface, hoặc doughnut.

**Trả về:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Biểu diễn ErrorBars của chuỗi với hướng X. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Biểu diễn ErrorBars của chuỗi với hướng Y. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Biểu diễn mục chú giải liên quan tới chuỗi này Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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

Marker. Chỉ đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. Thay đổi giá trị thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Trả về:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. Thay đổi giá trị thuộc tính này có thể gây tự động thay đổi Type của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Xác định chuỗi cột, thanh hoặc bong bóng sẽ đảo màu nếu giá trị là âm. Đọc/ghi boolean.

**Trả về:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Xác định chuỗi cột, thanh hoặc bong bóng sẽ đảo màu nếu giá trị là âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Xác định màu đặc đảo cho chuỗi. Để áp dụng cài đặt màu, đặt FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [ColorFormat](../../com.aspose.slides/colorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.lang.Integer - The java.lang.Integer object.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Biểu diễn các điểm bên trong. True nếu các điểm bên trong được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Biểu diễn các điểm bên trong. True nếu các điểm bên trong được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Biểu diễn các điểm ngoại lệ. True nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Biểu diễn các điểm ngoại lệ. True nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers 
```

Biểu diễn các dấu trung bình. True nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Biểu diễn các dấu trung bình. True nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Biểu diễn đường trung bình. True nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Biểu diễn đường trung bình. True nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

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

Biểu diễn bố trí các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Trả về:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Biểu diễn bố trí các nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Xác định biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.UpDownBars.HasUpDownBars để thay đổi giá trị. Sử dụng ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Trả về:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Xác định khoảng cách giữa các cụm cột hoặc thanh, dưới dạng phần trăm của độ rộng cột hoặc thanh. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.GapWidth để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapWidth.

**Trả về:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Trả về hoặc đặt khoảng cách, dưới dạng phần trăm của độ rộng dấu hiệu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.GapDepth để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapDepth.

**Trả về:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Xác định góc của lát bánh tròn hoặc bánh vòng đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.FirstSliceAngle để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.FirstSliceAngle.

**Trả về:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ bánh vòng (có thể từ 10% đến 90% kích thước vùng vẽ). Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.DoughnutHoleSize để thay đổi giá trị. Chỉ đọc byte.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.DoughnutHoleSize.

**Trả về:**
byte

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Xác định mức độ chồng lấn của các cột và thanh trên biểu đồ 2D, tính bằng phần trăm (từ -100% đến 100%). Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup. Đây là phép chiếu của thuộc tính phù hợp trong ParentSeriesGroup, vì vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng ParentSeriesGroup.Overlap. Chỉ đọc byte.

--------------------

Overlap xác định mức độ chồng lấn hoặc khoảng cách giữa các cột và thanh dưới dạng phần trăm độ rộng của chúng: -100%: Khoảng cách tối đa (các cột hoàn toàn tách rời). 0%: Các cột đặt cạnh nhau không chồng lấn hay khoảng cách. 100%: Chồng lấn tối đa (các cột hoàn toàn chồng lên nhau). Đây là phép chiếu của thuộc tính ParentSeriesGroup.Overlap.

**Trả về:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Xác định kích thước của bánh tròn hoặc thanh thứ hai trong biểu đồ bánh-in-bánh hoặc thanh-in-bánh, tính bằng phần trăm kích thước của bánh đầu tiên (có thể từ 5% đến 200%). Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.SecondPieSize để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.SecondPieSize.

**Trả về:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.HasSeriesLines để thay đổi giá trị. Sử dụng ParentSeriesGroup.SeriesLinesFormat để định dạng đường chuỗi. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.HasSeriesLines.

**Trả về:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Xác định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.BubbleSizeRepresentation để thay đổi giá trị.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.BubbleSizeRepresentation.

**Trả về:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Xác định giá trị sẽ được sử dụng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-in-bánh hoặc thanh-in-bánh. Được sử dụng cùng với thuộc tính PieSplitBy. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.PieSplitPosition để thay đổi giá trị. Chỉ đọc double.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitPosition.

**Trả về:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Xác định cách để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trên biểu đồ bánh-in-bánh hoặc thanh-in-bánh. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.PieSplitBy để thay đổi giá trị. Chỉ đọc [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitBy. 2) Nếu giá trị thuộc tính là PieSplitType.Custom thì bạn có thể định nghĩa thông tin phân tách tùy chỉnh bằng thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin phân tách tùy chỉnh cho biểu đồ bánh-in-bánh hoặc thanh-in-bánh có phân tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc thanh thứ hai trong biểu đồ bánh-in-bánh hoặc thanh-in-bánh. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Chỉ đọc [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Xác định mỗi dấu dữ liệu trong chuỗi có màu khác nhau. Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.IsColorVaried để thay đổi giá trị. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.IsColorVaried.

**Trả về:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0% đến 300% kích thước mặc định). Thuộc tính này không chỉ của chuỗi này mà của tất cả các chuỗi trong ParentSeriesGroup — đây là phép chiếu của thuộc tính nhóm phù hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng ParentSeriesGroup.BubbleSizeScale để thay đổi giá trị.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.BubbleSizeScale.

**Trả về:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Trả về slide cha của FillFormat. Chỉ đọc [BaseSlide](../../com.aspose.slides/baseslide).

**Trả về:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Trả về bản trình chiếu cha của FillFormat. Chỉ đọc [IPresentation](../../com.aspose.slides/ipresentation).

**Trả về:**
[IPresentation](../../com.aspose.slides/ipresentation)