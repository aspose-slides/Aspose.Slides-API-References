---
title: IChartData
second_title: Referensi API Aspose.Slides untuk Java
description: Merepresentasikan data yang digunakan untuk pembuatan diagram.
type: docs
url: /id/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Merepresentasikan data yang digunakan untuk pembuatan diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Mengambil pabrik sel untuk membuat sel yang digunakan untuk seri diagram atau kategori. |
| [getSeries()](#getSeries--) | Mengambil seri. |
| [getSeriesGroups()](#getSeriesGroups--) | Mengambil grup seri. |
| [getCategories()](#getCategories--) | Mengambil kategori utama (atau kategori utama dan sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jika false, maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jika false, maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Mengambil kategori sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true. |
| [readWorkbookStream()](#readWorkbookStream--) | Menulis workbook Excel yang disimpan secara internal ke dalam aliran memori. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Menginisialisasi workbook Excel yang disimpan secara internal dengan nilai yang ditentukan pengguna. |
| [setRange(String formula)](#setRange-java.lang.String-) | Atur rentang data diagram. |
| [getRange()](#getRange--) | Mengambil rentang data diagram. |
| [getDataSourceType()](#getDataSourceType--) | Merepresentasikan sumber data diagram |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Merepresentasikan path workbook eksternal jika sumber data bersifat eksternal, null jika tidak. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Mengambil tipe workbook tersemat. |
| [switchRowColumn()](#switchRowColumn--) | Menukar data pada sumbu. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Mengatur workbook eksternal sebagai sumber data untuk diagram. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Mengatur workbook eksternal sebagai sumber data untuk diagram. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Mengambil pabrik sel untuk membuat sel yang digunakan untuk seri diagram atau kategori. Hanya-baca [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Mengembalikan:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Mengambil seri. Hanya-baca [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Mengembalikan:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Mengambil grup seri. Hanya-baca [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Selain itu, setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" dalam kelas ChartSeriesGroup dapat dibaca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

**Mengembalikan:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Mengambil kategori utama (atau kategori utama dan sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false). Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika properti tersebut bernilai true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Jika false, maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika true, data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama. Boolean dapat dibaca/tulis.

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

Jika false, maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika true, data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama. Boolean dapat dibaca/tulis.

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

Mengambil kategori sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true. Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika properti tersebut bernilai true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Menulis workbook Excel yang disimpan secara internal ke dalam aliran memori.

**Mengembalikan:**
byte[] - Mengembalikan array byte yang berisi salinan dari workbook Excel yang disimpan secara internal.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Menginisialisasi workbook Excel yang disimpan secara internal dengan nilai yang ditentukan pengguna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ms | byte[] | Aliran yang disediakan pengguna berisi seluruh workbook Excel. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Atur rentang data diagram. Seri dan kategori akan diperbarui berdasarkan rentang data baru. Jika jumlah seri dalam rentang data lebih besar daripada jumlah seri dalam data diagram, seri tambahan dengan tipe yang sama seperti seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Rumus rentang data sel. Contoh: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

Mengambil rentang data diagram.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Mengembalikan:**
java.lang.String - Rumus rentang data sel. Contoh: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Merepresentasikan sumber data diagram

**Mengembalikan:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Merepresentasikan path workbook eksternal jika sumber data bersifat eksternal, null jika tidak

**Mengembalikan:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Mengambil tipe workbook tersemat. Mengembalikan [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jika DataSourceType (\#getDataSourceType.getDataSourceType) adalah [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Hanya-baca [WorkbookType](../../com.aspose.slides/workbooktype).

**Mengembalikan:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Menukar data pada sumbu. Data yang digambarkan pada sumbu X akan dipindahkan ke sumbu Y dan sebaliknya.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Mengatur workbook eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari workbook target.

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
| workbookPath | java.lang.String | Path ke workbook target |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Mengatur workbook eksternal sebagai sumber data untuk diagram.

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
| workbookPath | java.lang.String | Path ke workbook target |
| updateChartData | boolean | Jika nilai false, hanya path workbook yang akan diperbarui. Data diagram tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia. Jika nilai true, data diagram akan diperbarui dari workbook target. |