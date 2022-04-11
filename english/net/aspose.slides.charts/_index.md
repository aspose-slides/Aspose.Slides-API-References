---
title: Aspose.Slides.Charts
second_title: Aspose.Sildes for .NET API Reference
description: Contains classes for work with charts in Microsoft PowerPoint presentations.
type: docs
weight: 30
url: /net/aspose.slides.charts/
---
Contains classes for work with charts in Microsoft PowerPoint presentations.

## Classes

| Class | Description |
| --- | --- |
| class [AxesCompositionNotCombinableException](./axescompositionnotcombinableexception) | Exception which thrown when axes composition of the series is not combinable with present axes composition in chart. |
| class [AxesManager](./axesmanager) | Provides access to chart axes. |
| class [Axis](./axis) | Encapsulates the object that represents a chart's axis. |
| class [AxisFormat](./axisformat) | Represents chart format properties. |
| abstract class [BaseChartValue](./basechartvalue) | Represents a value of a chart. |
| class [CannotCombine2DAnd3DChartsException](./cannotcombine2dand3dchartsexception) | Exception which thrown when trying to combine 2D and 3D chart types. |
| class [Chart](./chart) | Represents an graphic chart on a slide. |
| class [ChartCategory](./chartcategory) | Represents chart categories. |
| class [ChartCategoryCollection](./chartcategorycollection) | Represents collection of [`ChartCategory`](aspose.slides.charts/chartcategory) |
| class [ChartCategoryLevelsManager](./chartcategorylevelsmanager) | Managed container of the values of the chart category levels. |
| class [ChartCellCollection](./chartcellcollection) | Represents collection of a cells with data. |
| class [ChartData](./chartdata) | Represents data used for a chart plotting. |
| class [ChartDataCell](./chartdatacell) | Represents cell for chart data. |
| class [ChartDataPoint](./chartdatapoint) | Represents series data point. |
| class [ChartDataPointCollection](./chartdatapointcollection) | Represents collection of a series data point. |
| class [ChartDataPointLevel](./chartdatapointlevel) | Represents data point level. Applies for Treemap and Sunburst chart. |
| class [ChartDataPointLevelsManager](./chartdatapointlevelsmanager) | Container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| class [ChartDataWorkbook](./chartdataworkbook) | Provides access to embedded Excel workbook |
| class [ChartDataWorksheet](./chartdataworksheet) | Represents worksheet associated with [`IChartDataCell`](aspose.slides.charts/ichartdatacell) |
| class [ChartDataWorksheetCollection](./chartdataworksheetcollection) | Represents the collection of worksheets of chart data workbook. |
| class [ChartLinesFormat](./chartlinesformat) | Represents gridlines format properties. |
| class [ChartPlotArea](./chartplotarea) | Represents rectangle where chart should be plotted. |
| class [ChartPortionFormat](./chartportionformat) | This class contains the chart portion formatting properties used in charts. Unlike [`IPortionFormatEffectiveData`](aspose.slides/iportionformateffectivedata), all properties of this class are writeable. |
| class [ChartSeries](./chartseries) | Represents a chart series. |
| class [ChartSeriesCollection](./chartseriescollection) | Represents collection of [`ChartSeries`](aspose.slides.charts/chartseries) |
| class [ChartSeriesGroup](./chartseriesgroup) | Represents group of series. |
| class [ChartTextFormat](./charttextformat) | Specifies default text formatting for chart text elements. |
| class [ChartTitle](./charttitle) | Represents chart title properties. |
| static class [ChartTypeCharacterizer](./charttypecharacterizer) | Helper for getting additional information about charts and series by its ChartType. |
| class [ChartWall](./chartwall) | Represents walls on 3d charts. |
| class [DataLabel](./datalabel) | Represents a series labels. |
| class [DataLabelCollection](./datalabelcollection) | Represents a series labels. |
| class [DataLabelFormat](./datalabelformat) | Represents formatting options for DataLabel. |
| class [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues) | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list |
| class [DataTable](./datatable) | Represents data table properties. |
| class [DoubleChartValue](./doublechartvalue) | Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| class [ErrorBarsCustomValues](./errorbarscustomvalues) | Specifies the errors bar values. It shall be used only when the Error bars value type is Custom. |
| class [ErrorBarsFormat](./errorbarsformat) | Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [`ErrorBarsCustomValues`](aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) property). |
| class [Format](./format) | Represents chart format properties. |
| class [Legend](./legend) | Represents chart's legend properties. |
| class [LegendEntryCollection](./legendentrycollection) | Represents legends collection. |
| class [LegendEntryProperties](./legendentryproperties) | Represents legend properties of a chart. |
| class [Marker](./marker) | Represents marker of a chert. |
| class [PieSplitCustomPointCollection](./piesplitcustompointcollection) | Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split. |
| class [Rotation3D](./rotation3d) | Represents 3D rotation of a chart. |
| class [StringChartValue](./stringchartvalue) | Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| class [StringOrDoubleChartValue](./stringordoublechartvalue) | Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| class [Trendline](./trendline) | Class represents trend line of chart series |
| class [TrendlineCollection](./trendlinecollection) | Represents a collection of Trendline |
| class [UpDownBarsManager](./updownbarsmanager) | Provide access to up/down bars of Line- or Stock-chart. |
## Interfaces

