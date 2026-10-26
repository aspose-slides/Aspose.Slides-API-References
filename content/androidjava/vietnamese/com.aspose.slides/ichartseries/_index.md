---
title: IChartSeries
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn một chuỗi biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartseries/
---
**Tất cả các giao diện đã thực hiện:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Biểu diễn một chuỗi biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getExplosion()](#getExplosion--) | Khoảng cách của một lát bánh mở so với tâm biểu đồ bánh được biểu thị dưới dạng phần trăm của độ kính bánh. |
| [setExplosion(int value)](#setExplosion-int-) | Khoảng cách của một lát bánh mở so với tâm biểu đồ bánh được biểu thị dưới dạng phần trăm của độ kính bánh. |
| [getSmooth()](#getSmooth--) | Biểu diễn việc làm mịn đường cong. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Biểu diễn việc làm mịn đường cong. |
| [getMarker()](#getMarker--) | Trả về dấu series. |
| [getBar3DShape()](#getBar3DShape--) | Chỉ định hình dạng của một series của biểu đồ thanh 3-D. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Chỉ định hình dạng của một series của biểu đồ thanh 3-D. |
| [getName()](#getName--) | Trả về tên series. |
| [getDataPoints()](#getDataPoints--) | Trả về bộ sưu tập các điểm dữ liệu của series này. |
| [getType()](#getType--) | Trả về một kiểu của series này. |
| [setType(int value)](#setType-int-) | Trả về một kiểu của series này. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Trả về nhóm series cha. |
| [getFormat()](#getFormat--) | Trả về định dạng của một series. |
| [getOrder()](#getOrder--) | Trả về thứ tự của một series. |
| [setOrder(int value)](#setOrder-int-) | Trả về thứ tự của một series. |
| [getLabels()](#getLabels--) | Trả về các Nhãn của một series. |
| [getTrendLines()](#getTrendLines--) | Bộ sưu tập các đường xu hướng series, chỉ đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Biểu diễn ErrorBars của series với hướng X. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Biểu diễn ErrorBars của series với hướng Y. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Cho biết nếu series này được vẽ trên trục giá trị thứ hai. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Cho biết nếu series này được vẽ trên trục giá trị thứ hai. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Trả về hoặc đặt định dạng số cho các giá trị của series. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị của series. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Trả về hoặc đặt định dạng số cho các giá trị x của series. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị x của series. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Trả về hoặc đặt định dạng số cho các giá trị y của series. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Trả về hoặc đặt định dạng số cho các giá trị y của series. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Trả về hoặc đặt định dạng số cho kích thước bong bóng của series. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Trả về hoặc đặt định dạng số cho kích thước bong bóng của series. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Chỉ định series dạng thanh, cột hoặc bong bóng sẽ đảo màu nếu giá trị là âm. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Chỉ định series dạng thanh, cột hoặc bong bóng sẽ đảo màu nếu giá trị là âm. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Chỉ định màu nền đặc đảo cho series. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Biểu diễn mục chú giải liên quan tới series này, chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Trả về một màu tự động của series dựa trên chỉ mục series và kiểu biểu đồ. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Biểu diễn các điểm nội bộ. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Biểu diễn các điểm nội bộ. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Biểu diễn các điểm ngoại lệ. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Biểu diễn các điểm ngoại lệ. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Biểu diễn các dấu trung bình. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Biểu diễn các dấu trung bình. |
| [getShowMeanLine()](#getShowMeanLine--) | Biểu diễn các dấu trung bình. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Biểu diễn các dấu trung bình. |
| [getQuartileMethod()](#getQuartileMethod--) | Biểu diễn phương pháp phần tư. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Biểu diễn phương pháp phần tư. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Biểu diễn các đường kết nối. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Biểu diễn các đường kết nối. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Biểu diễn bố cục của các nhãn danh mục cha. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Biểu diễn bố cục của các nhãn danh mục cha. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). |
| [hasUpDownBars()](#hasUpDownBars--) | Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. |
| [getGapWidth()](#getGapWidth--) | Chỉ định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm chiều rộng thanh hoặc cột. |
| [getGapDepth()](#getGapDepth--) | Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng dấu, giữa các series dữ liệu trong biểu đồ 3D. |
| [isColorVaried()](#isColorVaried--) | Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. |
| [hasSeriesLines()](#hasSeriesLines--) | Xác định liệu có các đường series cho series này và các series liên quan hay không. |
| [getOverlap()](#getOverlap--) | Chỉ định mức độ chồng chéo của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Chỉ định kích thước của phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của phần đầu tiên (có thể từ 5 tới 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Chỉ định một giá trị sẽ được dùng để xác định những điểm dữ liệu nào nằm trong phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | Chỉ định cách xác định những điểm dữ liệu nào nằm trong phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Chỉ định kích thước lỗ trong biểu đồ bánh donut (có thể từ 10 tới 90% kích thước vùng vẽ). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Chỉ định góc của lát bánh thứ nhất trong biểu đồ pie hoặc donut, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Khoảng cách của một lát bánh mở so với tâm biểu đồ bánh được biểu thị dưới dạng phần trăm của độ kính bánh. Đọc/ghi int.

**Trả về:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Khoảng cách của một lát bánh mở so với tâm biểu đồ bánh được biểu thị dưới dạng phần trăm của độ kính bánh. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Biểu diễn việc làm mịn đường cong. Đúng nếu làm mịn đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Áp dụng chỉ cho biểu đồ đường và biểu đồ phân tán nối bằng đường. Đọc/ghi boolean.

**Trả về:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Biểu diễn việc làm mịn đường cong. Đúng nếu làm mịn đường cong được bật cho biểu đồ đường hoặc biểu đồ phân tán. Áp dụng chỉ cho biểu đồ đường và biểu đồ phân tán nối bằng đường. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Trả về dấu series. Chỉ đọc [IMarker](../../com.aspose.slides/imarker).

**Trả về:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Chỉ định hình dạng của một series của biểu đồ thanh 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của series. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Trả về:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Chỉ định hình dạng của một series của biểu đồ thanh 3-D. Thay đổi giá trị của thuộc tính này có thể gây tự động thay đổi Kiểu của series. Đọc/ghi [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Trả về tên series. Chỉ đọc [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Trả về:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Trả về bộ sưu tập các điểm dữ liệu của series này. Chỉ đọc [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Trả về:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Trả về một kiểu của series này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Trả về:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Trả về một kiểu của series này. Đọc/ghi [ChartType](../../com.aspose.slides/charttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Trả về nhóm series cha. Chỉ đọc [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Trả về:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Trả về định dạng của một series. Chỉ đọc [IFormat](../../com.aspose.slides/iformat).

**Trả về:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Trả về thứ tự của một series. Đọc/ghi int.

**Trả về:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Trả về thứ tự của một series. Đọc/ghi int.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Trả về các Nhãn của một series. Chỉ đọc [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Trả về:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Bộ sưu tập các đường xu hướng series, chỉ đọc [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Trả về:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Biểu diễn ErrorBars của series với hướng X. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng X khả dụng cho series loại area, bar, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Biểu diễn ErrorBars của series với hướng Y. Chỉ đọc [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars với hướng Y khả dụng cho series loại area, bar, line, scatter và bubble. Đối với các loại biểu đồ khác thuộc tính này trả về null (bao gồm biểu đồ 3D). Khi sử dụng giá trị tùy chỉnh, hãy dùng bộ sưu tập DataPoints để chỉ định giá trị (với thuộc tính ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Trả về:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Cho biết nếu series này được vẽ trên trục giá trị thứ hai. Đọc/ghi boolean.

**Trả về:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Cho biết nếu series này được vẽ trên trục giá trị thứ hai. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Trả về hoặc đặt định dạng số cho các giá trị của series. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị của series. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Trả về hoặc đặt định dạng số cho các giá trị x của series. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị x của series. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Trả về hoặc đặt định dạng số cho các giá trị y của series. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Trả về hoặc đặt định dạng số cho các giá trị y của series. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Trả về hoặc đặt định dạng số cho kích thước bong bóng của series. Đọc/ghi String.

**Trả về:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Trả về hoặc đặt định dạng số cho kích thước bong bóng của series. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Chỉ định series dạng thanh, cột hoặc bong bóng sẽ đảo màu nếu giá trị là âm. Đọc/ghi boolean.

**Trả về:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Chỉ định series dạng thanh, cột hoặc bong bóng sẽ đảo màu nếu giá trị là âm. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Chỉ định màu nền đặc đảo cho series. Để áp dụng màu, đặt FillType của series thành FillType.Solid. Đọc/ghi [IColorFormat](../../com.aspose.slides/icolorformat).

**Trả về:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Biểu diễn mục chú giải liên quan tới series này, chỉ đọc [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Trả về:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Trả về một màu tự động của series dựa trên chỉ mục series và kiểu biểu đồ. Màu này được sử dụng mặc định nếu FillType bằng NotDefined.

**Trả về:**
java.lang.Integer - Automatic color of series java.lang.Integer

### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Biểu diễn các điểm nội bộ. Đúng nếu các điểm nội bộ được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Biểu diễn các điểm nội bộ. Đúng nếu các điểm nội bộ được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Biểu diễn các điểm ngoại lệ. Đúng nếu các điểm ngoại lệ được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Biểu diễn các dấu trung bình. Đúng nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Biểu diễn các dấu trung bình. Đúng nếu các dấu trung bình được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Biểu diễn các dấu trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Trả về:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Biểu diễn các dấu trung bình. Đúng nếu đường trung bình được hiển thị trên biểu đồ BoxAndWhisker. Áp dụng chỉ cho biểu đồ BoxAndWhisker. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Biểu diễn phương pháp phần tư. Áp dụng chỉ cho biểu đồ BoxAndWhisker.

**Trả về:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Biểu diễn phương pháp phần tư. Áp dụng chỉ cho biểu đồ BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Biểu diễn các đường kết nối. Áp dụng chỉ cho biểu đồ Waterfall.

**Trả về:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Biểu diễn các đường kết nối. Áp dụng chỉ cho biểu đồ Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Biểu diễn bố cục của các nhãn danh mục cha. Áp dụng chỉ cho biểu đồ Treemap.

**Trả về:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Biểu diễn bố cục của các nhãn danh mục cha. Áp dụng chỉ cho biểu đồ Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Chỉ định hệ số tỷ lệ cho biểu đồ bong bóng (có thể từ 0 tới 300% kích thước mặc định). Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.BubbleSizeScale để đọc/ghi thay đổi giá trị.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.BubbleSizeScale.

**Trả về:**
int

### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Xác định liệu biểu đồ Đường hoặc Cổ phiếu có thanh lên/xuống hay không. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.UpDownBars.HasUpDownBars để đọc/ghi thay đổi giá trị. Dùng thuộc tính ParentSeriesGroup.UpDownBars để định dạng thanh lên/xuống. Chỉ đọc boolean.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Trả về:**
boolean

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Chỉ định khoảng cách giữa các cụm thanh hoặc cột, tính bằng phần trăm chiều rộng thanh hoặc cột. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.GapWidth để đọc/ghi thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.GapWidth.

**Trả về:**
int

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Trả về hoặc đặt khoảng cách, tính bằng phần trăm độ rộng dấu, giữa các series dữ liệu trong biểu đồ 3D. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.GapDepth để đọc/ghi thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.GapDepth.

**Trả về:**
int

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Chỉ định mỗi dấu dữ liệu trong series có màu khác nhau. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.IsColorVaried để đọc/ghi thay đổi giá trị. Chỉ đọc boolean.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.IsColorVaried.

**Trả về:**
boolean

### hasSeriesLines() {#hasSeriesLines--}
```
public 
...
```

Xác định liệu có các đường series cho series này và các series liên quan hay không. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Sử dụng thuộc tính ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.HasSeriesLines để đọc/ghi thay đổi giá trị. Dùng ParentSeriesGroup.SeriesLinesFormat để định dạng các đường series. Chỉ đọc boolean.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.HasSeriesLines.

**Trả về:**
boolean

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Chỉ định mức độ chồng chéo của các thanh và cột trên biểu đồ 2-D, tính bằng phần trăm (từ -100% tới 100%). Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha. Nó là sự chiếu của thuộc tính thích hợp trong nhóm series cha, vì vậy thuộc tính này chỉ đọc. Để thay đổi giá trị, dùng thuộc tính ParentSeriesGroup.Overlap để đọc/ghi. Chỉ đọc byte.

--------------------

Overlap chỉ định mức độ chồng chéo hoặc khoảng cách giữa các thanh và cột tính bằng phần trăm độ rộng của chúng: -100%: Khoảng cách tối đa (các thanh hoàn toàn tách rời). 0%: Các thanh đặt cạnh nhau mà không chồng hoặc có khoảng cách. 100%: Chồng tối đa (các thanh hoàn toàn chồng lên nhau). Đây là sự chiếu của thuộc tính ParentSeriesGroup.Overlap.

**Trả về:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Chỉ định kích thước của phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie, tính bằng phần trăm kích thước của phần đầu tiên (có thể từ 5 tới 200%). Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.SecondPieSize để đọc/ghi thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.SecondPieSize.

**Trả về:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Chỉ định một giá trị sẽ được dùng để xác định những điểm dữ liệu nào nằm trong phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie. Được sử dụng cùng với thuộc tính PieSplitBy. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.PieSplitPosition để đọc/ghi thay đổi giá trị. Chỉ đọc double.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.PieSplitPosition.

**Trả về:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Chỉ định cách xác định những điểm dữ liệu nào nằm trong phần thứ hai (pie hoặc bar) của biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.PieSplitBy để đọc/ghi thay đổi giá trị. Chỉ đọc [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Đây là sự chiếu của thuộc tính ParentSeriesGroup.PieSplitBy. 2) Nếu giá trị thuộc tính là PieSplitType.Custom thì bạn có thể định nghĩa thông tin chia tách tùy chỉnh với thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Chỉ định kích thước lỗ trong biểu đồ bánh donut (có thể từ 10 tới 90% kích thước vùng vẽ). Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.DoughnutHoleSize để đọc/ghi thay đổi giá trị. Chỉ đọc byte.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.DoughnutHoleSize.

**Trả về:**
byte

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Chỉ định góc của lát bánh thứ nhất trong biểu đồ pie hoặc donut, tính bằng độ (theo chiều kim đồng hồ từ trên, từ 0 tới 360 độ). Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.FirstSliceAngle để đọc/ghi thay đổi giá trị. Chỉ đọc int.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.FirstSliceAngle.

**Trả về:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Thông tin chia tách tùy chỉnh cho biểu đồ pie-of-pie hoặc bar-of-pie có chia tách tùy chỉnh. Chứa các điểm dữ liệu sẽ được vẽ trong phần thứ hai của biểu đồ pie-of-pie hoặc bar-of-pie. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp Chỉ đọc [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.PieSplitCustomPoints.

**Trả về:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Chỉ định cách các giá trị kích thước bong bóng được biểu diễn trên biểu đồ bong bóng. Đây là thuộc tính không chỉ của series này mà của tất cả series trong nhóm series cha — đây là sự chiếu của thuộc tính nhóm thích hợp. Vì vậy thuộc tính này chỉ đọc. Dùng ParentSeriesGroup để truy cập nhóm series cha. Dùng ParentSeriesGroup.BubbleSizeRepresentation để đọc/ghi thay đổi giá trị.

--------------------

Đây là sự chiếu của thuộc tính ParentSeriesGroup.BubbleSizeRepresentation.

**Trả về:**
int