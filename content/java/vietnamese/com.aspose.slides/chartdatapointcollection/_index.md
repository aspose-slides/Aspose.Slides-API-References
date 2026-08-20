---
title: ChartDataPointCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn tập hợp các điểm dữ liệu của một chuỗi.
type: docs
url: /vi/com.aspose.slides/chartdatapointcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Đại diện cho tập hợp của một điểm dữ liệu chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the series data point by index (its serial number in this collection). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Return index (serial number) of data point in this collection. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | If collection already contains data point with index index then returns this data point. |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Copy to specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Creates the new data point and adds it to the end of collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the given index. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


Trả về điểm dữ liệu chuỗi theo chỉ mục (số thứ tự của nó trong tập hợp này).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```


Trả về chỉ mục (số thứ tự) của điểm dữ liệu trong tập hợp này.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Giá trị trả về:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.XValue. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính XValue của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.XValue. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.YValue. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính YValue của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.YValue. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.BubbleSize. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.BubbleSize. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.Value. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```


Xác định xem thuộc tính AsCell hay AsLiteralString hay AsLiteralDouble có thực trong đối tượng thuộc tính Value của các điểm dữ liệu hay không. Nói cách khác, nó chỉ định kiểu giá trị của thuộc tính Data của ChartDataPoint.Value. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```


Xác định các kiểu giá trị trong danh sách thuộc tính ChartDataPoint.ErrorBarsCustomValues. Chỉ đọc [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Giá trị trả về:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```


Nếu tập hợp đã chứa điểm dữ liệu với chỉ mục index thì trả về điểm dữ liệu này. Nếu tập hợp không chứa điểm dữ liệu với chỉ mục index==N (khi số điểm dữ liệu trong tập hợp này ít hơn hoặc bằng N) thì sẽ thêm các điểm dữ liệu thiếu và trả về điểm cuối cùng (có chỉ mục được yêu cầu). Ví dụ, các chỉ mục của tập hợp là \{0, 1, 2\}, và chỉ mục yêu cầu là 5. Khi đó phương thức sẽ thêm các điểm dữ liệu thiếu: \{0, 1, 2, 3, 4, 5\}. Và trả về điểm dữ liệu với chỉ mục 5.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | long | Chỉ mục. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Trả về điểm dữ liệu với chỉ mục được yêu cầu.
### size() {#size--}
```
public final int size()
```


Lấy số phần tử thực sự có trong tập hợp. Chỉ đọc int.

**Giá trị trả về:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Sao chép vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích để sao chép. |
| arrayIndex | int | Chỉ mục bắt đầu sao chép. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị chỉ ra việc truy cập tập hợp có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Giá trị trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một đối tượng đồng bộ. Chỉ đọc Object.

**Giá trị trả về:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Trả về một enumerator cho phép duyệt qua tập hợp.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một IGenericEnumerator có thể được dùng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Trả về một java iterator cho toàn bộ tập hợp.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một java.util.Iterator cho toàn bộ tập hợp.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```


Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho các chuỗi có chartType là một trong các kiểu con Stock (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Stock (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Line (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Line (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị X của điểm dữ liệu |
| yValue | double | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị X của điểm dữ liệu |
| yValue | double | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị X của điểm dữ liệu |
| yValue | double | Giá trị Y của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Radar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Radar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Column hoặc Bar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) và [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Column hoặc Bar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) và [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Area (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Area (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Pie (xem thêm phương thức [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Pie (xem thêm phương thức [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Doughnut (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Doughnut (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Kích thước bong bóng của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Kích thước bong bóng của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị X của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Y của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Kích thước bong bóng của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị X của điểm dữ liệu |
| yValue | double | Giá trị Y của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Kích thước bong bóng của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị X của điểm dữ liệu |
| yValue | double | Giá trị Y của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Kích thước bong bóng của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo một điểm dữ liệu mới và thêm nó vào cuối bộ sưu tập. Áp dụng cho các series mà chartType là một trong các kiểu phụ Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Bubble (xem phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Điểm dữ liệu XValue |
| yValue | double | Điểm dữ liệu YValue |
| bubbleSize | double | Điểm dữ liệu BubbleSize |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Surface (xem phương thức [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chartType là một trong các kiểu Surface (xem phương thức [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Sunburst.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu SizeValue |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu SizeValue |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Histogram.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Funnel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu Value |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm nó vào cuối tập hợp. Áp dụng cho series có chart type là Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Điểm dữ liệu ColorValue |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi tập hợp.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Xóa giá trị đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Giá trị. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ số đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của một điểm dữ liệu cần xóa. |