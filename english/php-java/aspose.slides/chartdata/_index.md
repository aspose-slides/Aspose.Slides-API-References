---
title: ChartData
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/chartdata/
---

## ChartData class

 Represents data used for a chart plotting.
 

## Methods

| Name | Description |
| --- | --- |
| [getCategories](getcategories)() | Gets the primary categories (or both primary and secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false). Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then ( #getSecondaryCategories) property return null and data in this #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in ( #getSecondaryCategories) property is used for secondary series and data in this #getCategories property is used for primary series. |
| [getChartDataWorkbook](getchartdataworkbook)() | Gets the cells factory to create cells used for chart series or categories. Read-only IChartDataWorkbook. |
| [getDataSourceType](getdatasourcetype)() | Represents external workbook path if external data source, null otherwise |
| [getExternalWorkbookPath](getexternalworkbookpath)() | Represents data source of the chart |
| [getRange](getrange)() | Gets chart data range. |
| [getSecondaryCategories](getsecondarycategories)() | Gets the secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true. Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then this ( #getSecondaryCategories) property return null and data in #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in this #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. |
| [getSeries](getseries)() | Gets the series. Read-only IChartSeriesCollection. |
| [getSeriesGroups](getseriesgroups)() | Gets the groups of series. Read-only IChartSeriesGroupCollection. 1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class. |
| [getUseSecondaryCategories](getusesecondarycategories)() | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |
| [readWorkbookStream](readworkbookstream)() | Writes the internally contained Excel workbook it into an in-memory stream. |
| [setExternalWorkbook](setexternalworkbook)(String) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [setExternalWorkbook](setexternalworkbook)(String, boolean) | Sets external workbook as a data source for the chart. |
| [setRange](setrange)(String) | Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection. |
| [setUseSecondaryCategories](setusesecondarycategories)(boolean) | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |
| [switchRowColumn](switchrowcolumn)() | Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa. |
| [writeWorkbookStream](writeworkbookstream)(byte[]) | Initializes the internally contained Excel workbook with user-specified value. |
