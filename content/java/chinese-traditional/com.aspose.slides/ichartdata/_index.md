---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: 表示用於圖表繪製的資料。
type: docs
url: /zh-hant/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

表示用於圖表繪製的資料。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 取得儲存格工廠以建立用於圖表系列或類別的儲存格。 |
| [getSeries()](#getSeries--) | 取得系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 取得系列的群組。 |
| [getCategories()](#getCategories--) | 取得主要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要與次要類別）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 取得次要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 true）。 |
| [readWorkbookStream()](#readWorkbookStream--) | 將內部包含的 Excel 活頁簿寫入記憶體串流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 以使用者指定的值初始化內部包含的 Excel 活頁簿。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 設定圖表資料範圍。 |
| [getRange()](#getRange--) | 取得圖表資料範圍。 |
| [getDataSourceType()](#getDataSourceType--) | 表示圖表的資料來源。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 如果資料來源為外部，則表示外部活頁簿路徑，否則為 null。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 取得嵌入式活頁簿的類型。 |
| [switchRowColumn()](#switchRowColumn--) | 交換軸向上的資料。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 將外部活頁簿設為圖表的資料來源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 將外部活頁簿設為圖表的資料來源。 |
| [refreshData()](#refreshData--) | 透過從來源活頁簿重新載入來重新整理圖表資料。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

取得儲存格工廠以建立用於圖表系列或類別的儲存格。唯讀 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回：**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

取得系列。唯讀 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回：**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

取得系列的群組。唯讀 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每個系列群組包含具備可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup 列舉定義並說明。此外，每個系列群組包含的系列會繪製於主要坐標軸或次要坐標軸（不會同時在同一群組中同時於兩者）。因此，系列分組的原則是依上述類型群組以及主要/次要繪製類型進行分組。2) 系列群組包含一些對該群組中所有系列共通的屬性（「系列群組屬性」）。ChartSeriesGroup 類別中的「系列群組屬性」是讀寫的。每個「系列群組屬性」在 ChartSeries 類別中可能有唯讀的投影。

**返回：**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

取得主要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要與次要類別）。唯讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且此 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而此 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。讀寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別是 series.getChart().getChartData().getCategories()
>  }
> ```

**返回：**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。讀寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別是 series.getChart().getChartData().getCategories()
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

取得次要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 true）。唯讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關類別是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性回傳 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回：**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

將內部包含的 Excel 活頁簿寫入記憶體串流。

**返回：**
byte[] - 回傳包含內部 Excel 活頁簿副本的位元組陣列。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

以使用者指定的值初始化內部包含的 Excel 活頁簿。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ms | byte[] | 使用者提供的包含整個 Excel 活頁簿的串流。 |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

設定圖表資料範圍。系列和類別將根據新資料範圍進行更新。如果資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合末端新增與目前最後一個系列相同類型的額外系列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

取得圖表資料範圍。

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**返回：**
java.lang.String - 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

表示圖表的資料來源

**返回：**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

如果資料來源為外部，則表示外部活頁簿路徑；否則為 null

**返回：**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

取得嵌入式活頁簿的類型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 為 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，則回傳 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。唯讀 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回：**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

交換軸向上的資料。繪製於 X 軸的資料將移至 Y 軸，反之亦然。

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
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
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

將外部活頁簿設定為圖表的資料來源。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |
| updateChartData | boolean | 如果 value 為 false，則僅更新活頁簿路徑。圖表資料不會從目標活頁簿載入或更新。當目標活頁簿不存在或無法取得時可使用此方式。若 value 為 true，則圖表資料將從目標活頁簿更新。 |
### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

透過從來源活頁簿重新載入來重新整理圖表資料。

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