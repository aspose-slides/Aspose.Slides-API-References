---
title: ChartDataPointCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 代表系列資料點的集合。
type: docs
url: /zh-hant/com.aspose.slides/chartdatapointcollection/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

代表系列資料點的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回系列資料點（它在此集合中的序號）。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 返回資料點在此集合中的索引（序號）。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 指定在資料點的 XValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 指定在資料點的 XValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 指定在資料點的 YValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 指定在資料點的 YValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 指定在資料點的 BubbleSize 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 指定在資料點的 BubbleSize 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 指定在資料點的 Value 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 指定在資料點的 Value 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | 指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 如果集合已包含索引為 index 的資料點，則返回該資料點。 |
| [size()](#size--) | 取得集合實際包含的元素數量。 |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | 複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 返回一個值，指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回一個可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 建立新的資料點並將其加入集合的末端。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除給定索引處的元素。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

返回系列資料點（它在此集合中的序號）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

返回資料點在此集合中的索引（序號）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**傳回值:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

指定在資料點的 XValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.XValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

指定在資料點的 XValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.XValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

指定在資料點的 YValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.YValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

指定在資料點的 YValue 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.YValue.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

指定在資料點的 BubbleSize 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.BubbleSize.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

指定在資料點的 BubbleSize 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.BubbleSize.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

指定在資料點的 Value 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.Value.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**傳回值:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

指定在資料點的 Value 屬性物件中實際使用的是 AsCell、AsLiteralString 或 AsLiteralDouble 屬性。換句話說，它指定 ChartDataPoint.Value.Data 屬性的值類型。讀寫 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

指定 ChartDataPoint.ErrorBarsCustomValues 屬性清單中值的類型。唯讀 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**傳回值:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

如果集合已包含索引為 index 的資料點，則返回該資料點。如果集合不包含索引為 index==N 的資料點（當此集合中的資料點數量小於或等於 N 時），則會新增缺少的資料點，並返回最後一個（即請求的索引）。例如，集合索引為 {0, 1, 2}，請求的索引為 5。則方法會新增缺少的資料點：{0, 1, 2, 3, 4, 5}，並返回索引為 5 的資料點。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | long | Index. |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 返回請求的索引的資料點。

### size() {#size--}
```
public final int size()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回值:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

複製到指定的陣列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要複製到的陣列。 |
| arrayIndex | int | 開始複製的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回一個值，指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean。

**傳回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。唯讀 Object。

**傳回值:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

返回一個可遍歷集合的列舉器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

返回整個集合的 java 迭代器。

**傳回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 一個 java.util.Iterator，用於遍歷整個集合。

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Stock 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Line 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Line 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值。 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Scatter 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Radar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Radar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Column 或 Bar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 和 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Column 或 Bar 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 和 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Area 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Area 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Pie 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Doughnut 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Doughnut 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | double | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Bubble 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| xValue | java.lang.String | 資料點 XValue |
| yValue | double | 資料點 YValue |
| bubbleSize | double | 資料點 BubbleSize |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

建立新的資料點並將其加入集合的末端。適用於 chartType 為 Surface 子類型之一的系列（另請參閱 [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 方法）。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Sunburst。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 SizeValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Treemap。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 SizeValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 BoxAndWhisker。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Waterfall。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Histogram。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Funnel。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點值 |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

建立新的資料點並將其加入集合的末端。適用於 chart type 為 Map。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 資料點 ColorValue |

**傳回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的資料點。

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有元素。

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

移除指定的值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 此值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除給定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之資料點的索引。 |