---
title: ChartDataPointCollection
second_title: Aspose.Sildes for .NET API 参考
description: 表示系列数据点的集合。
type: docs
weight: 1350
url: /zh/aspose.slides.charts/chartdatapointcollection/
---
## ChartDataPointCollection 类

表示系列数据点的集合。

```csharp
public class ChartDataPointCollection : DomObject<ChartSeries>, IChartDataPointCollection
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.slides.charts/chartdatapointcollection/count) { get; } | 获取集合中实际包含的元素数量。只读 Int32。 |
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | 指定在数据点的 BubbleSize 属性对象中，AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 ChartDataPoint.BubbleSize.Data 属性的值类型。可读写 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中值的类型。只读 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |
| [DataSourceTypeForValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforvalues) { get; set; } | 指定在数据点的 Value 属性对象中，AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。可读写 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForXValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforxvalues) { get; set; } | 指定在数据点的 XValue 属性对象中，AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 ChartDataPoint.XValue.Data 属性的值类型。可读写 [`DataSourceType`](../datasourcetype)。 |
| [DataSourceTypeForYValues](../../aspose.slides.charts/chartdatapointcollection/datasourcetypeforyvalues) { get; set; } | 指定在数据点的 YValue 属性对象中，AsCell、AsLiteralString 或 AsLiteralDouble 属性哪个是实际使用的。换句话说，它指定 ChartDataPoint.YValue.Data 属性的值类型。可读写 [`DataSourceType`](../datasourcetype)。 |
| [IsSynchronized](../../aspose.slides.charts/chartdatapointcollection/issynchronized) { get; } | 返回一个值，指示对集合的访问是否已同步（线程安全）。只读 Boolean。 |
| [Item](../../aspose.slides.charts/chartdatapointcollection/item) { get; } | 通过索引返回系列数据点（它在此集合中的序号）。(2 索引器) |
| [SyncRoot](../../aspose.slides.charts/chartdatapointcollection/syncroot) { get; } | 返回同步根。只读 Object。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 方法）。 |
| [AddDataPointForAreaSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型之一的系列（另请参阅 [`IsChartTypeArea`](../charttypecharacterizer/ischarttypearea) 方法）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 和 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 方法）。 |
| [AddDataPointForBarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另请参阅 [`IsChartTypeColumn`](../charttypecharacterizer/ischarttypecolumn) 和 [`IsChartTypeBar`](../charttypecharacterizer/ischarttypebar) 方法）。 |
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 BoxAndWhisker 的系列。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另请参阅 [`IsChartTypeBubble`](../charttypecharacterizer/ischarttypebubble) 方法）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 方法）。 |
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另请参阅 [`IsChartTypeDoughnut`](../charttypecharacterizer/ischarttypedoughnut) 方法）。 |
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Funnel 的系列。 |
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Histogram 的系列。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 方法）。 |
| [AddDataPointForLineSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型之一的系列（另请参阅 [`IsChartTypeLine`](../charttypecharacterizer/ischarttypeline) 方法）。 |
| [AddDataPointForMapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Map 的系列。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 方法）。 |
| [AddDataPointForPieSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型之一的系列（另请参阅 [`IsChartTypePie`](../charttypecharacterizer/ischarttypepie) 方法）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 方法）。 |
| [AddDataPointForRadarSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型之一的系列（另请参阅 [`IsChartTypeRadar`](../charttypecharacterizer/ischarttyperadar) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForScatterSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另请参阅 [`IsChartTypeScatter`](../charttypecharacterizer/ischarttypescatter) 方法）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 方法）。 |
| [AddDataPointForStockSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型之一的系列（另请参阅 [`IsChartTypeStock`](../charttypecharacterizer/ischarttypestock) 方法）。 |
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Sunburst 的系列。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型之一的系列（另请参阅 [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 方法）。 |
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型之一的系列（另请参阅 [`IsChartTypeSurface`](../charttypecharacterizer/ischarttypesurface) 方法）。 |
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Treemap 的系列。 |
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/chartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Waterfall 的系列。 |
| [Clear](../../aspose.slides.charts/chartdatapointcollection/clear)() | 移除集合中的所有元素。 |
| [CopyTo](../../aspose.slides.charts/chartdatapointcollection/copyto)(Array, int) | 复制到指定的数组。 |
| [GetEnumerator](../../aspose.slides.charts/chartdatapointcollection/getenumerator)() | 返回一个枚举器，用于遍历集合。 |
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/chartdatapointcollection/getorcreatedatapointbyidx)(uint) | 如果集合已包含索引为 *index* 的数据点，则返回该数据点。如果集合不包含索引为 *index*==N（当集合中的数据点数量小于或等于 N）时，则添加缺失的数据点并返回最后一个（即请求的索引）。例如，集合索引为 {0, 1, 2}，请求的索引为 5。则方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}，并返回索引为 5 的数据点。 |
| [Remove](../../aspose.slides.charts/chartdatapointcollection/remove)(IChartDataPoint) | 移除指定的值。 |
| [RemoveAt](../../aspose.slides.charts/chartdatapointcollection/removeat)(int) | 移除指定索引处的元素。 |

### 另请参阅

* 类 [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* 类 [ChartSeries](../chartseries)
* 接口 [IChartDataPointCollection](../ichartdatapointcollection)
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->