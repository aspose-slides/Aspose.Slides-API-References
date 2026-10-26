---
title: IChartDataPointCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho bộ sưu tập các điểm dữ liệu của một chuỗi.
type: docs
url: /vi/com.aspose.slides/ichartdatapointcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

Biểu diễn một tập hợp các điểm dữ liệu chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu chuỗi theo chỉ số (số thứ tự trong tập hợp này). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Trả về chỉ số (số thứ tự trong tập hợp này) của điểm dữ liệu trong tập hợp này. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Xác định loại giá trị trong danh sách các thuộc tính ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Nếu tập hợp đã chứa điểm dữ liệu có chỉ số index thì trả về điểm dữ liệu này. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ số đã cho. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Trả về điểm dữ liệu chuỗi theo chỉ số (số thứ tự trong tập hợp này).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

Trả về chỉ số (số thứ tự trong tập hợp này) của điểm dữ liệu trong tập hợp này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Trả về:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Trả về:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Trả về:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Trả về:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPointEx.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Trả về:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

Xác định liệu thuộc tính AsCell hoặc AsLiteralString hoặc AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. Nói cách khác, nó xác định loại giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

Xác định loại giá trị trong danh sách các thuộc tính ChartDataPoint.ErrorBarsCustomValues. Chỉ đọc [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Trả về:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

Nếu tập hợp đã chứa điểm dữ liệu có chỉ số index thì trả về điểm dữ liệu này. Nếu tập hợp không chứa điểm dữ liệu với chỉ số index==N (khi số điểm dữ liệu trong tập hợp này ít hơn hoặc bằng N) thì thêm các điểm dữ liệu thiếu và trả về điểm dữ liệu cuối cùng (có chỉ số yêu cầu). Ví dụ, các chỉ số trong tập hợp là {0, 1, 2}, và chỉ số yêu cầu là 5. Khi đó phương thức sẽ thêm các điểm dữ liệu thiếu: {0, 1, 2, 3, 4, 5}. Và trả về điểm dữ liệu có chỉ số 5.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | long | Chỉ số. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Trả về điểm dữ liệu với chỉ số yêu cầu.

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho chuỗi có chartType là một trong các kiểu con Stock (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị của điểm dữ liệu. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho chuỗi có chartType là một trong các kiểu con Stock (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeStock(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị của điểm dữ liệu. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho chuỗi có chartType là một trong các kiểu con Line (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị của điểm dữ liệu. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho chuỗi có chartType là một trong các kiểu con Line (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeLine(ChartType)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị của điểm dữ liệu. |

**Trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho chuỗi có chartType là một trong các kiểu con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType)).
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Scatter (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeScatter(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Radar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Radar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeRadar(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Column hoặc Bar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeColumn(ChartType) và ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Column hoặc Bar (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeColumn(ChartType) và ChartTypeCharacterizer.IsChartTypeBar(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Area (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeArea(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Area (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeArea(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Pie (xem thêm phương thức ChartTypeCharacterizer.IsChartTypePie(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Pie (xem thêm phương thức ChartTypeCharacterizer.IsChartTypePie(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Doughnut (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Doughnut (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Trả về:** [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Bubble (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | XValue của điểm dữ liệu |
| yValue | double | YValue của điểm dữ liệu |
| bubbleSize | double | BubbleSize của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Surface (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series có chartType là một trong các loại con Surface (xem thêm phương thức ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Sunburst.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Waterfall.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là BoxAndWhisker.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Treemap.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Histogram.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Funnel.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | value của điểm dữ liệu |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho series có chart type là Map.

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


**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue của điểm dữ liệu |

**Returns:**
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

Xóa giá trị được chỉ định.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Giá trị. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ số đã cho.

**Parameters:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của điểm dữ liệu cần xóa. |