---
title: ChartData
second_title: Aspose.Slides for Java API 參考
description: 表示用於圖表繪製的資料。
type: docs
url: /zh-hant/com.aspose.slides/chartdata/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**已實作的介面:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

表示用於圖表繪製的資料。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | 取得用於建立圖表系列或類別的儲存格工廠。 |
| [getSeries()](#getSeries--) | 取得系列。 |
| [getSeriesGroups()](#getSeriesGroups--) | 取得系列的群組。 |
| [getCategories()](#getCategories--) | 取得主要類別（如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則取得主要與次要類別）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | 如果為 false，則 #getSecondaryCategories.getSecondaryCategories 屬性返回 null，且 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | 如果為 false，則 #getSecondaryCategories.getSecondaryCategories 屬性返回 null，且 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | 如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true，則取得次要類別。 |
| [readWorkbookStream()](#readWorkbookStream--) | 將內部包含的 Excel 活頁簿寫入記憶體串流中。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 使用使用者指定的值初始化內部包含的 Excel 活頁簿。 |
| [getDataSourceType()](#getDataSourceType--) | 表示外部資料來源時的活頁簿路徑，否則為 null。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | 表示圖表的資料來源。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 取得嵌入式活頁簿的類型。 |
| [getRange()](#getRange--) | 取得圖表資料範圍。 |
| [setRange(String formula)](#setRange-java.lang.String-) | 設定圖表資料範圍。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 將外部活頁簿設為圖表的資料來源。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 將外部活頁簿設為圖表的資料來源。 |
| [refreshData()](#refreshData--) | 透過從來源活頁簿重新載入來重新整理圖表資料。 |
| [switchRowColumn()](#switchRowColumn--) | 交換軸向上的資料。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

取得用於建立圖表系列或類別的儲存格工廠。只讀 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**返回值:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

取得系列。只讀 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**返回值:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

取得系列的群組。只讀 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 每個系列群組包含可組合類型的系列。可組合系列類型的群組以 CombinableSeriesTypesGroup 列舉定義並描述。此外，每個系列群組中的系列均在主軸或次軸上繪製（不會同時在同一群組中同時在兩個軸上）。因此，系列分組的原則是以上述類型群組以及主/次繪製類型進行分組。 2) 系列群組包含一些對群組中每個系列共同的屬性（「系列群組屬性」）。ChartSeriesGroup class 中的「系列群組屬性」為可讀寫。每個「系列群組屬性」在 ChartSeries class 中可有只讀的投射。

**返回值:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

取得主要類別（如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則取得主要與次要類別）。只讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

--------------------

如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則 (#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且此 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則 (#getSecondaryCategories.getSecondaryCategories) 屬性中的資料用於次要系列，而此 #getCategories.getCategories 屬性中的資料用於主要系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

如果為 false，則 #getSecondaryCategories.getSecondaryCategories 屬性返回 null，且 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。若為 true，則 #getSecondaryCategories.getSecondaryCategories 屬性中的資料用於次要系列，而 #getCategories.getCategories 屬性中的資料用於主要系列。可讀寫布林值。

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

**返回值:** boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

如果為 false，則 #getSecondaryCategories.getSecondaryCategories 屬性返回 null，且 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。若為 true，則 #getSecondaryCategories.getSecondaryCategories 屬性中的資料用於次要系列，而 #getCategories.getCategories 屬性中的資料用於主要系列。可讀寫布林值。

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

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 true，則取得次要類別。只讀 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

--------------------

如果 #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) 屬性為 false，則此 (#getSecondaryCategories.getSecondaryCategories) 屬性返回 null，且 #getCategories.getCategories 屬性中的資料同時用於主要與次要系列。若該屬性為 true，則此 #getSecondaryCategories.getSecondaryCategories 屬性中的資料用於次要系列，而 #getCategories.getCategories 屬性中的資料用於主要系列。

**返回值:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

將內部包含的 Excel 活頁簿寫入記憶體串流中。

**返回值:**
byte[] - 返回一個包含內部 Excel 活頁簿副本的位元組陣列實例。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

使用使用者指定的值初始化內部包含的 Excel 活頁簿。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| ms | byte[] | 使用者提供的包含整個 Excel 活頁簿的串流。 |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

表示外部資料來源時的活頁簿路徑，否則為 null。

**返回值:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

表示圖表的資料來源。

**返回值:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

取得嵌入式活頁簿的類型。如果 DataSourceType (#getDataSourceType.getDataSourceType) 為 [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)，則返回 [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)。只讀 [WorkbookType](../../com.aspose.slides/workbooktype)。

**返回值:**
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

**返回值:**
java.lang.String - 儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

設定圖表資料範圍。系列與類別將根據新的資料範圍更新。如果資料範圍中的系列數量大於圖表資料中的系列數量，則會在集合末端新增與目前最後一個系列相同類型的額外系列。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 儲存格資料範圍公式。例如："Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

將外部活頁簿設為圖表的資料來源。圖表資料將從目標活頁簿更新。

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

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

將外部活頁簿設為圖表的資料來源。

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

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 目標活頁簿的路徑 |
| updateChartData | boolean | 如果值為 false，僅會更新活頁簿路徑。圖表資料不會從目標活頁簿載入或更新。當目標活頁簿不存在或無法取得時可使用此方式。如果值為 true，圖表資料將從目標活頁簿更新。 |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

透過從來源活頁簿重新載入來重新整理圖表資料。

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

交換軸向上的資料。繪製在 X 軸上的資料會移至 Y 軸，反之亦然。