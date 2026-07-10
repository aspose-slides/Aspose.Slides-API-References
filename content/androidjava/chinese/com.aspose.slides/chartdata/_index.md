---
title: ChartData
second_title: Aspose.Slides for Android via Java API 参考
description: 表示用于图表绘制的数据。
type: docs
url: /zh/com.aspose.slides/chartdata/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**全部已实现接口：**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

表示用于图表绘制的数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 获取用于创建图表系列或分类的单元格工厂。 |
| [getSeries()](#getSeries--) | 获取系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 获取系列组。 |
| [getCategories()](#getCategories--) | 获取主分类（如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则返回主分类和次分类）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果为 false，则 #getSecondaryCategories.getSecondaryCategories 属性返回 null，#getCategories.getCategories 属性中的数据同时用于主系列和次系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果为 false，则 #getSecondaryCategories.getSecondaryCategories 属性返回 null，#getCategories.getCategories 属性中的数据同时用于主系列和次系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 true，则获取次分类。 |
| [readWorkbookStream()](#readWorkbookStream--) | 将内部包含的 Excel 工作簿写入内存流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |
| [getDataSourceType()](#getDataSourceType--) | 如果是外部数据源，则表示外部工作簿路径，否则为 null。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 表示图表的数据源。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 获取嵌入式工作簿的类型。 |
| [getRange()](#getRange--) | 获取图表数据范围。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 设置图表数据范围。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 将外部工作簿设为图表的数据源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 将外部工作簿设为图表的数据源。 |
| [switchRowColumn()](#switchRowColumn--) | 交换坐标轴上的数据。 |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

获取用于创建图表系列或分类的单元格工厂。只读 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回：**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

获取系列。只读 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回：**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

获取系列组。只读 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每个系列组包含具有可组合类型的系列。可组合系列类型的组由 CombinableSeriesTypesGroup 枚举定义并描述。另外，每个系列组中的系列只能在主坐标轴或次坐标轴上绘制（同一组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次绘制类型进行分组。2) 系列组包含一些对该组内所有系列通用的属性（“系列组属性”）。ChartSeriesGroup 类中的“系列组属性”是可读写的。每个“系列组属性”在 ChartSeries 类中都有只读投影。

**返回：**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

获取主分类（如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则返回主分类和次分类）。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in this \#getCategories.getCategories property is used both for primary and secondary series. If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true then data in (\#getSecondaryCategories.getSecondaryCategories) property is used for secondary series and data in this \#getCategories.getCategories property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```
If false then \#getSecondaryCategories.getSecondaryCategories property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If true then data in \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相关分类是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关分类是 series.getChart().getChartData().getCategories()
>  }
> ```

**Returns:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

If false then \#getSecondaryCategories.getSecondaryCategories property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If true then data in \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series. Read/write boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相关分类是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关分类是 series.getChart().getChartData().getCategories()
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```
Gets the secondary categories if \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true. Read-only [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相关分类是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关分类是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is false then this (\#getSecondaryCategories.getSecondaryCategories) property return null and data in \#getCategories.getCategories property is used both for primary and secondary series. If \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) property is true then data in this \#getSecondaryCategories.getSecondaryCategories property is used for secondary series and data in \#getCategories.getCategories property is used for primary series.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Writes the internally contained Excel workbook it into an in-memory stream.

**Returns:**
byte[] - Returns an instance of byte array containing a copy of the internally contained Excel workbook.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

使用用户指定的值初始化内部包含的 Excel 工作簿。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | 用户提供的包含整个 Excel 工作簿的流。 |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Represents external workbook path if external data source, null otherwise

**Returns:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Represents data source of the chart

**Returns:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Gets the type of the embedded workbook. Returns [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) if  DataSourceType (\#getDataSourceType.getDataSourceType) is [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Read-only [WorkbookType](../../com.aspose.slides/workbooktype).

**Returns:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Gets chart data range.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Sets external workbook as a data source for the chart.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |
| updateChartData | boolean | If value is false only workbook path will be updated. Chart data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()


交换坐标轴上的数据。图表在 X 轴上的数据将移动到 Y 轴，反之亦然。