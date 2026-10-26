---
title: IChartSeries
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartseries/
---
**All Implemented Interfaces:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Biểu diễn một chuỗi biểu đồ.
## Phương thức

| Method | Description |
| --- | --- |
| [getExplosion()](#getExplosion--) | Khoảng cách của một miếng bánh mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. |
| [setExplosion(int value)](#setExplosion-int-) | Khoảng cách của một miếng bánh mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. |
| [getSmooth()](#getSmooth--) | Biểu diễn việc làm mịn đường cong. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Biểu diễn việc làm mịn đường cong. |
| [getMarker()](#getMarker--) | Trả về dấu đánh dấu của chuỗi. |
| [getBar3DShape()](#getBar3DShape--) | Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. |
| [getName()](#getName--) | Trả về tên chuỗi. |
| [getDataPoints()](#getDataPoints--) | Trả về tập hợp các điểm dữ liệu của chuỗi này. |
| [getType()](#getType--) | Trả về một kiểu của chuỗi này. |
| [setType(int value)](#setType-int-) | Trả về một kiểu của chuỗi này. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Trả về nhóm chuỗi cha. |
| [getFormat()](#getFormat--) | Trả về định dạng của một chuỗi. |
| [getOrder()](#getOrder--) | Trả về thứ tự của một chuỗi. |
| [setOrder(int value)](#setOrder-int-) | Trả về thứ tự của một chuỗi. |
| [getLabels()](#getLabels--) | Trả về các Nhãn của một chuỗi. |
| [getTrendLines()](#getTrendLines--) | Tập hợp các đường xu hướng của chuỗi. Chỉ đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Biểu diễn ErrorBars của chuỗi với hướng X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Biểu diễn ErrorBars của chuỗi với hướng Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Chỉ ra nếu chuỗi này được vẽ trên trục giá trị thứ hai. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Chỉ ra nếu chuỗi này được vẽ trên trục giá trị thứ hai. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Trả về hoặc đặt định dạng số cho các giá trị của chuỗi. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị của chuỗi. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Trả về hoặc đặt định dạng số cho các giá trị x của chuỗi. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị x của chuỗi. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Trả về hoặc đặt định dạng số cho các giá trị y của chuỗi. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị y của chuỗi. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Xác định rằng cột, thanh hoặc chuỗi bong bóng sẽ đổi màu nếu giá trị là âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Xác định rằng cột, thanh hoặc chuỗi bong bóng sẽ đổi màu nếu giá trị là âm. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Xác định màu nền đặc bị đảo ngược cho chuỗi. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Biểu diễn mục chú giải liên quan đến chuỗi này. Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Trả về màu tự động của chuỗi dựa trên chỉ mục chuỗi và kiểu biểu đồ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Biểu diễn các điểm bên trong. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Biểu diễn các điểm bên trong. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Biểu diễn các điểm ngoại lệ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Biểu diễn các điểm ngoại lệ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Biểu diễn các dấu trung bình. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Biểu diễn các dấu trung bình. |
| [getShowMeanLine()](#getShowMeanLine--) | Biểu diễn các dấu trung bình. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Biểu diễn các dấu trung bình. |
| [getQuartileMethod()](#getQuartileMethod--) | Biểu diễn phương pháp tứ phân vị. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Biểu diễn phương pháp tứ phân vị. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Biểu diễn các đường kết nối. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Biểu diễn các đường kết nối. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Biểu diễn bố cục của các nhãn danh mục cha. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Biểu diễn bố cục của các nhãn danh mục cha. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể nằm trong khoảng 0 đến 300% của kích thước mặc định). |
| [hasUpDownBars()](#hasUpDownBars--) | Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. |
| [getGapWidth()](#getGapWidth--) | Xác định khoảng cách giữa các cụm cột hoặc thanh, dưới dạng phần trăm của độ rộng cột hoặc thanh. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, dưới dạng phần trăm của độ rộng dấu đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. |
| [isColorVaried()](#isColorVaried--) | Xác định rằng mỗi dấu dữ liệu trong chuỗi có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Xác định liệu có đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. |
| [getOverlap()](#getOverlap--) | Xác định mức độ chồng chéo của các cột và thanh trên biểu đồ 2D, dưới dạng phần trăm (từ -100% đến 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Xác định kích thước của bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh, dưới dạng phần trăm của kích thước bánh đầu tiên (có thể từ 5 đến 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Xác định giá trị sẽ được dùng để quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [getPieSplitBy()](#getPieSplitBy--) | Xác định cách quyết định các điểm dữ liệu nào nằm trong bánh hoặc thanh thứ hai trong biểu đồ bánh trong bánh hoặc thanh trong bánh. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Xác định kích thước của lỗ trong biểu đồ vòng (có thể từ 10 đến 90% của kích thước khu vực vẽ). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Xác định góc của miếng bánh hoặc vòng đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tùy chỉnh cho biểu đồ bánh trong bánh hoặc thanh trong bánh với cách chia tùy chỉnh. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Khoảng cách của một miếng bánh mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Trả về:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Khoảng cách của một miếng bánh mở từ trung tâm của biểu đồ bánh được biểu thị dưới dạng phần trăm của đường kính bánh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Biểu diễn việc làm mịn đường cong. True nếu việc làm mịn đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Chỉ áp dụng cho biểu đồ đường và biểu đồ phân tán được nối bằng các đường. Đọc/ghi boolean.

**Trả về:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Biểu diễn việc làm mịn đường cong. True nếu việc làm mịn đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Chỉ áp dụng cho biểu đồ đường và biểu đồ phân tán được nối bằng các đường. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Trả về dấu đánh dấu của chuỗi. Chỉ đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Trả về:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Xác định hình dạng của một chuỗi trong biểu đồ cột 3D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của chuỗi. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Trả về tên chuỗi. Chỉ đọc [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Trả về:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Trả về tập hợp các điểm dữ liệu của chuỗi này. Chỉ đọc [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Trả về:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Trả về một kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Trả về một kiểu của chuỗi này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Trả về nhóm chuỗi cha. Chỉ đọc [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Trả về định dạng của một chuỗi. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Trả về thứ tự của một chuỗi. Đọc/ghi int.

**Trả về:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Trả về thứ tự của một chuỗi. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Trả về các Nhãn của một chuỗi. Chỉ đọc [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Trả về:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Tập hợp các đường xu hướng của chuỗi. Chỉ đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Trả về:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Biểu diễn ErrorBars của chuỗi với hướng X. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars có hướng X khả dụng cho các chuỗi loại area, bar, scatter và bubble. Đối với bất kỳ loại biểu đồ nào khác, thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Trong trường hợp sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Biểu diễn ErrorBars của chuỗi với hướng Y. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars có hướng Y khả dụng cho các chuỗi loại area, bar, line, scatter và bubble. Đối với bất kỳ loại biểu đồ nào khác, thuộc tính này trả về null (bao gồm cả biểu đồ 3D). Trong trường hợp sử dụng giá trị tùy chỉnh, hãy dùng tập hợp DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Chỉ ra nếu chuỗi này được vẽ trên trục giá trị thứ hai. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Chỉ ra nếu chuỗi này được vẽ trên trục giá trị thứ hai. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Trả về hoặc đặt định dạng số cho các giá trị của chuỗi. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị của chuỗi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Trả về hoặc đặt định dạng số cho các giá trị x của chuỗi. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị x của chuỗi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Trả về hoặc đặt định dạng số cho các giá trị y của chuỗi. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị y của chuỗi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Trả về hoặc đặt định dạng số cho kích thước bong bóng của chuỗi. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Xác định rằng cột, thanh hoặc chuỗi bong bóng sẽ đổi màu nếu giá trị là âm. Đọc/ghi boolean.

**Trả về:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Xác định rằng cột, thanh hoặc chuỗi bong bóng sẽ đổi màu nếu giá trị là âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Xác định màu nền đặc bị đảo ngược cho chuỗi. Để áp dụng cài đặt màu, hãy đặt thuộc tính FillType của định dạng chuỗi thành FillType.Solid. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Biểu diễn mục chú giải liên quan đến chuỗi này. Chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Trả về một màu tự động của chuỗi dựa trên chỉ số chuỗi và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.awt.Color - Màu tự động của chuỗi java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Biểu thị các điểm nội. True nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Biểu thị các điểm nội. True nếu các điểm nội được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Biểu thị các điểm ngoại lệ. True nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Biểu thị các điểm ngoại lệ. True nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Biểu thị các điểm trung bình. True nếu các điểm trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Biểu thị các điểm trung bình. True nếu các điểm trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Biểu thị các điểm trung bình. True nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Biểu thị các điểm trung bình. True nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Chỉ áp dụng cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Biểu thị phương pháp phần tư. Chỉ áp dụng cho biểu đồ BoxAndWhisker.

**Trả về:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Biểu thị phương pháp phần tư. Chỉ áp dụng cho biểu đồ BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Biểu thị các đường kết nối. Chỉ áp dụng cho biểu đồ Waterfall.

**Trả về:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Biểu thị các đường kết nối. Chỉ áp dụng cho biểu đồ Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Biểu thị bố cục nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Trả về:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Biểu thị bố cục nhãn danh mục cha. Chỉ áp dụng cho biểu đồ Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Xác định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 đến 300 % kích thước mặc định). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeScale Đọc/ghi để thay đổi giá trị.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.BubbleSizeScale.

**Trả về:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Xác định liệu biểu đồ Line hoặc Stock có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Trả về:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Xác định khoảng cách giữa các cụm cột hoặc thanh, dưới dạng phần trăm của chiều rộng cột hoặc thanh. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapWidth Đọc/ghi để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapWidth.

**Trả về:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Trả về hoặc đặt khoảng cách, dưới dạng phần trăm của chiều rộng đánh dấu, giữa các chuỗi dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.GapDepth Đọc/ghi để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.GapDepth.

**Trả về:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Xác định mỗi điểm dữ liệu trong chuỗi có màu khác nhau. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.IsColorVaried Đọc/ghi để thay đổi giá trị. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.IsColorVaried.

**Trả về:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Xác định liệu có các đường chuỗi cho chuỗi này và các chuỗi liên quan hay không. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.HasSeriesLines Đọc/ghi để thay đổi giá trị. Sử dụng thuộc tính ParentSeriesGroup.SeriesLinesFormat để định dạng các đường chuỗi. Chỉ đọc boolean.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.HasSeriesLines.

**Trả về:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Xác định mức độ chồng lấp của các thanh và cột trên biểu đồ 2-D, dưới dạng phần trăm (từ -100 % đến 100 %). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha. Nó là phép chiếu của thuộc tính tương ứng trong nhóm chuỗi cha, vì vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, sử dụng thuộc tính ParentSeriesGroup.Overlap Đọc/ghi. Chỉ đọc byte.

--------------------

Overlap xác định mức độ chồng lấp hoặc khoảng cách giữa các thanh và cột dưới dạng phần trăm chiều rộng của chúng: -100 %: Khoảng cách tối đa (các thanh hoàn toàn tách rời). 0 %: Các thanh được đặt cạnh nhau mà không chồng lấp hay khoảng cách. 100 %: Chồng lấp tối đa (các thanh hoàn toàn chồng lên nhau). Đây là phép chiếu của thuộc tính ParentSeriesGroup.Overlap.

**Trả về:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Xác định kích thước của bánh hoặc cột thứ hai của biểu đồ pie-of-pie hoặc bar-of-pie, dưới dạng phần trăm của kích thước bánh thứ nhất (có thể từ 5 đến 200 %). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.SecondPieSize Đọc/ghi để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.SecondPieSize.

**Trả về:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Xác định giá trị sẽ được sử dụng để quyết định dữ liệu nào nằm trong bánh hoặc cột thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitPosition Đọc/ghi để thay đổi giá trị. Chỉ đọc double.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitPosition.

**Trả về:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Xác định cách quyết định dữ liệu nào nằm trong bánh hoặc cột thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.PieSplitBy Đọc/ghi để thay đổi giá trị. Chỉ đọc [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitBy. 2) Nếu giá trị thuộc tính là PieSplitType.Custom thì bạn có thể định nghĩa thông tin chia tách tùy chỉnh bằng thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Xác định kích thước lỗ trong biểu đồ vòng donut (có thể từ 10 đến 90 % kích thước vùng vẽ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.DoughnutHoleSize Đọc/ghi để thay đổi giá trị. Chỉ đọc byte.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.DoughnutHoleSize.

**Trả về:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Xác định góc của lát bánh hoặc donut đầu tiên, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 đến 360 độ). Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.FirstSliceAngle Đọc/ghi để thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.FirstSliceAngle.

**Trả về:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie với chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong bánh hoặc cột thứ hai trên biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của chuỗi này mà của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Chỉ đọc [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Xác định cách các giá trị kích thước bong bóng được biểu thị trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của chuỗi này mà còn của tất cả các chuỗi trong nhóm chuỗi cha - đây là phép chiếu của thuộc tính nhóm tương ứng. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm chuỗi cha. Sử dụng thuộc tính ParentSeriesGroup.BubbleSizeRepresentation đọc/ghi để thay đổi giá trị.

--------------------

Đây là phép chiếu của thuộc tính ParentSeriesGroup.BubbleSizeRepresentation.

**Trả về:**  
int