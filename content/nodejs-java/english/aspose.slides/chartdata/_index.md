---
title: ChartData
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/chartdata/
---

## ChartData class

 Represents data used for a chart plotting.
 
### getCategories {#getCategories}

| Name | Description |
| --- | --- |
| getCategories () | Gets the primary categories (or both primary and secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false). Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then ( #getSecondaryCategories) property return null and data in this #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in ( #getSecondaryCategories) property is used for secondary series and data in this #getCategories property is used for primary series. |

 **Returns:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getChartDataWorkbook {#getChartDataWorkbook}

| Name | Description |
| --- | --- |
| getChartDataWorkbook () | Gets the cells factory to create cells used for chart series or categories. Read-only IChartDataWorkbook. |

 **Returns:**
[ChartDataWorkbook](../chartdataworkbook)


---


### getDataSourceType {#getDataSourceType}

| Name | Description |
| --- | --- |
| getDataSourceType () | Represents external workbook path if external data source, null otherwise |

 **Returns:**
int


---


### getExternalWorkbookPath {#getExternalWorkbookPath}

| Name | Description |
| --- | --- |
| getExternalWorkbookPath () | Represents data source of the chart |

 **Returns:**
String


---


### getRange {#getRange}

| Name | Description |
| --- | --- |
| getRange () | Gets chart data range. |

 **Returns:**
String

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Chart doesn't use workbook as a data source |


---


### getSecondaryCategories {#getSecondaryCategories}

| Name | Description |
| --- | --- |
| getSecondaryCategories () | Gets the secondary categories if #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true. Read-only IChartCategoryCollection. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is false then this ( #getSecondaryCategories) property return null and data in #getCategories property is used both for primary and secondary series. If #getUseSecondaryCategories/ #setUseSecondaryCategories(boolean) property is true then data in this #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. |

 **Returns:**
[ChartCategoryCollection](../chartcategorycollection)


---


### getSeries {#getSeries}

| Name | Description |
| --- | --- |
| getSeries () | Gets the series. Read-only IChartSeriesCollection. |

 **Returns:**
[ChartSeriesCollection](../chartseriescollection)


---


### getSeriesGroups {#getSeriesGroups}

| Name | Description |
| --- | --- |
| getSeriesGroups () | Gets the groups of series. Read-only IChartSeriesGroupCollection. 1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class. |

 **Returns:**
ChartSeriesGroupCollection


---


### getUseSecondaryCategories {#getUseSecondaryCategories}

| Name | Description |
| --- | --- |
| getUseSecondaryCategories () | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |

 **Returns:**
boolean


---


### readWorkbookStream {#readWorkbookStream}

| Name | Description |
| --- | --- |
| readWorkbookStream () | Writes the internally contained Excel workbook it into an in-memory stream. |

 **Returns:**
byte


---


### setExternalWorkbook {#setExternalWorkbook}

| Name | Description |
| --- | --- |
| setExternalWorkbook (String) | Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


### setExternalWorkbook {#setExternalWorkbook}

| Name | Description |
| --- | --- |
| setExternalWorkbook (String, boolean) | Sets external workbook as a data source for the chart. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| workbookPath | String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

 **Error**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | External workbook is not available or can't be loaded. |


---


### setRange {#setRange}

| Name | Description |
| --- | --- |
| setRange (String) | Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| formula | String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentException | formula has incorrect format. |


---


### setUseSecondaryCategories {#setUseSecondaryCategories}

| Name | Description |
| --- | --- |
| setUseSecondaryCategories (boolean) | If false then #getSecondaryCategories property return null and data in #getCategories property is used both for primary and secondary series. If true then data in #getSecondaryCategories property is used for secondary series and data in #getCategories property is used for primary series. Read/write boolean. |


---


### switchRowColumn {#switchRowColumn}

| Name | Description |
| --- | --- |
| switchRowColumn () | Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa. |


---


### writeWorkbookStream {#writeWorkbookStream}

| Name | Description |
| --- | --- |
| writeWorkbookStream (byte[]) | Initializes the internally contained Excel workbook with user-specified value. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |


---


