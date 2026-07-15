---
title: ChartDataPointCollection
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn bộ sưu tập các điểm dữ liệu của một chuỗi.
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

Biểu diễn bộ sưu tập các điểm dữ liệu của một chuỗi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về điểm dữ liệu của chuỗi theo chỉ số (số thứ tự trong bộ sưu tập này). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Trả về chỉ số (số thứ tự) của điểm dữ liệu trong bộ sưu tập này. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính XValue của các điểm dữ liệu. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính XValue của các điểm dữ liệu. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính YValue của các điểm dữ liệu. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính YValue của các điểm dữ liệu. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính Value của các điểm dữ liệu. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính Value của các điểm dữ liệu. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | Xác định các kiểu giá trị trong danh sách thuộc tính ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | Nếu bộ sưu tập đã chứa điểm dữ liệu với chỉ số index thì trả về điểm dữ liệu này. |
| [size()](#size--) | Lấy số lượng phần tử thực sự có trong bộ sưu tập. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một đối tượng đồng bộ. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | Xóa giá trị được chỉ định. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ số đã cho. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

Trả về điểm dữ liệu của chuỗi theo chỉ số (số thứ tự trong bộ sưu tập này).

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

Trả về chỉ số (số thứ tự) của điểm dữ liệu trong bộ sưu tập này.

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

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính XValue của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính XValue của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.XValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính YValue của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính YValue của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.YValue.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính BubbleSize của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.BubbleSize.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính Value của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

**Giá trị trả về:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

Xác định thuộc tính AsCell, AsLiteralString hay AsLiteralDouble đang được sử dụng trong đối tượng thuộc tính Value của các điểm dữ liệu. Nói cách khác, nó xác định kiểu giá trị của thuộc tính ChartDataPoint.Value.Data. Đọc/ghi [DataSourceType](../../com.aspose.slides/datasourcetype).

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

Nếu bộ sưu tập đã chứa điểm dữ liệu với chỉ số index thì trả về điểm dữ liệu này. Nếu bộ sưu tập không chứa điểm dữ liệu với index == N (khi số điểm dữ liệu trong bộ sưu tập ≤ N) thì sẽ thêm các điểm thiếu và trả về điểm cuối cùng (có chỉ số yêu cầu). Ví dụ, chỉ số bộ sưu tập là {0, 1, 2}, và chỉ số yêu cầu là 5. Khi đó phương thức sẽ thêm các điểm thiếu: {0, 1, 2, 3, 4, 5}. Và trả về điểm dữ liệu có chỉ số 5.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | long | Chỉ số. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Trả về điểm dữ liệu có chỉ số yêu cầu.
### size() {#size--}
```
public final int size()
```

Lấy số lượng phần tử thực sự có trong bộ sưu tập. Chỉ đọc int.

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
| arrayIndex | int | Chỉ số bắt đầu sao chép. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

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

Trả về một enumerator duyệt qua bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một IGenericEnumerator có thể dùng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Stock (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Stock (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Line (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Line (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu. |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Scatter (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Radar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Radar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Column hoặc Bar (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) và [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Column hoặc Bar (xém thêm phương thức [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) và [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Area (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Area (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Pie (xem thêm phương thức [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Pie (xem thêm phương thức [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Doughnut (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Doughnut (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | double | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Bubble (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| xValue | java.lang.String | Giá trị XValue của điểm dữ liệu |
| yValue | double | Giá trị YValue của điểm dữ liệu |
| bubbleSize | double | Giá trị BubbleSize của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Surface (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chartType là một trong các loại Surface (xem thêm phương thức [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Sunburst.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị SizeValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Treemap.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị SizeValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là BoxAndWhisker.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Waterfall.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Histogram.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Funnel.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị Value của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

Tạo điểm dữ liệu mới và thêm vào cuối bộ sưu tập. Áp dụng cho các chuỗi có chart type là Map.

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Giá trị ColorValue của điểm dữ liệu |

**Giá trị trả về:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Điểm dữ liệu mới.
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

Xóa giá trị được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Giá trị cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phần tử tại chỉ số đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của điểm dữ liệu cần xóa. |