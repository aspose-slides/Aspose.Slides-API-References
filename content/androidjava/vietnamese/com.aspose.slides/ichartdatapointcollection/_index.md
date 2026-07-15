---
title: IChartDataPointCollection
second_title: Tham chiếu API Aspose.Slides cho Android thông qua Java
description: Biểu diễn một bộ sưu tập các điểm dữ liệu của chuỗi.
type: docs
url: /vi/com.aspose.slides/ichartdatapointcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Biểu diễn một bộ sưu tập các điểm dữ liệu của chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu chuỗi theo chỉ mục (số thứ tự của nó trong bộ sưu tập này). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Trả về chỉ mục (số thứ tự trong bộ sưu tập này) của điểm dữ liệu trong bộ sưu tập này. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính XValue của điểm dữ liệu hay không. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính XValue của điểm dữ liệu hay không. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính YValue của điểm dữ liệu hay không. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính YValue của điểm dữ liệu hay không. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính BubbleSize của điểm dữ liệu hay không. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính BubbleSize của điểm dữ liệu hay không. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính Value của điểm dữ liệu hay không. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính Value của điểm dữ liệu hay không. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Xác định loại giá trị trong danh sách các thuộc tính ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Nếu bộ sưu tập đã chứa điểm dữ liệu với chỉ mục index thì trả về điểm dữ liệu này. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Xóa giá trị đã chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ mục đã cho. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Trả về điểm dữ liệu chuỗi theo chỉ mục (số thứ tự của nó trong bộ sưu tập này).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Trả về chỉ mục (số thứ tự trong bộ sưu tập này) của điểm dữ liệu trong bộ sưu tập này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Giá trị trả về:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính XValue của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceForXValues(int value)
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính XValue của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính YValue của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính YValue của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính BubbleSize của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính BubbleSize của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính Value của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Xác định xem thuộc tính AsCell, AsLiteralString hoặc AsLiteralDouble có thực tế trong đối tượng thuộc tính Value của điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Xác định loại giá trị trong danh sách các thuộc tính ChartDataPoint.ErrorBarsCustomValues. Chỉ đọc [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Giá trị trả về:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Nếu bộ sưu tập đã chứa điểm dữ liệu với chỉ mục index thì trả về điểm dữ liệu này. Nếu bộ sưu tập không chứa điểm dữ liệu với chỉ mục index==N (khi số điểm dữ liệu trong bộ sưu tập ít hơn hoặc bằng N) thì thêm các điểm dữ liệu thiếu và trả về điểm cuối cùng (có chỉ mục yêu cầu). Ví dụ, các chỉ mục trong bộ sưu tập là {0, 1, 2}, và chỉ mục yêu cầu là 5. Khi đó phương thức sẽ thêm các điểm dữ liệu thiếu: {0, 1, 2, 3, 4, 5}. Và trả về điểm dữ liệu có chỉ mục 5.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | long | Chỉ mục. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Trả về điểm dữ liệu có chỉ mục yêu cầu.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Stock (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Stock (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Line (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Line (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Radar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Radar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeRadar(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Column hoặc Bar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeColumn(ChartType) và ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Column hoặc Bar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeColumn(ChartType) và ChartTypeCharacterizer.IsChartTypeBar(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Area (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Area (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeArea(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Pie (xem thêm phương thức ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Pie (xem thêm phương thức ChartTypeCharacterizer.IsChartTypePie(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Doughnut (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Doughnut (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Surface (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Surface (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeSurface(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Sunburst.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Histogram.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Funnel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

Xóa giá trị đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Giá trị. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một điểm dữ liệu cần xóa. |