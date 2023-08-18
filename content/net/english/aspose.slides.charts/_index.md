---
title: Aspose.Slides.Charts
second_title: Aspose.Sildes for .NET API Reference
description: Contains classes for work with charts in Microsoft PowerPoint presentations.
type: docs
weight: 30
url: /aspose.slides.charts/
---
Contains classes for work with charts in Microsoft PowerPoint presentations.

## Classes

| Class | Description |
| --- | --- |
| [AxesCompositionNotCombinableException](./axescompositionnotcombinableexception) | Exception which thrown when axes composition of the series is not combinable with present axes composition in chart. |
| [AxesManager](./axesmanager) | Provides access to chart axes. |
| [Axis](./axis) | Encapsulates the object that represents a chart's axis. |
| [AxisFormat](./axisformat) | Represents chart format properties. |
| [BaseChartValue](./basechartvalue) | Represents a value of a chart. |
| [CannotCombine2DAnd3DChartsException](./cannotcombine2dand3dchartsexception) | Exception which thrown when trying to combine 2D and 3D chart types. |
| [Chart](./chart) | Represents an graphic chart on a slide. |
| [ChartCategory](./chartcategory) | Represents chart categories. |
| [ChartCategoryCollection](./chartcategorycollection) | Represents collection of [`ChartCategory`](../aspose.slides.charts/chartcategory) |
| [ChartCategoryLevelsManager](./chartcategorylevelsmanager) | Managed container of the values of the chart category levels. |
| [ChartCellCollection](./chartcellcollection) | Represents collection of a cells with data. |
| [ChartData](./chartdata) | Represents data used for a chart plotting. |
| [ChartDataCell](./chartdatacell) | Represents cell for chart data. |
| [ChartDataPoint](./chartdatapoint) | Represents series data point. |
| [ChartDataPointCollection](./chartdatapointcollection) | Represents collection of a series data point. |
| [ChartDataPointLevel](./chartdatapointlevel) | Represents data point level. Applies for Treemap and Sunburst chart. |
| [ChartDataPointLevelsManager](./chartdatapointlevelsmanager) | Container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| [ChartDataWorkbook](./chartdataworkbook) | Provides access to embedded Excel workbook |
| [ChartDataWorksheet](./chartdataworksheet) | Represents worksheet associated with [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) |
| [ChartDataWorksheetCollection](./chartdataworksheetcollection) | Represents the collection of worksheets of chart data workbook. |
| [ChartLinesFormat](./chartlinesformat) | Represents gridlines format properties. |
| [ChartPlotArea](./chartplotarea) | Represents rectangle where chart should be plotted. |
| [ChartPortionFormat](./chartportionformat) | This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](../aspose.slides/iportionformateffectivedata), all properties of this class are writeable. |
| [ChartSeries](./chartseries) | Represents a chart series. |
| [ChartSeriesCollection](./chartseriescollection) | Represents collection of [`ChartSeries`](../aspose.slides.charts/chartseries) |
| [ChartSeriesGroup](./chartseriesgroup) | Represents group of series. |
| [ChartTextFormat](./charttextformat) | Specifies default text formatting for chart text elements. |
| [ChartTitle](./charttitle) | Represents chart title properties. |
| [ChartTypeCharacterizer](./charttypecharacterizer) | Helper for getting additional information about charts and series by its ChartType. |
| [ChartWall](./chartwall) | Represents walls on 3d charts. |
| [DataLabel](./datalabel) | Represents a series labels. |
| [DataLabelCollection](./datalabelcollection) | Represents a series labels. |
| [DataLabelFormat](./datalabelformat) | Represents formatting options for DataLabel. |
| [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues) | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list |
| [DataTable](./datatable) | Represents data table properties. |
| [DoubleChartValue](./doublechartvalue) | Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [ErrorBarsCustomValues](./errorbarscustomvalues) | Specifies the errors bar values. It shall be used only when the Error bars value type is Custom. |
| [ErrorBarsFormat](./errorbarsformat) | Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) property). |
| [Format](./format) | Represents chart format properties. |
| [Legend](./legend) | Represents chart's legend properties. |
| [LegendEntryCollection](./legendentrycollection) | Represents legends collection. |
| [LegendEntryProperties](./legendentryproperties) | Represents legend properties of a chart. |
| [Marker](./marker) | Represents marker of a chert. |
| [PieSplitCustomPointCollection](./piesplitcustompointcollection) | Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split. |
| [Rotation3D](./rotation3d) | Represents 3D rotation of a chart. |
| [StringChartValue](./stringchartvalue) | Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [StringOrDoubleChartValue](./stringordoublechartvalue) | Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [Trendline](./trendline) | Class represents trend line of chart series |
| [TrendlineCollection](./trendlinecollection) | Represents a collection of Trendline |
| [UpDownBarsManager](./updownbarsmanager) | Provide access to up/down bars of Line- or Stock-chart. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IActualLayout](./iactuallayout) | Specifies actual position of a chart element. |
| [IAxesManager](./iaxesmanager) | Provides access to chart axes. |
| [IAxis](./iaxis) | Encapsulates the object that represents a chart's axis. |
| [IAxisFormat](./iaxisformat) | Represents chart format properties. |
| [IBaseChartValue](./ibasechartvalue) | Represents a value of a chart. |
| [IChart](./ichart) | Represents an graphic chart on a slide. |
| [IChartCategory](./ichartcategory) | Represents chart categories. |
| [IChartCategoryCollection](./ichartcategorycollection) | Represents collection of [`IChartCategory`](../aspose.slides.charts/ichartcategory) |
| [IChartCategoryLevelsManager](./ichartcategorylevelsmanager) | Managed container of the values of the chart category levels. |
| [IChartCellCollection](./ichartcellcollection) | Represents collection of a cells with data. |
| [IChartComponent](./ichartcomponent) | Represents a component of a chart. |
| [IChartData](./ichartdata) | Represents data used for a chart plotting. |
| [IChartDataCell](./ichartdatacell) | Represents cell for chart data. |
| [IChartDataPoint](./ichartdatapoint) | Represents series data point. |
| [IChartDataPointCollection](./ichartdatapointcollection) | Represents collection of a series data point. |
| [IChartDataPointLevel](./ichartdatapointlevel) | Represents data point level. Applies for Treemap and Sunburst chart. |
| [IChartDataPointLevelsManager](./ichartdatapointlevelsmanager) | Container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| [IChartDataWorkbook](./ichartdataworkbook) | Provides access to embedded Excel workbook |
| [IChartDataWorksheet](./ichartdataworksheet) | Represents worksheet associated with [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) |
| [IChartDataWorksheetCollection](./ichartdataworksheetcollection) | Represents the collection of worksheets of chart data workbook. |
| [IChartLinesFormat](./ichartlinesformat) | Represents gridlines format properties. |
| [IChartParagraphFormat](./ichartparagraphformat) | Represents a paragraph formatting properties of a chart. |
| [IChartPlotArea](./ichartplotarea) | Represents chart title properties. |
| [IChartPortionFormat](./ichartportionformat) | Represents the chart portion formatting properties used in charts. |
| [IChartSeries](./ichartseries) | Represents a chart series. |
| [IChartSeriesCollection](./ichartseriescollection) | Represents collection of [`IChartSeries`](../aspose.slides.charts/ichartseries) |
| [IChartSeriesGroup](./ichartseriesgroup) | Represents group of series. |
| [IChartSeriesGroupCollection](./ichartseriesgroupcollection) | Represents the collection of groups of combinable series. |
| [IChartSeriesReadonlyCollection](./ichartseriesreadonlycollection) | Represents a readonly collection of [`IChartSeries`](../aspose.slides.charts/ichartseries) |
| [IChartTextBlockFormat](./icharttextblockformat) | Represents formatting properties for chart text elements. |
| [IChartTextFormat](./icharttextformat) | Chart operate with restricted set of text format properties. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describe this restricted set. |
| [IChartTitle](./icharttitle) | Represents chart title properties. |
| [IChartWall](./ichartwall) | Represents walls on 3d charts. |
| [IDataLabel](./idatalabel) | Represents a series labels. |
| [IDataLabelCollection](./idatalabelcollection) | Represents a series labels. |
| [IDataLabelFormat](./idatalabelformat) | Represents formatting options for DataLabel. |
| [IDataSourceTypeForErrorBarsCustomValues](./idatasourcetypeforerrorbarscustomvalues) | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list |
| [IDataTable](./idatatable) | Represents data table properties. |
| [IDoubleChartValue](./idoublechartvalue) | Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [IErrorBarsCustomValues](./ierrorbarscustomvalues) | Specifies the errors bar values. It shall be used only when the Error bars value type is Custom. |
| [IErrorBarsFormat](./ierrorbarsformat) | Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) property). |
| [IFormat](./iformat) | Represents chart format properties. |
| [IFormattedTextContainer](./iformattedtextcontainer) | Represents chart text format. |
| [ILayoutable](./ilayoutable) | Specifies the exact position of a chart element. |
| [ILegend](./ilegend) | Represents chart's legend properties. |
| [ILegendEntryCollection](./ilegendentrycollection) | Represents legends collection. |
| [ILegendEntryProperties](./ilegendentryproperties) | Represents legend properties of a chart. |
| [IMarker](./imarker) | Represents marker of a chert. |
| [IMultipleCellChartValue](./imultiplecellchartvalue) | Represents a collection of a chart cells. |
| [IOverridableText](./ioverridabletext) | Represents overridable text for a chart. |
| [IPieSplitCustomPointCollection](./ipiesplitcustompointcollection) | Represents a collection of points that shall be drawn in the second pie or bar on a bar-of-pie or pie-of-pie chart with a custom split. |
| [IRotation3D](./irotation3d) | Represents 3D rotation of a chart. |
| [ISingleCellChartValue](./isinglecellchartvalue) | Represents a chart data cell. |
| [IStringChartValue](./istringchartvalue) | Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [IStringOrDoubleChartValue](./istringordoublechartvalue) | Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| [ITrendline](./itrendline) | Class represents trend line of chart series |
| [ITrendlineCollection](./itrendlinecollection) | Represents a collection of TrendlineEx |
| [IUpDownBarsManager](./iupdownbarsmanager) | Provide access to up/down bars of Line- or Stock-chart. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| [AxisAggregationType](./axisaggregationtype) | Represents aggregation type of category axis. Used with Histogram or HistogramPareto series only. |
| [AxisPositionType](./axispositiontype) | Determines a position of axis. |
| [BubbleSizeRepresentationType](./bubblesizerepresentationtype) | Specifies the possible ways to represent data as bubble chart sizes. |
| [CategoryAxisType](./categoryaxistype) | Represents a type of a category axis. |
| [ChartDataSourceType](./chartdatasourcetype) | Represents a type of data source of the chart |
| [ChartShapeType](./chartshapetype) | Represents a shape of chart. |
| [ChartType](./charttype) | Represents a type of chart. |
| [CombinableSeriesTypesGroup](./combinableseriestypesgroup) | Enumeration of groups of combinable series types. Each element relates to group of types of chart series that can persist simultaneously in one ChartSeriesGroup. For example: ChartType.PercentsStackedArea series cannot be simultaneously with ChartType.StackedArea series in one ChartSeriesGroup. But two or more ChartType.PercentsStackedArea can be in one ChartSeriesGroup simultaneously (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). And ChartType.Line series can be with ChartType.LineWithMarkers series simultaneously in one CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup. |
| [CrossesType](./crossestype) | Determines where axis will cross. |
| [DataSourceType](./datasourcetype) | Data source types. |
| [DisplayBlanksAsType](./displayblanksastype) | Determines how missing data will be displayed. |
| [DisplayUnitType](./displayunittype) | Determines multiplicity of the displayed data. |
| [ErrorBarType](./errorbartype) | Represents type of error bar |
| [ErrorBarValueType](./errorbarvaluetype) | Represents type of error bar value |
| [LayoutTargetType](./layouttargettype) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
| [LegendDataLabelPosition](./legenddatalabelposition) | Determines position of data labels. |
| [LegendPositionType](./legendpositiontype) | Determines a position of legend on a chart. |
| [MarkerStyleType](./markerstyletype) | Determines form of marker on chart's data point. |
| [ParentLabelLayoutType](./parentlabellayouttype) | Represents layout of category data labels. Used with Treemap series only. |
| [PictureType](./picturetype) | Determines mode of bar picture filling. |
| [PieSplitType](./piesplittype) | Represents a type of splitting points in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [QuartileMethodType](./quartilemethodtype) | Returns type of quartile method |
| [StyleType](./styletype) | Represents chart style. |
| [TickLabelPositionType](./ticklabelpositiontype) | Represents the position type of tick-mark labels on the specified axis. |
| [TickMarkType](./tickmarktype) | Represents the tick mark type for the specified axis. |
| [TimeUnitType](./timeunittype) | Represents the base unit for the category axis |
| [TrendlineType](./trendlinetype) | Represents type of trend line |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
