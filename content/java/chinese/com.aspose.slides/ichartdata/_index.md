---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: 表示用于绘制图表的数据。
type: docs
url: /zh/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

表示用于绘制图表的数据。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 获取用于创建图表系列或类别的单元格工厂。 |
| [getSeries()](#getSeries--) | 获取系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 获取系列的分组。 |
| [getCategories()](#getCategories--) | 获取主类别（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则获取主类别和次要类别）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 true，则获取次要类别。 |
| [readWorkbookStream()](#readWorkbookStream--) | 将内部包含的 Excel 工作簿写入内存流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 设置图表数据范围。 |
| [getRange()](#getRange--) | 获取图表数据范围。 |
| [getDataSourceType()](#getDataSourceType--) | 表示图表的数据源 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 如果数据源是外部的，则表示外部工作簿路径，否则为 null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 获取嵌入工作簿的类型。 |
| [switchRowColumn()](#switchRowColumn--) | 交换轴向上的数据。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 将外部工作簿设置为图表的数据源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 将外部工作簿设置为图表的数据源。 |
| [refreshData()](#refreshData--) | 通过从源工作簿重新加载来刷新图表数据。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


获取用于创建图表系列或类别的单元格工厂。只读 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回值:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


获取系列。只读 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回值:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


获取系列的分组。只读 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------
每个系列组包含具有可组合类型的系列。可组合系列类型的组使用 CombinableSeriesTypesGroup 枚举定义和描述。此外，每个系列组包含在主坐标轴或次坐标轴上绘制的系列（同一组中不会同时出现两种情况）。因此，系列分组的原则是按照上述类型组以及主/次坐标轴绘制类型进行分组。2) 系列组包含一些对组内每个系列都通用的属性（“系列组属性”）。ChartSeriesGroup 类中的 “系列组属性” 是可读写的。每个 “系列组属性” 在 ChartSeries 类中可以有只读的投影。

**返回值:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


获取主类别（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则获取主类别和次要类别）。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------
> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相关类别为 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相关类别为 series.getChart().getChartData().getCategories()
>  }
> ```
--------------------
如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且此 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。如果该属性为 true，则 (\#getSecondaryCategories.getSecondaryCategories) 属性中的数据用于次要系列，而此 (\#getCategories.getCategories) 属性中的数据用于主系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。如果为 true，则 (\#getSecondaryCategories.getSecondaryCategories) 属性中的数据用于次要系列，(\#getCategories.getCategories) 属性中的数据用于主系列。可读写布尔值。

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

**返回值:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


如果为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。如果为 true，则 (\#getSecondaryCategories.getSecondaryCategories) 属性中的数据用于次要系列，(\#getCategories.getCategories) 属性中的数据用于主系列。可读写布尔值。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 true，则获取次要类别。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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
如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 属性为 false，则此 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 (\#getCategories.getCategories) 属性中的数据同时用于主系列和次要系列。如果该属性为 true，则此 (\#getSecondaryCategories.getSecondaryCategories) 属性中的数据用于次要系列，且 (\#getCategories.getCategories) 属性中的数据用于主系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


将内部包含的 Excel 工作簿写入内存流。

**返回值:**
byte[] - 返回一个字节数组，其中包含内部嵌入的 Excel 工作簿的副本。

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


使用用户指定的值初始化内部包含的 Excel 工作簿。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ms | byte[] | 用户提供的包含整个 Excel 工作簿的流。 |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


设置图表数据范围。系列和类别将根据新的数据范围进行更新。如果数据范围中的系列数量大于图表数据中的系列数量，则会在集合末尾添加与当前集合中最后一个系列类型相同的附加系列。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | 单元格数据范围公式。例如："Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


获取图表数据范围。

--------------------
> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**返回值:**
java.lang.String - 单元格数据范围公式。例如："Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


表示图表的数据源

**返回值:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


如果数据源是外部的，则表示外部工作簿路径，否则为 null

**返回值:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


获取嵌入工作簿的类型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 为 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，则返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。只读 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回值:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


交换轴向上的数据。绘制在 X 轴上的数据将移至 Y 轴，反之亦然。

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


将外部工作簿设置为图表的数据源。图表数据将从目标工作簿进行更新。

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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目标工作簿的路径 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


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

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目标工作簿的路径 |
| updateChartData | boolean | 如果值为 false，则仅更新工作簿路径。图表数据将不会从目标工作簿加载并更新。可在目标工作簿不存在或不可用时使用。若值为 true，则图表数据将从目标工作簿更新。 |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```


通过从源工作簿重新加载来刷新图表数据。

--------------------
> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```