| Interface | Description |
| --- | --- |
| interface [IActualLayout](./iactuallayout) | Specifies actual position of a chart element. |
| interface [IAxesManager](./iaxesmanager) | Provides access to chart axes. |
| interface [IAxis](./iaxis) | Encapsulates the object that represents a chart's axis. |
| interface [IAxisFormat](./iaxisformat) | Represents chart format properties. |
| interface [IBaseChartValue](./ibasechartvalue) | Represents a value of a chart. |
| interface [IChart](./ichart) | Represents an graphic chart on a slide. |
| interface [IChartCategory](./ichartcategory) | Represents chart categories. |
| interface [IChartCategoryCollection](./ichartcategorycollection) | Represents collection of [`IChartCategory`](aspose.slides.charts/ichartcategory) |
| interface [IChartCategoryLevelsManager](./ichartcategorylevelsmanager) | Managed container of the values of the chart category levels. |
| interface [IChartCellCollection](./ichartcellcollection) | Represents collection of a cells with data. |
| interface [IChartComponent](./ichartcomponent) | Represents a component of a chart. |
| interface [IChartData](./ichartdata) | Represents data used for a chart plotting. |
| interface [IChartDataCell](./ichartdatacell) | Represents cell for chart data. |
| interface [IChartDataPoint](./ichartdatapoint) | Represents series data point. |
| interface [IChartDataPointCollection](./ichartdatapointcollection) | Represents collection of a series data point. |
| interface [IChartDataPointLevel](./ichartdatapointlevel) | Represents data point level. Applies for Treemap and Sunburst chart. |
| interface [IChartDataPointLevelsManager](./ichartdatapointlevelsmanager) | Container of data point levels. Applied for Treeamp and Sunburst series. Data point levels indexing is zero-based. |
| interface [IChartDataWorkbook](./ichartdataworkbook) | Provides access to embedded Excel workbook |
| interface [IChartDataWorksheet](./ichartdataworksheet) | Represents worksheet associated with [`IChartDataCell`](aspose.slides.charts/ichartdatacell) |
| interface [IChartDataWorksheetCollection](./ichartdataworksheetcollection) | Represents the collection of worksheets of chart data workbook. |
| interface [IChartLinesFormat](./ichartlinesformat) | Represents gridlines format properties. |
| interface [IChartParagraphFormat](./ichartparagraphformat) | Represents a paragraph formatting properties of a chart. |
| interface [IChartPlotArea](./ichartplotarea) | Represents chart title properties. |
| interface [IChartPortionFormat](./ichartportionformat) | Represents the chart portion formatting properties used in charts. |
| interface [IChartSeries](./ichartseries) | Represents a chart series. |
| interface [IChartSeriesCollection](./ichartseriescollection) | Represents collection of [`IChartSeries`](aspose.slides.charts/ichartseries) |
| interface [IChartSeriesGroup](./ichartseriesgroup) | Represents group of series. |
| interface [IChartSeriesGroupCollection](./ichartseriesgroupcollection) | Represents the collection of groups of combinable series. |
| interface [IChartSeriesReadonlyCollection](./ichartseriesreadonlycollection) | Represents a readonly collection of [`IChartSeries`](aspose.slides.charts/ichartseries) |
| interface [IChartTextBlockFormat](./icharttextblockformat) | Represents formatting properties for chart text elements. |
| interface [IChartTextFormat](./icharttextformat) | Chart operate with restricted set of text format properties. IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat interfaces describe this restricted set. |
| interface [IChartTitle](./icharttitle) | Represents chart title properties. |
| interface [IChartWall](./ichartwall) | Represents walls on 3d charts. |
| interface [IDataLabel](./idatalabel) | Represents a series labels. |
| interface [IDataLabelCollection](./idatalabelcollection) | Represents a series labels. |
| interface [IDataLabelFormat](./idatalabelformat) | Represents formatting options for DataLabel. |
| interface [IDataSourceTypeForErrorBarsCustomValues](./idatasourcetypeforerrorbarscustomvalues) | Specifies types of values in ChartDataPoint.ErrorBarsCustomValues properties list |
| interface [IDataTable](./idatatable) | Represents data table properties. |
| interface [IDoubleChartValue](./idoublechartvalue) | Represent double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| interface [IErrorBarsCustomValues](./ierrorbarscustomvalues) | Specifies the errors bar values. It shall be used only when the Error bars value type is Custom. |
| interface [IErrorBarsFormat](./ierrorbarsformat) | Represents error bars of chart series. ErrorBars custom values are in IChartDataPointCollection (in [`ErrorBarsCustomValues`](aspose.slides.charts/ichartdatapoint/errorbarscustomvalues) property). |
| interface [IFormat](./iformat) | Represents chart format properties. |
| interface [IFormattedTextContainer](./iformattedtextcontainer) | Represents chart text format. |
| interface [ILayoutable](./ilayoutable) | Specifies the exact position of a chart element. |
| interface [ILegend](./ilegend) | Represents chart's legend properties. |
| interface [ILegendEntryCollection](./ilegendentrycollection) | Represents legends collection. |
| interface [ILegendEntryProperties](./ilegendentryproperties) | Represents legend properties of a chart. |
| interface [IMarker](./imarker) | Represents marker of a chert. |
| interface [IMultipleCellChartValue](./imultiplecellchartvalue) | Represents a collection of a chart cells. |
| interface [IOverridableText](./ioverridabletext) | Represents overridable text for a chart. |
| interface [IPieSplitCustomPointCollection](./ipiesplitcustompointcollection) | Represents a collection of points that shall be drawn in the second pie or bar on a bar-of-pie or pie-of-pie chart with a custom split. |
| interface [IRotation3D](./irotation3d) | Represents 3D rotation of a chart. |
| interface [ISingleCellChartValue](./isinglecellchartvalue) | Represents a chart data cell. |
| interface [IStringChartValue](./istringchartvalue) | Represent string value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| interface [IStringOrDoubleChartValue](./istringordoublechartvalue) | Represent string or double value which can be stored in pptx presentation document in two ways: 1) in cell/cells of workbook related to chart; 2) as literal value. |
| interface [ITrendline](./itrendline) | Class represents trend line of chart series |
| interface [ITrendlineCollection](./itrendlinecollection) | Represents a collection of TrendlineEx |
| interface [IUpDownBarsManager](./iupdownbarsmanager) | Provide access to up/down bars of Line- or Stock-chart. |
## Enumeration

