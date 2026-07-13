---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /id/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Mewakili data yang digunakan untuk memplot grafik.
## Metode

| Metode | Deskripsi |
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
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gets the type of the embedded workbook. |
| [switchRowColumn()](#switchRowColumn--) | Swap the data over the axis. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Sets external workbook as a data source for the chart. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Sets external workbook as a data source for the chart. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori grafik. Hanya-baca [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Mengembalikan:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Mendapatkan seri. Hanya-baca [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Mengembalikan:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Mendapatkan grup seri. Hanya-baca [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak kedua kasus dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup (“series group properties”). “Series group properties” dalam kelas ChartSeriesGroup dapat dibaca/tulis. Setiap “series group properties” dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

**Mengembalikan:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Mendapatkan kategori utama (atau baik kategori utama maupun sekunder jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false). Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false maka (\#getSecondaryCategories.getSecondaryCategories) property return null dan data dalam (\#getCategories.getCategories) property digunakan baik untuk seri utama maupun sekunder. Jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true maka data dalam (\#getSecondaryCategories.getSecondaryCategories) property digunakan untuk seri sekunder dan data dalam (\#getCategories.getCategories) property digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Jika false maka (\#getSecondaryCategories.getSecondaryCategories) property return null dan data dalam (\#getCategories.getCategories) property digunakan baik untuk seri utama maupun sekunder. Jika true maka data dalam (\#getSecondaryCategories.getSecondaryCategories) property digunakan untuk seri sekunder dan data dalam (\#getCategories.getCategories) property digunakan untuk seri utama. Baca/tulis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

**Mengembalikan:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Jika false maka (\#getSecondaryCategories.getSecondaryCategories) property return null dan data dalam (\#getCategories.getCategories) property digunakan baik untuk seri utama maupun sekunder. Jika true maka data dalam (\#getSecondaryCategories.getSecondaryCategories) property digunakan untuk seri sekunder dan data dalam (\#getCategories.getCategories) property digunakan untuk seri utama. Baca/tulis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Mendapatkan kategori sekunder jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true. Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

Jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false maka property (\#getSecondaryCategories.getSecondaryCategories) ini return null dan data dalam (\#getCategories.getCategories) property digunakan baik untuk seri utama maupun sekunder. Jika (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true maka data dalam property (\#getSecondaryCategories.getSecondaryCategories) ini digunakan untuk seri sekunder dan data dalam (\#getCategories.getCategories) property digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Writes the internally contained Excel workbook it into an in-memory stream.

**Mengembalikan:**
byte[] - Returns an array of byte containing a copy of the internally contained Excel workbook.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initializes the internally contained Excel workbook with user-specified value.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ms | byte[] | The user-supplied stream containing the entire Excel workbook. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Set chart data range. Series and categories will be updated based on new data range. If amount of series in data range greater than count of series in the chart data then additional series with the same type as a last series in the current collection will be added to the end of the collection.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | The cells data range formula. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Mendapatkan rentang data grafik.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Mengembalikan:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Represents data source of the chart

**Mengembalikan:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Represents external workbook path if data source is external, null otherwise

**Mengembalikan:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Gets the type of the embedded workbook. Returns [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) if  DataSourceType (\#getDataSourceType.getDataSourceType) is [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Read-only [WorkbookType](../../com.aspose.slides/workbooktype).

**Mengembalikan:**
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

**Parameter:**
| Parameter | Tipe | Deskripsi |
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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | java.lang.String | Path to the target workbook |
| updateChartData | boolean | Jika nilai false hanya jalur workbook yang akan diperbarui. Data grafik tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia. Jika nilai true data grafik akan diperbarui dari workbook target. |