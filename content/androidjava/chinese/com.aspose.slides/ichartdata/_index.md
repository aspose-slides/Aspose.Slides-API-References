---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: 表示用于图表绘制的数据。
type: docs
url: /zh/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

表示用于图表绘制的数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 获取单元格工厂，以创建用于图表系列或类别的单元格。 |
| [getSeries()](#getSeries--) | 获取系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 获取系列组。 |
| [getCategories()](#getCategories--) | 获取主类别（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则获取主、次类别）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 true，则获取次类别。 |
| [readWorkbookStream()](#readWorkbookStream--) | 将内部包含的 Excel 工作簿写入内存流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 设置图表数据范围。 |
| [getRange()](#getRange--) | 获取图表数据范围。 |
| [getDataSourceType()](#getDataSourceType--) | 表示图表的数据源 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 如果数据源为外部，则表示外部工作簿路径，否则为 null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 获取嵌入工作簿的类型。 |
| [switchRowColumn()](#switchRowColumn--) | 交换轴上的数据。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 将外部工作簿设置为图表的数据源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 将外部工作簿设置为图表的数据源。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

获取单元格工厂，以创建用于图表系列或类别的单元格。只读 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回：**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

获取系列。只读 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回：**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

获取系列组。只读 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组使用 CombinableSeriesTypesGroup 枚举定义和描述。另外，每个系列组包含绘制在主坐标轴或次坐标轴上的系列（同一组中不会同时出现两种情况）。因此，系列分组的原则是按照上述类型组以及主/次坐标轴绘制类型进行分组。2) 系列组包含一些对该组中每个系列都通用的系列属性（“series group properties”）。ChartSeriesGroup 类中的 “Series group properties” 为读写。每个 “series group properties” 在 ChartSeries 类中可以有只读的投影。

**返回：**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

获取主类别（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则获取主、次类别）。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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
>      // 相关类别是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关类别是 series.getChart().getChartData().getCategories()
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
>      // 相关类别是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关类别是 series.getChart().getChartData().getCategories()
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
>      // 相关类别是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关类别是 series.getChart().getChartData().getCategories()
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
将内部包含的 Excel 工作簿写入内存流。

**Returns:**
byte[] - 返回一个字节数组，其中包含内部包含的 Excel 工作簿的副本。
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
| formula | java.lang.String | 单元格数据范围公式。例如：“Sheet1!$A$1:$C$4”、 “SomeSheetName!A1:B100”、 “Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5”。 |

### getRange() {#getRange--}
```
public abstract String getRange()
```
Gets chart data range.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```
表示图表的数据源

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Represents external workbook path if data source is external, null otherwise

**Returns:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```
获取嵌入工作簿的类型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 为 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，则返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。Read-only [WorkbookType](../../com.aspose.slides/workbooktype)。

**Returns:**
int
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


将外部工作簿设置为图表的数据源。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目标工作簿的路径 |
| updateChartData | boolean | 如果值为 false，仅更新工作簿路径。图表数据不会从目标工作簿加载和更新。可在目标工作簿不存在或不可用时使用。如果值为 true，则会从目标工作簿更新图表数据。 |