| Enumeration | Description |
| --- | --- |
| enum [AxisAggregationType](./axisaggregationtype) | Represents aggregation type of category axis. Used with Histogram or HistogramPareto series only. |
| enum [AxisPositionType](./axispositiontype) | Determines a position of axis. |
| enum [BubbleSizeRepresentationType](./bubblesizerepresentationtype) | Specifies the possible ways to represent data as bubble chart sizes. |
| enum [CategoryAxisType](./categoryaxistype) | Represents a type of a category axis. |
| enum [ChartDataSourceType](./chartdatasourcetype) | Represents a type of data source of the chart |
| enum [ChartShapeType](./chartshapetype) | Represents a shape of chart. |
| enum [ChartType](./charttype) | Represents a type of chart. |
| enum [CombinableSeriesTypesGroup](./combinableseriestypesgroup) | Enumeration of groups of combinable series types. Each element relates to group of types of chart series that can persist simultaneously in one ChartSeriesGroup. For example: ChartType.PercentsStackedArea series cannot be simultaneously with ChartType.StackedArea series in one ChartSeriesGroup. But two or more ChartType.PercentsStackedArea can be in one ChartSeriesGroup simultaneously (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). And ChartType.Line series can be with ChartType.LineWithMarkers series simultaneously in one CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup. |
| enum [CrossesType](./crossestype) | Determines where axis will cross. |
| enum [DataSourceType](./datasourcetype) | Data source types. |
| enum [DisplayBlanksAsType](./displayblanksastype) | Determines how missing data will be displayed. |
| enum [DisplayUnitType](./displayunittype) | Determines multiplicity of the displayed data. |
| enum [ErrorBarType](./errorbartype) | Represents type of error bar |
| enum [ErrorBarValueType](./errorbarvaluetype) | Represents type of error bar value |
| enum [LayoutTargetType](./layouttargettype) | If layout of the plot area defined manually this property specifies whether to layout the plot area by its inside (not including axis and axis labels) or outside (including axis and axis labels). |
| enum [LegendDataLabelPosition](./legenddatalabelposition) | Determines position of data labels. |
| enum [LegendPositionType](./legendpositiontype) | Determines a position of legend on a chart. |
| enum [MarkerStyleType](./markerstyletype) | Determines form of marker on chart's data point. |
| enum [ParentLabelLayoutType](./parentlabellayouttype) | Represents layout of category data labels. Used with Treemap series only. |
| enum [PictureType](./picturetype) | Determines mode of bar picture filling. |
| enum [PieSplitType](./piesplittype) | Represents a type of splitting points in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| enum [QuartileMethodType](./quartilemethodtype) | Returns type of quartile method |
| enum [StyleType](./styletype) | Represents chart style. |
| enum [TickLabelPositionType](./ticklabelpositiontype) | Represents the position type of tick-mark labels on the specified axis. |
| enum [TickMarkType](./tickmarktype) | Represents the tick mark type for the specified axis. |
| enum [TimeUnitType](./timeunittype) | Represents the base unit for the category axis |
| enum [TrendlineType](./trendlinetype) | Represents type of trend line |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
