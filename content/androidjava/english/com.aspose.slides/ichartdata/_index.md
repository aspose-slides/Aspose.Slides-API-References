---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Represents data used for a chart plotting.
## Methods

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Gets the cells factory to create cells used for chart series or categories. |
| [getSeries()](#getSeries--) | Gets the series. |
| [getSeriesGroups()](#getSeriesGroups--) | Gets the groups of series. |
| [getCategories()](#getCategories--) | Gets the primary categories (or both primary and secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Gets the secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true. |
| [readWorkbookStream()](#readWorkbookStream--) | Writes the internally contained Excel workbook it into an in-memory stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initializes the internally contained Excel workbook with user-specified value. |
| [setRange(String formula)](#setRange-java.lang.String-) | Set chart data range. |
| [getRange()](#getRange--) | Gets chart data range. |
| [getDataSourceType()](#getDataSourceType--) | Represents data source of the chart |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Represents external workbook path if data source is external, null otherwise |
| [switchRowColumn()](#switchRowColumn--) | Swap the data over the axis. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Sets external workbook as a data source for the chart. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Sets external workbook as a data source for the chart. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Gets the cells factory to create cells used for chart series or categories. Read-only [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returns:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Gets the series. Read-only [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returns:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Gets the groups of series. Read-only [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

**Returns:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Gets the primary categories (or both primary and secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false). Read-only [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in this (\#getCategories.getCategories) property is used both for primary and secondary series. If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in this (\#getCategories.getCategories) property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

**Returns:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


Gets the secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true. Read-only [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false then this (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. If (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true then data in this (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in (\#getCategories.getCategories) property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Writes the internally contained Excel workbook it into an in-memory stream.

**Returns:**
byte[] - Returns an array of byte containing a copy of the internally contained Excel workbook.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Initializes the internally contained Excel workbook with user-specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


Gets chart data range.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Represents data source of the chart

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Represents external workbook path if data source is external, null otherwise

**Returns:**
java.lang.String
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Swap the data over the axis. Data being charted on the X axis will move to the Y axis and vice versa.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Sets external workbook as a data source for the chart.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

