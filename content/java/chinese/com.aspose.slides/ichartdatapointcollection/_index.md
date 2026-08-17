---
title: IChartDataPointCollection
second_title: Aspose.Slides for Java API 参考
description: 表示系列数据点的集合。
type: docs
url: /zh/com.aspose.slides/ichartdatapointcollection/
---
**所有已实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

表示系列数据点的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回集合中按索引（在此集合中的序号）获取系列数据点。 |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | 返回集合中数据点的索引（在此集合中的序号）。 |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | 指定数据点 XValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | 指定数据点 XValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | 指定数据点 YValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | 指定数据点 YValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | 指定数据点 BubbleSize 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | 指定数据点 BubbleSize 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | 指定数据点 Value 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | 指定数据点 Value 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。 |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。 |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | 如果集合已包含索引为 index 的数据点，则返回该数据点。 |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | 创建新的数据点并将其添加到集合末尾。 |
| [clear()](#clear--) | 从集合中移除所有元素。 |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | 移除指定的值。 |
| [removeAt(int index)](#removeAt-int-) | 移除给定索引处的元素。 |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

返回集合中按索引（在此集合中的序号）获取系列数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)

### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

返回集合中数据点的索引（在此集合中的序号）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**返回:**  
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

指定数据点 XValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.XValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回:**  
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

指定数据点 XValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.XValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

指定数据点 YValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.YValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回:**  
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

指定数据点 YValue 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.YValue.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

指定数据点 BubbleSize 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.BubbleSize.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回:**  
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

指定数据点 BubbleSize 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPointEx.BubbleSize.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

指定数据点 Value 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**返回:**  
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

指定数据点 Value 属性对象中实际使用的属性是 AsCell、AsLiteralString 还是 AsLiteralDouble。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。读/写 [DataSourceType](../../com.aspose.slides/datasourcetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。只读 [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)。

**返回:**  
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

如果集合已包含索引为 index 的数据点，则返回该数据点。如果集合不包含索引为 index==N 的数据点（当集合中的数据点数量小于等于 N 时），则会补足缺失的数据点并返回最后一个（即请求的索引）。例如，集合索引为 {0, 1, 2}，请求的索引为 5。则方法会补足缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | long | 索引。 |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 返回请求索引的数据点。

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型的系列（另见 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点值。 |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型的系列（另见 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值。 |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型的系列（另见 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点值。 |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型的系列（另见 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点值。 |

**返回:**  
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

创建新的数据点并将其添加到集合的末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。

**参数：**
| Parameter | Type | Description |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - New data point.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | double | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also ChartTypeCharacterizer.IsChartTypeBubble(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xValue | java.lang.String | 数据点 XValue |
| yValue | double | 数据点 YValue |
| bubbleSize | double | 数据点 BubbleSize |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Surface subtypes (see also ChartTypeCharacterizer.IsChartTypeSurface(ChartType) method).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Sunburst.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 SizeValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Waterfall.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is BoxAndWhisker.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 Value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Treemap.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 SizeValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series which chart type is Histogram.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series where chart type is Funnel.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 value |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


Creates the new data point and adds it to the end of collection. Applicable for series where chart type is Map.

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | 数据点 ColorValue |

**返回：**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - 新的数据点。
### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


Removes the specified value.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | 该值。 |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the given index.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要移除的数据点的索引。 |