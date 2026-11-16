---
title: Aspose.Slides.Charts
second_title: Aspose.Sildes .NET API 参考
description: 包含用于在 Microsoft PowerPoint 演示文稿中处理图表的类。
type: docs
weight: 40
url: /zh/aspose.slides.charts/
---
包含用于在 Microsoft PowerPoint 演示文稿中处理图表的类。

## 类

| 类 | 描述 |
| --- | --- |
| [AxesCompositionNotCombinableException](./axescompositionnotcombinableexception) | 当系列的轴组合无法与图表中当前的轴组合兼容时抛出的 Exception。 |
| [AxesManager](./axesmanager) | 提供对图表轴的访问。 |
| [Axis](./axis) | 封装表示图表轴的对象。 |
| [AxisFormat](./axisformat) | 表示图表格式属性。 |
| [BaseChartValue](./basechartvalue) | 表示图表的值。 |
| [CachedChartValue](./cachedchartvalue) | 表示已缓存的图表值（例如 X、Y、气泡大小或主要值）。 |
| [CannotCombine2DAnd3DChartsException](./cannotcombine2dand3dchartsexception) | 在尝试组合 2D 和 3D 图表类型时抛出的 Exception。 |
| [Chart](./chart) | 表示幻灯片上的图形图表。 |
| [ChartCategory](./chartcategory) | 表示图表类别。 |
| [ChartCategoryCollection](./chartcategorycollection) | 表示 [`ChartCategory`](../aspose.slides.charts/chartcategory) 的集合。 |
| [ChartCategoryLevelsManager](./chartcategorylevelsmanager) | 受管理的图表类别级别值容器。 |
| [ChartCellCollection](./chartcellcollection) | 表示包含数据的单元格集合。 |
| [ChartData](./chartdata) | 表示用于绘制图表的数据。 |
| [ChartDataCell](./chartdatacell) | 表示图表数据的单元格。 |
| [ChartDataPoint](./chartdatapoint) | 表示系列数据点。 |
| [ChartDataPointCollection](./chartdatapointcollection) | 表示系列数据点的集合。 |
| [ChartDataPointLevel](./chartdatapointlevel) | 表示数据点级别。适用于 Treemap 和 Sunburst 图表。 |
| [ChartDataPointLevelsManager](./chartdatapointlevelsmanager) | 数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别的索引从零开始。 |
| [ChartDataWorkbook](./chartdataworkbook) | 提供对嵌入式 Excel 工作簿的访问 |
| [ChartDataWorksheet](./chartdataworksheet) | 表示与 [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) 关联的工作表。 |
| [ChartDataWorksheetCollection](./chartdataworksheetcollection) | 表示图表数据工作簿的工作表集合。 |
| [ChartLinesFormat](./chartlinesformat) | 表示网格线格式属性。 |
| [ChartPlotArea](./chartplotarea) | 表示绘制图表的矩形区域。 |
| [ChartPortionFormat](./chartportionformat) | 此类包含图表中使用的图表部分格式属性。与 [`IPortionFormatEffectiveData`](../aspose.slides/iportionformateffectivedata) 不同，此类的所有属性均可写。 |
| [ChartSeries](./chartseries) | 表示图表序列。 |
| [ChartSeriesCollection](./chartseriescollection) | 表示 [`ChartSeries`](../aspose.slides.charts/chartseries) 的集合。 |
| [ChartSeriesGroup](./chartseriesgroup) | 表示序列组。 |
| [ChartTextFormat](./charttextformat) | 指定图表文本元素的默认文本格式。 |
| [ChartTitle](./charttitle) | 表示图表标题属性。 |
| [ChartTypeCharacterizer](./charttypecharacterizer) | 帮助获取关于图表及其序列的附加信息（基于 ChartType）。 |
| [ChartWall](./chartwall) | 表示 3D 图表的壁面。 |
| [DataLabel](./datalabel) | 表示系列标签。 |
| [DataLabelCollection](./datalabelcollection) | 表示系列标签。 |
| [DataLabelFormat](./datalabelformat) | 表示 DataLabel 的格式选项。 |
| [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues) | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中的值类型。 |
| [DataTable](./datatable) | 表示数据表属性。 |
| [DoubleChartValue](./doublechartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的双精度值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [ErrorBarsCustomValues](./errorbarscustomvalues) | 指定误差条的值。仅在误差条值类型为 Custom 时使用。 |
| [ErrorBarsFormat](./errorbarsformat) | 表示图表系列的误差条。误差条的自定义值位于 IChartDataPointCollection（在 [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) 属性中）。 |
| [Format](./format) | 表示图表格式属性。 |
| [Legend](./legend) | 表示图表图例属性。 |
| [LegendEntryCollection](./legendentrycollection) | 表示图例集合。 |
| [LegendEntryProperties](./legendentryproperties) | 表示图表的图例属性。 |
| [Marker](./marker) | 表示图表标记。 |
| [PieSplitCustomPointCollection](./piesplitcustompointcollection) | 表示在自定义拆分的条形饼图或饼形饼图中用于拆分点的点集合。 |
| [Rotation3D](./rotation3d) | 表示图表的 3D 旋转。 |
| [StringChartValue](./stringchartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的字符串值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [StringOrDoubleChartValue](./stringordoublechartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的字符串或双精度值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [Trendline](./trendline) | 类表示图表系列的趋势线。 |
| [TrendlineCollection](./trendlinecollection) | 表示 Trendline 的集合。 |
| [UpDownBarsManager](./updownbarsmanager) | 提供对折线图或股票图的上/下误差条的访问。 |

## 接口

| 接口 | 描述 |
| --- | --- |
| [IActualLayout](./iactuallayout) | 指定图表元素的实际位置。 |
| [IAxesManager](./iaxesmanager) | 提供对图表轴的访问。 |
| [IAxis](./iaxis) | 封装表示图表轴的对象。 |
| [IAxisFormat](./iaxisformat) | 表示图表格式属性。 |
| [IBaseChartValue](./ibasechartvalue) | 表示图表的值。 |
| [ICachedChartValue](./icachedchartvalue) | 表示已缓存的图表值（例如 X、Y、气泡大小或主要值）。 |
| [IChart](./ichart) | 表示幻灯片上的图形图表。 |
| [IChartCategory](./ichartcategory) | 表示图表类别。 |
| [IChartCategoryCollection](./ichartcategorycollection) | 表示 [`IChartCategory`](../aspose.slides.charts/ichartcategory) 的集合。 |
| [IChartCategoryLevelsManager](./ichartcategorylevelsmanager) | 受管理的图表类别级别值容器。 |
| [IChartCellCollection](./ichartcellcollection) | 表示包含数据的单元格集合。 |
| [IChartComponent](./ichartcomponent) | 表示图表的组件。 |
| [IChartData](./ichartdata) | 表示用于绘制图表的数据。 |
| [IChartDataCell](./ichartdatacell) | 表示图表数据的单元格。 |
| [IChartDataPoint](./ichartdatapoint) | 表示系列数据点。 |
| [IChartDataPointCollection](./ichartdatapointcollection) | 表示系列数据点的集合。 |
| [IChartDataPointLevel](./ichartdatapointlevel) | 表示数据点级别。适用于 Treemap 和 Sunburst 图表。 |
| [IChartDataPointLevelsManager](./ichartdatapointlevelsmanager) | 数据点级别的容器。适用于 Treeamp 和 Sunburst 系列。数据点级别的索引从零开始。 |
| [IChartDataWorkbook](./ichartdataworkbook) | 提供对嵌入式 Excel 工作簿的访问 |
| [IChartDataWorksheet](./ichartdataworksheet) | 表示与 [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) 关联的工作表。 |
| [IChartDataWorksheetCollection](./ichartdataworksheetcollection) | 表示图表数据工作簿的工作表集合。 |
| [IChartLinesFormat](./ichartlinesformat) | 表示网格线格式属性。 |
| [IChartParagraphFormat](./ichartparagraphformat) | 表示图表的段落格式属性。 |
| [IChartPlotArea](./ichartplotarea) | 表示图表标题属性。 |
| [IChartPortionFormat](./ichartportionformat) | 表示图表中使用的图表部分格式属性。 |
| [IChartSeries](./ichartseries) | 表示图表序列。 |
| [IChartSeriesCollection](./ichartseriescollection) | 表示 [`IChartSeries`](../aspose.slides.charts/ichartseries) 的集合。 |
| [IChartSeriesGroup](./ichartseriesgroup) | 表示序列组。 |
| [IChartSeriesGroupCollection](./ichartseriesgroupcollection) | 表示可组合序列组的集合。 |
| [IChartSeriesReadonlyCollection](./ichartseriesreadonlycollection) | 表示 [`IChartSeries`](../aspose.slides.charts/ichartseries) 的只读集合。 |
| [IChartTextBlockFormat](./icharttextblockformat) | 表示图表文本元素的格式属性。 |
| [IChartTextFormat](./icharttextformat) | 图表使用受限的文本格式属性集。IChartTextFormat、IChartTextBlockFormat、IChartParagraphFormat、IChartPortionFormat 接口描述了此受限集合。 |
| [IChartTitle](./icharttitle) | 表示图表标题属性。 |
| [IChartWall](./ichartwall) | 表示 3D 图表的壁面。 |
| [IDataLabel](./idatalabel) | 表示系列标签。 |
| [IDataLabelCollection](./idatalabelcollection) | 表示系列标签。 |
| [IDataLabelFormat](./idatalabelformat) | 表示 DataLabel 的格式选项。 |
| [IDataSourceTypeForErrorBarsCustomValues](./idatasourcetypeforerrorbarscustomvalues) | 指定 ChartDataPoint.ErrorBarsCustomValues 属性列表中的值类型。 |
| [IDataTable](./idatatable) | 表示数据表属性。 |
| [IDoubleChartValue](./idoublechartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的双精度值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [IErrorBarsCustomValues](./ierrorbarscustomvalues) | 指定误差条的值。仅在误差条值类型为 Custom 时使用。 |
| [IErrorBarsFormat](./ierrorbarsformat) | 表示图表系列的误差条。误差条的自定义值位于 IChartDataPointCollection（在 [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) 属性中）。 |
| [IFormat](./iformat) | 表示图表格式属性。 |
| [IFormattedTextContainer](./iformattedtextcontainer) | 表示图表文本格式。 |
| [ILayoutable](./ilayoutable) | 指定图表元素的精确位置。 |
| [ILegend](./ilegend) | 表示图表图例属性。 |
| [ILegendEntryCollection](./ilegendentrycollection) | 表示图例集合。 |
| [ILegendEntryProperties](./ilegendentryproperties) | 表示图表的图例属性。 |
| [IMarker](./imarker) | 表示图表标记。 |
| [IMultipleCellChartValue](./imultiplecellchartvalue) | 表示图表单元格的集合。 |
| [IOverridableText](./ioverridabletext) | 表示图表的可覆盖文本。 |
| [IPieSplitCustomPointCollection](./ipiesplitcustompointcollection) | 表示在自定义拆分的条形饼图或饼形饼图的第二个饼或条中绘制的点集合。 |
| [IRotation3D](./irotation3d) | 表示图表的 3D 旋转。 |
| [ISingleCellChartValue](./isinglecellchartvalue) | 表示图表数据单元格。 |
| [IStringChartValue](./istringchartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的字符串值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [IStringOrDoubleChartValue](./istringordoublechartvalue) | 表示可以以两种方式存储在 pptx 演示文稿中的字符串或双精度值：1) 存于与图表关联的工作簿的单元格/单元格中；2) 作为文字值。 |
| [ITrendline](./itrendline) | 类表示图表系列的趋势线。 |
| [ITrendlineCollection](./itrendlinecollection) | 表示 TrendlineEx 的集合。 |
| [IUpDownBarsManager](./iupdownbarsmanager) | 提供对折线图或股票图的上/下误差条的访问。 |

## 枚举

| 枚举 | 描述 |
| --- | --- |
| [AxisAggregationType](./axisaggregationtype) | 表示类别轴的聚合类型。仅用于 Histogram 或 HistogramPareto 系列。 |
| [AxisPositionType](./axispositiontype) | 确定轴的位置。 |
| [BubbleSizeRepresentationType](./bubblesizerepresentationtype) | 指定将数据表示为气泡图大小的可能方式。 |
| [CategoryAxisType](./categoryaxistype) | 表示类别轴的类型。 |
| [ChartDataSourceType](./chartdatasourcetype) | 表示图表的数据源类型。 |
| [ChartShapeType](./chartshapetype) | 表示图表的形状。 |
| [ChartType](./charttype) | 表示图表的类型。 |
| [CombinableSeriesTypesGroup](./combinableseriestypesgroup) | 可组合序列类型组的枚举。每个元素对应于可以在同一 ChartSeriesGroup 中同时存在的图表序列类型组。例如：ChartType.PercentsStackedArea 系列不能与 ChartType.StackedArea 系列在同一 ChartSeriesGroup 中同时存在。但两个或更多 ChartType.PercentsStackedArea 可以同时位于同一 ChartSeriesGroup（CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea）。并且 ChartType.Line 系列可以与 ChartType.LineWithMarkers 系列在同一 CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup 中同时存在。 |
| [CrossesType](./crossestype) | 确定轴的交叉位置。 |
| [DataSourceType](./datasourcetype) | 数据源类型。 |
| [DisplayBlanksAsType](./displayblanksastype) | 确定缺失数据的显示方式。 |
| [DisplayUnitType](./displayunittype) | 确定显示数据的多重性。 |
| [ErrorBarType](./errorbartype) | 表示误差条的类型。 |
| [ErrorBarValueType](./errorbarvaluetype) | 表示误差条值的类型。 |
| [LayoutTargetType](./layouttargettype) | 如果手动定义绘图区的布局，此属性指定是按内部（不包括轴和轴标签）还是外部（包括轴和轴标签）布局绘图区。 |
| [LegendDataLabelPosition](./legenddatalabelposition) | 确定数据标签的位置。 |
| [LegendPositionType](./legendpositiontype) | 确定图表中图例的位置。 |
| [MarkerStyleType](./markerstyletype) | 确定图表数据点上标记的形状。 |
| [ParentLabelLayoutType](./parentlabellayouttype) | 表示类别数据标签的布局。仅用于 Treemap 系列。 |
| [PictureType](./picturetype) | 确定条形图片填充模式。 |
| [PieSplitType](./piesplittype) | 表示在饼形饼图或条形饼图的第二个饼或条中拆分点的类型。 |
| [QuartileMethodType](./quartilemethodtype) | 返回四分位数方法的类型。 |
| [StyleType](./styletype) | 表示图表样式。 |
| [TickLabelPositionType](./ticklabelpositiontype) | 表示指定轴上刻度标签的位置类型。 |
| [TickMarkType](./tickmarktype) | 表示指定轴的刻度线类型。 |
| [TimeUnitType](./timeunittype) | 表示类别轴的基准单位。 |
| [TrendlineType](./trendlinetype) | 表示趋势线的类型。 |
| [WorkbookType](./workbooktype) | 指定 Open XML 工作簿文件的类型。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->