---
title: ChartData
second_title: Aspose.Slides for Java API 参考
description: 表示用于图表绘制的数据。
type: docs
url: /zh/com.aspose.slides/chartdata/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

表示用于图表绘制的数据。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 获取用于创建图表系列或类别的单元格的工厂。 |
| [getSeries()](#getSeries--) | 获取系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 获取系列的组。 |
| [getCategories()](#getCategories--) | 获取主类别（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则获取主类别和次要类别）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果为 false，则 \#getSecondaryCategories.getSecondaryCategories 属性返回 null，且 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果为 false，则 \#getSecondaryCategories.getSecondaryCategories 属性返回 null，且 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 true，则获取次要类别。 |
| [readWorkbookStream()](#readWorkbookStream--) | 将内部包含的 Excel 工作簿写入内存流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用用户指定的值初始化内部包含的 Excel 工作簿。 |
| [getDataSourceType()](#getDataSourceType--) | 如果是外部数据源，则表示外部工作簿路径；否则为 null。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 表示图表的数据源。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 获取嵌入式工作簿的类型。 |
| [getRange()](#getRange--) | 获取图表数据范围。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 设置图表数据范围。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 将外部工作簿设置为图表的数据源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 将外部工作簿设置为图表的数据源。 |
| [switchRowColumn()](#switchRowColumn--) | 交换轴上的数据。 |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

获取用于创建图表系列或类别的单元格的工厂。只读 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回值：**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

获取系列。只读 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回值：**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

获取系列的组。只读 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

1) 每个系列组包含具有可组合类型的系列。使用 CombinableSeriesTypesGroup 枚举定义并描述可组合系列类型的组。每个系列组中的系列要么绘制在主坐标轴上，要么绘制在次坐标轴上（同一组中不会同时出现两种情况）。因此，系列分组的原则是按上述类型组以及主/次绘制类型进行分组。2) 系列组包含一些对组内所有系列通用的系列属性（“系列组属性”）。ChartSeriesGroup 类中的 “系列组属性” 为读写。每个 “系列组属性” 在 ChartSeries 类中可以有只读的投影。

**返回值：**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

获取主类别（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则获取主类别和次要类别）。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且此 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 true，则 (\#getSecondaryCategories.getSecondaryCategories) 属性中的数据用于次要系列，而此 \#getCategories.getCategories 属性中的数据用于主系列。

**返回值：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

如果为 false，则 \#getSecondaryCategories.getSecondaryCategories 属性返回 null，且 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 如果为 true，则 \#getSecondaryCategories.getSecondaryCategories 属性中的数据用于次要系列，\#getCategories.getCategories 属性中的数据用于主系列。 读写布尔型。

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

**返回值：**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

如果为 false，则 \#getSecondaryCategories.getSecondaryCategories 属性返回 null，且 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 如果为 true，则 \#getSecondaryCategories.getSecondaryCategories 属性中的数据用于次要系列，\#getCategories.getCategories 属性中的数据用于主系列。 读写布尔型。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 true，则获取次要类别。只读 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 false，则此 (\#getSecondaryCategories.getSecondaryCategories) 属性返回 null，且 \#getCategories.getCategories 属性中的数据同时用于主系列和次要系列。 如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 属性为 true，则此 \#getSecondaryCategories.getSecondaryCategories 属性中的数据用于次要系列，\#getCategories.getCategories 属性中的数据用于主系列。

**返回值：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

将内部包含的 Excel 工作簿写入内存流。

**返回值：**
byte[] - 返回包含内部 Excel 工作簿副本的字节数组实例。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

使用用户指定的值初始化内部包含的 Excel 工作簿。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ms | byte[] | 用户提供的包含整个 Excel 工作簿的流。 |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

如果是外部数据源，则表示外部工作簿路径；否则为 null。

**返回值：**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

表示图表的数据源。

**返回值：**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

获取嵌入式工作簿的类型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 为 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，则返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。只读 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回值：**
int
### getRange() {#getRange--}
```
public final String getRange()
```

获取图表数据范围。

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

**返回值：**
java.lang.String - 单元格数据范围公式。例如: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

设置图表数据范围。系列和类别将根据新的数据范围进行更新。如果数据范围中的系列数量大于图表数据中的系列计数，则会在当前集合末尾添加与当前最后一个系列类型相同的额外系列。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | 单元格数据范围公式。例如: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

将外部工作簿设置为图表的数据源。图表数据将从目标工作簿更新。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目标工作簿的路径 |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

将外部工作簿设置为图表的数据源。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目标工作簿的路径 |
| updateChartData | boolean | 如果值为 false，则仅更新工作簿路径。图表数据不会从目标工作簿加载和更新。当目标工作簿不存在或不可用时可使用此方式。如果值为 true，则图表数据将从目标工作簿更新。 |
### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

交换轴上的数据。绘制在 X 轴上的数据将移动到 Y 轴，反之亦然。