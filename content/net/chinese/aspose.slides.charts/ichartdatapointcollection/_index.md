---  
title: IChartDataPointCollection
second_title: Aspose.Sildes for .NET API Reference  
description: 表示系列数据点的集合。
type: docs  
weight: 1750  
url: /zh/aspose.slides.charts/ichartdatapointcollection/
---  

## IChartDataPointCollection 接口  

表示系列数据点的集合。  

```csharp  
public interface IChartDataPointCollection : IGenericCollection<IChartDataPoint>  
```  

## 属性  

| 名称 | 描述 |  
| --- | --- |  
| [DataSourceTypeForBubbleSizes](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforbubblesizes) { get; set; } | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性在数据点的 BubbleSize 属性对象中是否有效。换句话说，它指定 ChartDataPointEx.BubbleSize.Data 属性的值类型。可读可写 [`DataSourceType`](../datasourcetype)。 |  
| [DataSourceTypeForErrorBarsCustomValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforerrorbarscustomvalues) { get; } | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中的值类型。只读 [`IDataSourceTypeForErrorBarsCustomValues`](../idatasourcetypeforerrorbarscustomvalues)。 |  
| [DataSourceTypeForValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforvalues) { get; set; } | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性在数据点的 Value 属性对象中是否有效。换句话说，它指定 ChartDataPoint.Value.Data 属性的值类型。可读可写 [`DataSourceType`](../datasourcetype)。 |  
| [DataSourceTypeForXValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforxvalues) { get; set; } | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性在数据点的 XValue 属性对象中是否有效。换句话说，它指定 ChartDataPointEx.XValue.Data 属性的值类型。可读可写 [`DataSourceType`](../datasourcetype)。 |  
| [DataSourceTypeForYValues](../../aspose.slides.charts/ichartdatapointcollection/datasourcetypeforyvalues) { get; set; } | 指定 AsCell、AsLiteralString 或 AsLiteralDouble 属性在数据点的 YValue 属性对象中是否有效。换句话说，它指定 ChartDataPointEx.YValue.Data 属性的值类型。可读可写 [`DataSourceType`](../datasourcetype)。 |  
| [Item](../../aspose.slides.charts/ichartdatapointcollection/item) { get; } | 通过索引（在此集合中的序号）返回系列数据点。（2 个索引器） |  

## 方法  

| 名称 | 描述 |  
| --- | --- |  
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。 |  
| [AddDataPointForAreaSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries#adddatapointforareaseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Area 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeArea(ChartType) 方法）。 |  
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。 |  
| [AddDataPointForBarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries#adddatapointforbarseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Column 或 Bar 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 和 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 方法）。 |  
| [AddDataPointForBoxAndWhiskerSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforboxandwhiskerseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 BoxAndWhisker 的系列。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_7)(double, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_6)(double, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_5)(double, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_4)(double, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_3)(IChartDataCell, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_2)(IChartDataCell, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_1)(IChartDataCell, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries)(IChartDataCell, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_11)(string, double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_10)(string, double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_9)(string, IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForBubbleSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforbubbleseries#adddatapointforbubbleseries_8)(string, IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Bubble 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeBubble(ChartType) 方法）。 |  
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。 |  
| [AddDataPointForDoughnutSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries#adddatapointfordoughnutseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Doughnut 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 方法）。 |  
| [AddDataPointForFunnelSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforfunnelseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Funnel 的系列。 |  
| [AddDataPointForHistogramSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforhistogramseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Histogram 的系列。 |  
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。 |  
| [AddDataPointForLineSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries#adddatapointforlineseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Line 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeLine(ChartType) 方法）。 |  
| [AddDataPointForMapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Map 的系列。 |  
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。 |  
| [AddDataPointForPieSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries#adddatapointforpieseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Pie 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypePie(ChartType) 方法）。 |  
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。 |  
| [AddDataPointForRadarSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforradarseries#adddatapointforradarseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Radar 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeRadar(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_3)(double, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_2)(double, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_1)(IChartDataCell, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries)(IChartDataCell, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_5)(string, double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForScatterSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforscatterseries#adddatapointforscatterseries_4)(string, IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Scatter 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeScatter(ChartType) 方法）。 |  
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。 |  
| [AddDataPointForStockSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries#adddatapointforstockseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Stock 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeStock(ChartType) 方法）。 |  
| [AddDataPointForSunburstSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsunburstseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Sunburst 的系列。 |  
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries_1)(double) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。 |  
| [AddDataPointForSurfaceSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries#adddatapointforsurfaceseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chartType 为 Surface 子类型之一的系列（另见 ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 方法）。 |  
| [AddDataPointForTreemapSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointfortreemapseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Treemap 的系列。 |  
| [AddDataPointForWaterfallSeries](../../aspose.slides.charts/ichartdatapointcollection/adddatapointforwaterfallseries)(IChartDataCell) | 创建新的数据点并将其添加到集合末尾。适用于 chart type 为 Waterfall 的系列。 |  
| [Clear](../../aspose.slides.charts/ichartdatapointcollection/clear)() | 从集合中移除所有元素。 |  
| [GetOrCreateDataPointByIdx](../../aspose.slides.charts/ichartdatapointcollection/getorcreatedatapointbyidx)(uint) | 如果集合中已包含索引为 *index* 的数据点，则返回该数据点。如果集合中不包含索引为 *index*==N 的数据点（即该集合中的数据点数量小于或等于 N），则添加缺失的数据点并返回最后一个（即具有请求索引的点）。例如，集合索引为 {0, 1, 2}，请求的索引为 5。然后该方法添加缺失的数据点：{0, 1, 2, 3, 4, 5}。并返回索引为 5 的数据点。 |  
| [Remove](../../aspose.slides.charts/ichartdatapointcollection/remove)(IChartDataPoint) | 移除指定的值。 |  
| [RemoveAt](../../aspose.slides.charts/ichartdatapointcollection/removeat)(int) | 移除给定索引处的元素。 |  

### 另请参阅  

* 接口 [IGenericCollection&lt;T&gt;](../../aspose.slides/igenericcollection-1)  
* 接口 [IChartDataPoint](../ichartdatapoint)  
* 命名空间 [Aspose.Slides.Charts](../../aspose.slides.charts)  
* 程序集 [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->