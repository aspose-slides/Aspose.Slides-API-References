---
title: ChartData
type: docs
weight: 0
url: /php-java/chartdata/
---

# ChartData class

 Represents data used for a chart plotting.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getCategories](/php-java/chartdata/getcategories/)() | IChartCategoryCollection | Gets the primary categories (or both primary and secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false). Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then ( #getSecondaryCategories) property return null and data in this #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in ( #getSecondaryCategories) property is used for secondary series and data in this #getCategories property is used for primary series. |
| [getChartDataWorkbook](/php-java/chartdata/getchartdataworkbook/)() | IChartDataWorkbook | Gets the cells factory to create cells used for chart series or categories. Read-only IChartDataWorkbook. |
| [getDataSourceType](/php-java/chartdata/getdatasourcetype/)() | int | Represents external workbook path if external data source, null otherwise |
| [getExternalWorkbookPath](/php-java/chartdata/getexternalworkbookpath/)() | String | Represents data source of the chart |
| [getRange](/php-java/chartdata/getrange/)() | String | Gets chart data range. |
| [getSecondaryCategories](/php-java/chartdata/getsecondarycategories/)() | IChartCategoryCollection | Gets the secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true. Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then this ( #getSecondaryCategories) property return null and data in #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in this #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. |
| [getSeries](/php-java/chartdata/getseries/)() | IChartSeriesCollection | Gets the series. Read-only IChartSeriesCollection. |
| [getSeriesGroups](/php-java/chartdata/getseriesgroups/)() | IChartSeriesGroupCollection | Gets the groups of series. Read-only IChartSeriesGroupCollection. 1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class. |
| [getUseSecondaryCategories](/php-java/chartdata/getusesecondarycategories/)() | boolean | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |
| [readWorkbookStream](/php-java/chartdata/readworkbookstream/)() | byte | Writes the internally contained Excel workbook it into an in-memory stream. |
| [setExternalWorkbook](/php-java/chartdata/setexternalworkbook/)(String) | void | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |
| [setExternalWorkbook](/php-java/chartdata/setexternalworkbook/)(String, boolean) | void | Sets external workbook as a data source for the chart. |
| [setRange](/php-java/chartdata/setrange/)(String) | void | Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection. |
| [setUseSecondaryCategories](/php-java/chartdata/setusesecondarycategories/)(boolean) | void | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |
| [switchRowColumn](/php-java/chartdata/switchrowcolumn/)() | void | Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa. |
| [writeWorkbookStream](/php-java/chartdata/writeworkbookstream/)(byte[]) | void | Initializes the internally contained Excel workbook with user-specified value. |
