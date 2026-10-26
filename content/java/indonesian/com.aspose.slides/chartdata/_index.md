---
title: ChartData
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili data yang digunakan untuk plot grafik.
type: docs
url: /id/com.aspose.slides/chartdata/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Mewakili data yang digunakan untuk plot grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori grafik. |
| [getSeries()](#getSeries--) | Mendapatkan seri. |
| [getSeriesGroups()](#getSeriesGroups--) | Mendapatkan grup seri. |
| [getCategories()](#getCategories--) | Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jika false maka properti \#getSecondaryCategories.getSecondaryCategories mengembalikan null dan data pada properti \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jika false maka properti \#getSecondaryCategories.getSecondaryCategories mengembalikan null dan data pada properti \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Mendapatkan kategori sekunder jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true. |
| [readWorkbookStream()](#readWorkbookStream--) | Menulis workbook Excel yang berisi secara internal ke dalam stream memori. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Menginisialisasi workbook Excel yang berisi secara internal dengan nilai yang ditentukan pengguna. |
| [getDataSourceType()](#getDataSourceType--) | Mewakili jalur workbook eksternal jika sumber data eksternal, null jika tidak. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Mewakili sumber data diagram. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Mendapatkan tipe workbook yang disematkan. |
| [getRange()](#getRange--) | Mendapatkan rentang data diagram. |
| [setRange(String formula)](#setRange-java.lang.String-) | Mengatur rentang data diagram. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Menetapkan workbook eksternal sebagai sumber data untuk diagram. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Menetapkan workbook eksternal sebagai sumber data untuk diagram. |
| [switchRowColumn()](#switchRowColumn--) | Menukar data di atas sumbu. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Mendapatkan pabrik sel untuk membuat sel yang digunakan untuk seri atau kategori diagram. Baca-saja [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

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

1) Setiap grup seri berisi seri dengan tipe yang dapat digabungkan. Grup tipe seri yang dapat digabungkan didefinisikan dan dijelaskan dengan enum CombinableSeriesTypesGroup. Selain itu setiap grup seri berisi seri yang dipetakan baik pada sumbu utama maupun pada sumbu sekunder (tidak keduanya dalam satu grup). Jadi, prinsip pengelompokan seri adalah pengelompokan berdasarkan grup tipe yang disebutkan di atas dan berdasarkan tipe plot utama/sekunder. 2) Grup seri berisi beberapa properti seri yang umum untuk setiap seri dalam grup ("properti grup seri"). "Properti grup seri" pada kelas ChartSeriesGroup bersifat baca/tulis. Setiap "properti grup seri" dapat memiliki proyeksi baca-saja dalam kelas ChartSeries.

**Mengembalikan:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Mendapatkan kategori utama (atau kategori utama dan sekunder jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false). Baca-saja [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada properti \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada properti \#getCategories.getCategories digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Jika false maka properti \#getSecondaryCategories.getSecondaryCategories mengembalikan null dan data pada \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika true maka data pada \#getSecondaryCategories.getSecondaryCategories digunakan untuk seri sekunder dan data pada \#getCategories.getCategories digunakan untuk seri utama. Baca/tulis boolean.

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
public final void setUseSecondaryCategories(boolean value)
```

Jika false maka properti \#getSecondaryCategories.getSecondaryCategories mengembalikan null dan data pada \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika true maka data pada \#getSecondaryCategories.getSecondaryCategories digunakan untuk seri sekunder dan data pada \#getCategories.getCategories digunakan untuk seri utama. Baca/tulis boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Mendapatkan kategori sekunder jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true. Baca-saja [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai false maka properti (\#getSecondaryCategories.getSecondaryCategories) mengembalikan null dan data pada \#getCategories.getCategories digunakan baik untuk seri utama maupun sekunder. Jika properti \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) bernilai true maka data pada properti (\#getSecondaryCategories.getSecondaryCategories) digunakan untuk seri sekunder dan data pada \#getCategories.getCategories digunakan untuk seri utama.

**Mengembalikan:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Menulis workbook Excel yang berisi secara internal ke dalam stream memori.

**Mengembalikan:**
byte[] - Mengembalikan sebuah instance array byte yang berisi salinan workbook Excel yang berisi secara internal.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Menginisialisasi workbook Excel yang berisi secara internal dengan nilai yang ditentukan pengguna.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ms | byte[] | Stream yang disediakan pengguna yang berisi seluruh workbook Excel. |

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

Mewakili sumber data diagram.

**Mengembalikan:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Mendapatkan tipe workbook yang disematkan. Mengembalikan [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jika DataSourceType (\#getDataSourceType.getDataSourceType) adalah [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Baca-saja [WorkbookType](../../com.aspose.slides/workbooktype).

**Mengembalikan:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Mendapatkan rentang data diagram.

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
java.lang.String - Formula rentang data sel. Misalnya: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Mengatur rentang data diagram. Seri dan kategori akan diperbarui berdasarkan rentang data baru. Jika jumlah seri dalam rentang data lebih besar dari jumlah seri dalam data diagram, maka seri tambahan dengan tipe yang sama seperti seri terakhir dalam koleksi saat ini akan ditambahkan ke akhir koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Formula rentang data sel. Misalnya: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Menetapkan workbook eksternal sebagai sumber data untuk diagram. Data diagram akan diperbarui dari workbook target.

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
| workbookPath | java.lang.String | Jalur ke workbook target |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Menetapkan workbook eksternal sebagai sumber data untuk diagram.

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
| workbookPath | java.lang.String | Jalur ke workbook target |
| updateChartData | boolean | Jika nilai false, hanya jalur workbook yang akan diperbarui. Data diagram tidak akan dimuat dan diperbarui dari workbook target. Dapat digunakan ketika workbook target tidak ada atau tidak tersedia. Jika nilai true, data diagram akan diperbarui dari workbook target. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Menukar data di atas sumbu. Data yang dipetakan pada sumbu X akan berpindah ke sumbu Y dan sebaliknya.