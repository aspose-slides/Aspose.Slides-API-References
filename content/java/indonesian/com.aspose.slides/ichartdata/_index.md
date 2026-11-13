---
title: IChartData
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili data yang digunakan untuk memplot diagram.
type: docs
url: /id/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Mewakili data yang digunakan untuk memplot diagram.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori diagram. |
| [getSeries()](#getSeries--) | Mendapatkan seri. |
| [getSeriesGroups()](#getSeriesGroups--) | Mendapatkan grup seri. |
| [getCategories()](#getCategories--) | Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jika false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jika false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Mendapatkan kategori sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true. |
| [readWorkbookStream()](#readWorkbookStream--) | Menulis buku kerja Excel yang terdapat di dalamnya ke dalam aliran memori. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Menginisialisasi buku kerja Excel yang terdapat di dalamnya dengan nilai yang ditentukan pengguna. |
| [setRange(String formula)](#setRange-java.lang.String-) | Mengatur rentang data diagram. |
| [getRange()](#getRange--) | Mendapatkan rentang data diagram. |
| [getDataSourceType()](#getDataSourceType--) | Mewakili sumber data diagram. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Mewakili jalur buku kerja eksternal jika sumber data bersifat eksternal, null jika tidak. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Mendapatkan tipe buku kerja yang disematkan. |
| [switchRowColumn()](#switchRowColumn--) | Menukar data pada sumbu. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. |
| [refreshData()](#refreshData--) | Menyegarkan data diagram dengan memuat ulang dari buku kerja sumber. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori diagram. Hanya-baca [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

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

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Juga setiap grup seri berisi seri yang dipetakan pada sumbu utama atau pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe pemetaan utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("series group properties"). "Series group properties" dalam kelas ChartSeriesGroup bersifat baca/tulis. Setiap "series group properties" dapat memiliki proyeksi hanya-baca dalam kelas ChartSeries.

**Mengembalikan:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false). Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Jika false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama. Baca/tulis boolean.

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

Jika false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama. Baca/tulis boolean.

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

Mendapatkan kategori sekunder jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true. Hanya-baca [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai false maka properti ini (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti (\#getCategories.getCategories) digunakan baik untuk seri utama maupun sekunder. Jika properti (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) bernilai true maka data pada properti ini (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti (\#getCategories.getCategories) digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Menulis buku kerja Excel yang terdapat di dalamnya ke dalam aliran memori.

**Mengembalikan:**
byte[] - Mengembalikan array byte yang berisi salinan buku kerja Excel yang terdapat di dalamnya.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Menginisialisasi buku kerja Excel yang terdapat di dalamnya dengan nilai yang ditentukan pengguna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ms | byte[] | Aliran yang disediakan pengguna yang berisi seluruh buku kerja Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Mengatur rentang data diagram. Seri dan kategori akan diperbarui berdasarkan rentang data baru. Jika jumlah seri dalam rentang data lebih besar dari jumlah seri dalam data diagram, maka seri tambahan dengan tipe yang sama dengan seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Formula rentang data sel. Misalnya: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Mendapatkan rentang data diagram.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Mengembalikan:**
java.lang.String - Formula rentang data sel. Misalnya: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Mewakili sumber data diagram

**Mengembalikan:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Mewakili jalur buku kerja eksternal jika sumber data bersifat eksternal, null jika tidak.

**Mengembalikan:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Mendapatkan tipe buku kerja yang disematkan. Mengembalikan [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jika DataSourceType (\#getDataSourceType.getDataSourceType) adalah [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Hanya-baca [WorkbookType](../../com.aspose.slides/workbooktype).

**Mengembalikan:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Menukar data pada sumbu. Data yang dipetakan pada sumbu X akan dipindahkan ke sumbu Y dan sebaliknya.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Menetapkan buku kerja eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari buku kerja target.

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
| workbookPath | java.lang.String | Jalur ke buku kerja target |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Menetapkan buku kerja eksternal sebagai sumber data untuk diagram.

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
| workbookPath | java.lang.String | Jalur ke buku kerja target |
| updateChartData | boolean | Jika nilai false, hanya jalur buku kerja yang akan diperbarui. Data diagram tidak akan dimuat dan diperbarui dari buku kerja target. Dapat digunakan saat buku kerja target tidak ada atau tidak tersedia. Jika nilai true, data diagram akan diperbarui dari buku kerja target. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Menyegarkan data diagram dengan memuat ulang dari buku kerja sumber.

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