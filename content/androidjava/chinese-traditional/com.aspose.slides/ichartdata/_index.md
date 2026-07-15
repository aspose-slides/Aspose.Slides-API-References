---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /zh-hant/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

表示用於圖表繪製的資料。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 取得用於建立圖表系列或類別之儲存格的工廠。 |
| [getSeries()](#getSeries--) | 取得系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 取得系列的群組。 |
| [getCategories()](#getCategories--) | 取得主要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要及次要類別）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 取得次要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 true）。 |
| [readWorkbookStream()](#readWorkbookStream--) | 將內部包含的 Excel 工作簿寫入記憶體中的串流。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用使用者指定的值初始化內部包含的 Excel 工作簿。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 設定圖表資料範圍。 |
| [getRange()](#getRange--) | 取得圖表資料範圍。 |
| [getDataSourceType()](#getDataSourceType--) | 表示圖表的資料來源 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 如果資料來源是外部，則表示外部工作簿路徑，否則為 null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 取得嵌入式工作簿的類型。 |
| [switchRowColumn()](#switchRowColumn--) | 交換軸向資料。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 將外部工作簿設為圖表的資料來源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 將外部工作簿設為圖表的資料來源。 |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

取得用於建立圖表系列或類別之儲存格的工廠。唯讀 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回值:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

取得系列。唯讀 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回值:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

取得系列的群組。唯讀 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每個系列群組包含可組合類型的系列。可組合系列類型的群組以 `CombinableSeriesTypesGroup` 列舉定義並說明。此外，每個系列群組內的系列會繪製於主要軸或次要軸（不會同時出現在同一群組中）。因此，系列分組的原則是依上述類型群組以及主要/次要繪製類型進行分組。2) 系列群組包含在群組內所有系列共用的屬性（「系列群組屬性」）。`ChartSeriesGroup` 類別中的「系列群組屬性」是可讀寫的。每個「系列群組屬性」在 `ChartSeries` 類別中可以有唯讀的投影。

**返回值:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

取得主要類別（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要及次要類別）。唯讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的類別是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且此 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。若屬性為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而此 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。可讀寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的類別是 series.getChart().getChartData().getCategories()
>  }
> ```

**返回值:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。可讀寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的類別是 series.getChart().getChartData().getCategories()
>  }
> ```

**參數:**
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
>      // 相關的類別是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的類別是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要和次要系列。若屬性為 true，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

將內部包含的 Excel 工作簿寫入記憶體中的串流。

**返回值:**
byte[] - 返回一個包含內部 Excel 工作簿副本的位元組陣列。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

使用使用者指定的值初始化內部包含的 Excel 工作簿。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ms | byte[] | 使用者提供的串流，包含完整的 Excel 工作簿。 |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

設定圖表資料範圍。系列和類別會根據新資料範圍更新。如果資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合末端新增與最後一個系列類型相同的額外系列。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

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

**返回值:**
java.lang.String - 儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

表示圖表的資料來源

**返回值:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

表示外部工作簿路徑（如果資料來源是外部），否則為 null

**返回值:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

取得嵌入式工作簿的類型。如果 `DataSourceType` (\#getDataSourceType.getDataSourceType) 為 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，則返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。唯讀 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回值:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

交換軸向資料。X 軸上的資料會移至 Y 軸，反之亦然。

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

將外部工作簿設為圖表的資料來源。圖表資料將根據目標工作簿更新。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標工作簿的路徑 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

將外部工作簿設為圖表的資料來源。

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

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標工作簿的路徑 |
| updateChartData | boolean | 若值為 false，僅更新工作簿路徑。圖表資料不會從目標工作簿載入或更新。可在目標工作簿不存在或無法取得時使用。若值為 true，則會從目標工作簿更新圖表資料。 |