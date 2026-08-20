---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: 代表用於圖表繪製的資料。
type: docs
url: /zh-hant/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

代表用於圖表繪製的資料。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 取得用於建立圖表系列或分類之儲存格的工廠。 |
| [getSeries()](#getSeries--) | 取得系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 取得系列的群組。 |
| [getCategories()](#getCategories--) | 取得主要分類（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要與次要分類）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 取得次要分類（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 true）。 |
| [readWorkbookStream()](#readWorkbookStream--) | 將內部包含的 Excel 工作簿寫入記憶體流中。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用使用者指定的值初始化內部包含的 Excel 工作簿。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 設定圖表資料範圍。 |
| [getRange()](#getRange--) | 取得圖表資料範圍。 |
| [getDataSourceType()](#getDataSourceType--) | 表示圖表的資料來源 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 如果資料來源為外部，則表示外部工作簿路徑；否則為 null。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 取得內嵌工作簿的類型。 |
| [switchRowColumn()](#switchRowColumn--) | 交換軸向上的資料。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 將外部工作簿設定為圖表的資料來源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 將外部工作簿設定為圖表的資料來源。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

取得用於建立圖表系列或分類之儲存格的工廠。只讀 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

取得系列。只讀 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

取得系列的群組。只讀 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每個系列群組包含具有可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup 列舉定義並描述。此外，每個系列群組包含在主坐標軸或次坐標軸上繪製的系列（同一群組中不會同時出現在兩種情況）。因此，系列分組的原則是以上述類型群組以及主/次繪製類型為依據的分組。2) 系列群組包含在該群組中所有系列共同的某些屬性（「系列群組屬性」）。ChartSeriesGroup 類別中的「系列群組屬性」為讀/寫。每個「系列群組屬性」在 ChartSeries 類別中可有只讀的投影。

**返回:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

取得主要分類（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則同時取得主要與次要分類）。只讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的分類是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的分類是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且此 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而此 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。讀/寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的分類是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的分類是 series.getChart().getChartData().getCategories()
>  }
> ```

**返回:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

如果為 false，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若為 true，則 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。讀/寫 boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的分類是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的分類是 series.getChart().getChartData().getCategories()
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

取得次要分類（如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 true）。只讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 相關的分類是 series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 相關的分類是 series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

如果 (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) 屬性為 false，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 (\#getCategories.getCategories) 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則此 (\#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而 (\#getCategories.getCategories) 屬性中的資料用於主要系列。

**返回:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

將內部包含的 Excel 工作簿寫入記憶體流中。

**返回:**  
byte[] - 返回一個包含內部 Excel 工作簿副本的位元組陣列。

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

使用使用者指定的值初始化內部包含的 Excel 工作簿。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| ms | byte[] | 使用者提供的包含完整 Excel 工作簿的流。 |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

設定圖表資料範圍。系列與分類將根據新資料範圍進行更新。如果資料範圍中的系列數量大於圖表資料中的系列計數，則會在集合末端新增與目前最後一個系列相同類型的額外系列。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

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

**返回:**  
java.lang.String - 儲存格資料範圍公式。例如: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

表示圖表的資料來源

**返回:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

如果資料來源為外部，則表示外部工作簿路徑；否則為 null。

**返回:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

取得內嵌工作簿的類型。如果 DataSourceType (\#getDataSourceType.getDataSourceType) 為 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，則返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。只讀 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回:**  
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

交換軸向上的資料。原本繪製於 X 軸的資料將移至 Y 軸，反之亦然。

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

將外部工作簿設定為圖表的資料來源。圖表資料將從目標工作簿更新。

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

將外部工作簿設定為圖表的資料來源。

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
| updateChartData | boolean | 如果值為 false，僅會更新工作簿路徑。圖表資料不會從目標工作簿載入或更新。可在目標工作簿不存在或不可用時使用。如果值為 true，則會從目標工作簿更新圖表資料。 |