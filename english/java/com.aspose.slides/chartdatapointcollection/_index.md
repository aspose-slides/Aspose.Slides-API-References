---
title: ChartDataPointCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents collection of a series data point.
type: docs
weight: 85
url: /java/com.aspose.slides/chartdatapointcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

Represents collection of a series data point.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the series data point by index. |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | Return index of data point in this collection. |
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


Returns the series data point by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```


Return index of data point in this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**Returns:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. In other words it specifies the type of value of ChartDataPoint.XValue.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returns:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points XValue property object. In other words it specifies the type of value of ChartDataPoint.XValue.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. In other words it specifies the type of value of ChartDataPoint.YValue.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returns:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points YValue property object. In other words it specifies the type of value of ChartDataPoint.YValue.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. In other words it specifies the type of value of ChartDataPoint.BubbleSize.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returns:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points BubbleSize property object. In other words it specifies the type of value of ChartDataPoint.BubbleSize.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. In other words it specifies the type of value of ChartDataPoint.Value.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Returns:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```


Specifies whether AsCell or AsLiteralString or AsLiteralDouble property is actual in data points Value property object. In other words it specifies the type of value of ChartDataPoint.Value.Data property. Read/write [DataSourceType](../../com.aspose.slides/datasourcetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```


Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list. Read-only [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**Returns:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```


If collection already contains data point with index index then returns this data point. If collection doesn't contains data point with index index==N (when number of data points in this collection is less or equal then N) then adds deficient data points and returns last (which has requested index). For example, collection indexes are \{0, 1, 2\}, and requested index is 5. Then method adds deficient data points: \{0, 1, 2, 3, 4, 5\}. And returns data point with index 5.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | long | Index. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Returns data point with requested index.
### size() {#size--}
```
public final int size()
```


Gets the number of elements actually contained in the collection. Read-only int.

**Returns:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


Copy to specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to copy to. |
| arrayIndex | int | Index to begin copying. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer\#isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer\#isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer\#isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer\#isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value. |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer\#isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer\#isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer\#isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer\#isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer\#isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer\#isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer\#isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer\#isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer\#isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer\#isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer\#isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer\#isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer\#isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer\#isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | Data point XValue |
| yValue | double | Data point YValue |
| bubbleSize | double | Data point BubbleSize |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also [ChartTypeCharacterizer\#isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also [ChartTypeCharacterizer\#isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) method).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Sunburst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Treemap.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point SizeValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is BoxAndWhisker.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Waterfall.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Histogram.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Funnel.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point Value |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Map.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Data point ColorValue |

**Returns:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a data point to remove. |

