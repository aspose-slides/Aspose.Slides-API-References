---
title: ChartData
second_title: Aspose.Slides for Java API 參考
description: 表示用於圖表繪製的資料。
type: docs
url: /zh-hant/com.aspose.slides/chartdata/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

表示用於繪製圖表的資料。
## Methods

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 取得用於建立圖表系列或類別之儲存格的工廠。 |
| [getSeries()](#getSeries--) | 取得系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 取得系列的群組。 |
| [getCategories()](#getCategories--) | 取得主要類別（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則同時取得主要和次要類別）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果為 false，則 \#getSecondaryCategories.getSecondaryCategories 屬性回傳 null，且 \#getCategories.getCategories 屬性中的資料同時用於主要和次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果為 false，則 \#getSecondaryCategories.getSecondaryCategories 屬性回傳 null，且 \#getCategories.getCategories 屬性中的資料同時用於主要和次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 取得次要類別（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true）。 |
| [readWorkbookStream()](#readWorkbookStream--) | 將內部包含的 Excel 活頁簿寫入記憶體串流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用使用者指定的值初始化內部包含的 Excel 活頁簿。 |
| [getDataSourceType()](#getDataSourceType--) | 若為外部資料來源，則表示外部活頁簿路徑，否則為 null。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 表示圖表的資料來源。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 取得嵌入式活頁簿的類型。 |
| [getRange()](#getRange--) | 取得圖表資料範圍。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 設定圖表資料範圍。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 將外部活頁簿設定為圖表的資料來源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 將外部活頁簿設定為圖表的資料來源。 |
| [switchRowColumn()](#switchRowColumn--) | 交換軸向上的資料。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

取得用於建立圖表系列或類別之儲存格的工廠。唯讀 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回：**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

取得系列。唯讀 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回：**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

取得系列的群組。唯讀 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

每個系列群組包含可组合类型的系列。可组合系列类型的群组使用 CombinableSeriesTypesGroup 枚举定义并描述。此外，每个系列群组包含绘制在主坐标轴或次坐标轴上的系列（同一群组中不会同时出现两种情况）。因此，系列分组的原则是按照上述类型群组以及主/次绘制类型进行分组。2）系列群组包含对该群组中每个系列通用的某些系列属性（“系列群组属性”）。ChartSeriesGroup 类中的 “系列群组属性” 为可读写。每个 “系列群组属性” 在 ChartSeries 类中可以有只读的投影。

**返回：**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

取得主要類別（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則同時取得主要和次要類別）。唯讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別為 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別為 series.getChart().getChartData().getCategories()
>  }
> ```


如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且資料在 \#getCategories.getCategories 屬性中同時用於主要和次要系列。若 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true，則資料在 (\#getSecondaryCategories.getSecondaryCategories) 屬性中用於次要系列，且資料在此 \#getCategories.getCategories 屬性中用於主要系列。

**返回：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

如果為 false，則 \#getSecondaryCategories.getSecondaryCategories 屬性回傳 null，且 \#getCategories.getCategories 屬性中的資料同時用於主要和次要系列。若為 true，則 \#getSecondaryCategories.getSecondaryCategories 屬性中的資料用於次要系列，\#getCategories.getCategories 屬性中的資料用於主要系列。可讀寫布林。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別為 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別為 series.getChart().getChartData().getCategories()
>  }
> ```


**返回：**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

如果為 false，則 \#getSecondaryCategories.getSecondaryCategories 屬性回傳 null，且 \#getCategories.getCategories 屬性中的資料同時用於主要和次要系列。若為 true，則 \#getSecondaryCategories.getSecondaryCategories 屬性中的資料用於次要系列，\#getCategories.getCategories 屬性中的資料用於主要系列。可讀寫布林。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別為 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別為 series.getChart().getChartData().getCategories()
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

取得次要類別（如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true）。唯讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別為 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別為 series.getChart().getChartData().getCategories()
>  }
> ```


如果 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且資料在 \#getCategories.getCategories 屬性中同時用於主要和次要系列。若 \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true，則資料在此 \#getSecondaryCategories.getSecondaryCategories 屬性中用於次要系列，且資料在 \#getCategories.getCategories 屬性中用於主要系列。

**返回：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

將內部包含的 Excel 活頁簿寫入記憶體串流。

**返回：**
byte[] - 回傳包含內部 Excel 活頁簿副本的位元組陣列實例。

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

使用使用者指定的值初始化內部包含的 Excel 活頁簿。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ms | byte[] | 使用者提供的、包含完整 Excel 活頁簿的串流。 |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

若為外部資料來源，則表示外部活頁簿路徑，否則為 null。

**返回：**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

表示圖表的資料來源。

**返回：**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

取得嵌入式活頁簿的類型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 為 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，則回傳 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。唯讀 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回：**
int

### getRange() {#getRange--}
```
public final String getRange()
```

取得圖表資料範圍。

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


**返回：**
java.lang.String - 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

設定圖表資料範圍。系列與類別將根據新資料範圍更新。如果資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合末端新增與最後一個系列相同類型的額外系列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

將外部活頁簿設定為圖表的資料來源。圖表資料將從目標活頁簿更新。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

將外部活頁簿設定為圖表的資料來源。

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


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |
| updateChartData | boolean | 如果值為 false，僅更新活頁簿路徑。圖表資料不會從目標活頁簿載入和更新。可在目標活頁簿不存在或無法取得時使用。如果值為 true，圖表資料將從目標活頁簿更新。 |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

交換軸向上的資料。原本在 X 軸上繪製的資料將移至 Y 軸，反之亦然。