---
title: IChartDataPointCollection
second_title: Aspose.Slides for Java API 參考
description: 表示系列資料點的集合。
type: docs
url: /zh-hant/com.aspose.slides/ichartdatapointcollection/
---
**已實作的所有介面:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

表示系列資料點的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 傳回此集合中依索引（其在此集合中的序號）之系列資料點。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 傳回此集合中資料點的索引（在此集合中的序號）。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 指定資料點 XValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 指定資料點 XValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 指定資料點 YValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 指定資料點 YValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 指定資料點 BubbleSize 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 指定資料點 BubbleSize 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 指定資料點 Value 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 指定資料點 Value 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | 指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 若集合已包含索引為 index 的資料點，則傳回該資料點。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其新增至集合的結尾。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除給定索引處的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

傳回此集合中依索引（其在此集合中的序號）之系列資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

傳回此集合中資料點的索引（在此集合中的序號）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**傳回值:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

指定資料點 XValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.XValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

指定資料點 XValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.XValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

指定資料點 YValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.YValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

指定資料點 YValue 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.YValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

指定資料點 BubbleSize 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.BubbleSize.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

指定資料點 BubbleSize 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPointEx.BubbleSize.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

指定資料點 Value 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPoint.Value.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

指定資料點 Value 屬性物件中 AsCell、AsLiteralString 或 AsLiteralDouble 屬性是否為實際屬性。換言之，它指定 ChartDataPoint.Value.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。唯讀 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**傳回值:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

若集合已包含索引為 index 的資料點，則傳回該資料點。若集合不包含索引為 index==N 的資料點（當此集合的資料點數量小於或等於 N 時），則會新增缺失的資料點並傳回最後一個（即請求的索引）。例如，集合索引為 {0, 1, 2}，請求的索引為 5，則方法會新增缺失的資料點：{0, 1, 2, 3, 4, 5}，並傳回索引為 5 的資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | long | 索引。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 傳回具請求索引的資料點。
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

建立新的資料點並將其新增至集合的結尾。適用於 chartType 為 Stock 子類型之一的系列（另見 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

建立新的資料點並將其新增至集合的結尾。適用於 chartType 為 Stock 子類型之一的系列（另見 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

建立新的資料點並將其新增至集合的結尾。適用於 chartType 為 Line 子類型之一的系列（另見 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

建立新的資料點並將其新增至集合的結尾。適用於 chartType 為 Line 子類型之一的系列（另見 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

建立新的資料點並將其新增至集合的結尾。適用於 chartType 為 Scatter 子類型之一的系列（另見 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |

| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Scatter 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Scatter 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Scatter 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Scatter 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Scatter 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Radar 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Radar 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Column 或 Bar 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Column 或 Bar 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Area 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Area 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Pie 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Pie 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Doughnut 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

建立新資料點並將其新增到集合的末端。適用於圖表類型為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Bubble 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Surface 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


建立新的資料點並將其新增至集合的末端。適用於其 chartType 為 Surface 子類型之一的系列（另請參閱 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Sunburst 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 SizeValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Waterfall 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 值 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 BoxAndWhisker 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Treemap 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 SizeValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Histogram 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 值 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Funnel 的系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 值 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


建立新的資料點並將其新增至集合的末端。適用於圖表類型為 Map 的系列。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 ColorValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。
### clear() {#clear--}
```
public abstract void clear()
```


從集合中移除所有元素。

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


移除指定的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 值。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


移除給定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的資料點索引。 |