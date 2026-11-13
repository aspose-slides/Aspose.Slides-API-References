---
title: ChartData
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili data yang digunakan untuk pemetaan bagan.
type: docs
url: /id/com.aspose.slides/chartdata/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Mewakili data yang digunakan untuk pemetaan bagan.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori bagan. |
| [getSeries()](#getSeries--) | Mendapatkan seri. |
| [getSeriesGroups()](#getSeriesGroups--) | Mendapatkan grup seri. |
| [getCategories()](#getCategories--) | Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jika false maka properti #getSecondaryCategories.getSecondaryCategories mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jika false maka properti #getSecondaryCategories.getSecondaryCategories mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Mendapatkan kategori sekunder jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true. |
| [readWorkbookStream()](#readWorkbookStream--) | Menulis workbook Excel yang terdapat secara internal ke dalam aliran memori. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Menginisialisasi workbook Excel yang terdapat secara internal dengan nilai yang ditentukan pengguna. |
| [getDataSourceType()](#getDataSourceType--) | Mewakili jalur workbook eksternal jika sumber data eksternal, null jika tidak. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Mewakili sumber data bagan. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Mendapatkan tipe workbook yang tersemat. |
| [getRange()](#getRange--) | Mendapatkan rentang data bagan. |
| [setRange(String formula)](#setRange-java.lang.String-) | Menetapkan rentang data bagan. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Menetapkan workbook eksternal sebagai sumber data untuk bagan. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Menetapkan workbook eksternal sebagai sumber data untuk bagan. |
| [refreshData()](#refreshData--) | Menyegarkan data bagan dengan memuat ulang dari workbook sumber. |
| [switchRowColumn()](#switchRowColumn--) | Menukar data di atas sumbu. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori bagan. Baca-saja [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Mengembalikan:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Mendapatkan seri. Baca-saja [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Mengembalikan:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Mendapatkan grup seri. Baca-saja [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan baik pada sumbu utama atau pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan jenis pemetaan utama/sekunder. 

**Mengembalikan:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false). Baca-saja [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getCategories()
>  }
```

Jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false maka properti (#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika properti ... bernilai true maka data dalam properti (#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data dalam properti #getCategories.getCategories digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Jika false maka properti #getSecondaryCategories.getSecondaryCategories mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika true maka data dalam properti #getSecondaryCategories.getSecondaryCategories digunakan untuk seri sekunder dan data dalam properti #getCategories.getCategories digunakan untuk seri utama. Baca/tulis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

**Mengembalikan:** boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Jika false maka properti #getSecondaryCategories.getSecondaryCategories mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika true maka data dalam properti #getSecondaryCategories.getSecondaryCategories digunakan untuk seri sekunder dan data dalam properti #getCategories.getCategories digunakan untuk seri utama. Baca/tulis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Mendapatkan kategori sekunder jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true. Baca-saja [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kategori yang terkait adalah series.getChart().getChartData().getCategories()
>  }
> ```

Jika properti #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false maka properti (#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data dalam properti #getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika properti ... bernilai true maka data dalam properti #getSecondaryCategories.getSecondaryCategories digunakan untuk seri sekunder dan data dalam properti #getCategories.getCategories digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Menulis workbook Excel yang terdapat secara internal ke dalam aliran memori.

**Mengembalikan:**
byte[] - Mengembalikan sebuah instance array byte yang berisi salinan workbook Excel yang terdapat secara internal.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Menginisialisasi workbook Excel yang terdapat secara internal dengan nilai yang ditentukan pengguna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ms | byte[] | Aliran yang diberikan pengguna yang berisi seluruh workbook Excel. |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Mewakili jalur workbook eksternal jika sumber data eksternal, null jika tidak.

**Mengembalikan:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Mewakili sumber data bagan.

**Mengembalikan:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Mendapatkan tipe workbook yang tersemat. Mengembalikan [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jika DataSourceType (#getDataSourceType.getDataSourceType) adalah [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Baca-saja [WorkbookType](../../com.aspose.slides/workbooktype).

**Mengembalikan:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Mendapatkan rentang data bagan.

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

**Mengembalikan:**
java.lang.String - Rumus rentang data sel. Contoh: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Menetapkan rentang data bagan. Seri dan kategori akan diperbarui berdasarkan rentang data baru. Jika jumlah seri dalam rentang data lebih besar daripada jumlah seri dalam data bagan, maka seri tambahan dengan tipe yang sama seperti seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Rumus rentang data sel. Contoh: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Menetapkan workbook eksternal sebagai sumber data untuk bagan. Data bagan akan diperbarui dari workbook target.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | java.lang.String | Path ke workbook target |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Menetapkan workbook eksternal sebagai sumber data untuk bagan.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| workbookPath | java.lang.String | Path ke workbook target |
| updateChartData | boolean | Jika nilai false hanya jalur workbook yang akan diperbarui. Data bagan tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia. Jika nilai true data bagan akan diperbarui dari workbook target. |
### refreshData() {#refreshData--}
```
public final void refreshData()
```

Menyegarkan data bagan dengan memuat ulang dari workbook sumber.

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

Menukar data di atas sumbu. Data yang dipetakan pada sumbu X akan pindah ke sumbu Y dan sebaliknya.