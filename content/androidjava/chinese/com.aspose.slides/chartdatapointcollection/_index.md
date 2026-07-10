---
title: ChartDataPointCollection
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示系列数据点的集合。
type: docs
url: /zh/com.aspose.slides/chartdatapointcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)  
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

表示系列数据点的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 按索引（在此集合中的序号）返回系列数据点。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 返回数据点在此集合中的索引（序号）。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 指定在数据点的 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 指定在数据点的 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 指定在数据点的 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 指定在数据点的 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 指定在数据点的 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 指定在数据点的 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 指定在数据点的 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 指定在数据点的 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 如果集合已包含索引为 index 的数据点，则返回该数据点。 |
| [size()](#size--) | 获取集合中实际包含的元素数量。 |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | 复制到指定数组。 |
| [isSynchronized()](#isSynchronized--) | 返回指示集合访问是否同步（线程安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步根。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 为整个集合返回 java 迭代器。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 创建新数据点并将其添加到集合末尾。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除给定索引处的元素。 |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

按索引（在此集合中的序号）返回系列数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```

返回数据点在此集合中的索引（序号）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**返回值:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```

指定在数据点的 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.XValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回值:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```

指定在数据点的 XValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.XValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```

指定在数据点的 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.YValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回值:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```

指定在数据点的 YValue 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.YValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```

指定在数据点的 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.BubbleSize.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回值:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```

指定在数据点的 BubbleSize 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.BubbleSize.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```

指定在数据点的 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回值:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```

指定在数据点的 Value 属性对象中实际使用的是 AsCell、AsLiteralString 还是 AsLiteralDouble 属性。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。只读 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**返回值:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```

如果集合已经包含索引为 index 的数据点，则返回该数据点。如果集合不包含索引为 index==N（当集合中的数据点数量小于或等于 N） 的数据点，则会补足缺失的数据点并返回最后一个（即请求的索引）。例如，集合索引为 {0, 1, 2}，请求索引为 5，则方法会添加缺失的数据点：{0, 1, 2, 3, 4, 5}，并返回索引为 5 的数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | long | 索引。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 返回具有请求索引的数据点。

### size() {#size--}
```
public final int size()
```

获取集合中实际包含的元素数量。只读 int。

**返回值:**
int

### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```

复制到指定数组。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 要复制到的数组。 |
| arrayIndex | int | 开始复制的索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

返回指示集合访问是否同步（线程安全）的值。只读 boolean。

**返回值:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

返回同步根。只读 Object。

**返回值:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

返回遍历集合的枚举器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回值:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - 用于整个集合的 java.util.Iterator。

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value。 |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 和 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) 和 [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型的系列（另见 [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Sunburst 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 SizeValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Treemap 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 SizeValue |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 BoxAndWhisker 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Waterfall 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Histogram 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Funnel 的系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回值:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新数据点。

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

创建新数据点并将其添加到集合末尾。适用于 chartType 为 Map 的系列。

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

从集合中移除所有元素。

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

移除指定的值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 该值。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)


移除给定索引处的元素。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的数据点的索引。 |