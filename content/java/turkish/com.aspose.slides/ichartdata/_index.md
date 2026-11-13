---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Grafik çizimi için kullanılan verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Grafik çizimi için kullanılan verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. |
| [getSeries()](#getSeries--) | Serileri alır. |
| [getSeriesGroups()](#getSeriesGroups--) | Seri gruplarını alır. |
| [getCategories()](#getCategories--) | Birincil kategorileri alır (veya (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği false ise birincil ve ikincil kategorileri birlikte alır). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. |
| [getSecondaryCategories()](#getSecondaryCategories--) | İkincil kategorileri alır eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği true ise. |
| [readWorkbookStream()](#readWorkbookStream--) | İçerdiği Excel çalışma kitabını bellek içi bir akışa yazar. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | İçerdiği Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır. |
| [setRange(String formula)](#setRange-java.lang.String-) | Grafik veri aralığını ayarlar. |
| [getRange()](#getRange--) | Grafik veri aralığını alır. |
| [getDataSourceType()](#getDataSourceType--) | Grafiğin veri kaynağını temsil eder. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Veri kaynağı dışsal ise dış çalışma kitabı yolunu temsil eder, aksi takdirde null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gömülü çalışma kitabının tipini alır. |
| [switchRowColumn()](#switchRowColumn--) | Veriyi eksen üzerinde değiştirir. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [refreshData()](#refreshData--) | Kaynak çalışma kitabından yeniden yükleyerek grafik verisini yeniler. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. Salt okunur [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Döndürür:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Serileri alır. Salt okunur [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Döndürür:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Seri gruplarını alır. Salt okunur [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Her seri grubu, birleştirilebilir türlere sahip serileri içerir. Birleştirilebilir seri türlerinin grupları CombinableSeriesTypesGroup enum ile tanımlanır ve açıklanır. Ayrıca her seri grubu, ya birincil eksenlerde ya da ikincil eksenlerde çizilen serileri içerir (her iki durumda bir grup içinde bulunmaz). Bu nedenle seri gruplandırma prensibi, yukarıda bahsedilen tip gruplarına ve birincil/ikincil çizim tipine göre yapılır. 2) Seri grubu, grup içindeki her seri için ortak bazı seri özelliklerine sahiptir (“seri grup özellikleri”). ChartSeriesGroup sınıfındaki “seri grup özellikleri” okunabilir/yazılabilir özelliktedir. Her “seri grup özelliği” ChartSeries sınıfında salt okunur bir projeksiyona sahip olabilir.

**Döndürür:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Birincil kategorileri alır (veya (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği false ise birincil ve ikincil kategorileri birlikte alır). Salt okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilgili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilgili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği false ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. Eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği true ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. True ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri birincil seriler için kullanılır. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilgili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilgili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

**Döndürür:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. True ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri birincil seriler için kullanılır. Okunabilir/yazılabilir boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilgili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilgili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

İkincil kategorileri alır eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği true ise. Salt okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilgili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilgili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği false ise bu (\#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve (\#getCategories.getCategories) özelliğindeki veri hem birincil hem de ikincil seriler için kullanılır. Eğer (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) özelliği true ise bu (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

İçerdiği Excel çalışma kitabını bellek içi bir akışa yazar.

**Döndürür:**
byte[] - İçerdiği Excel çalışma kitabının bir kopyasını içeren bayt dizisi döndürür.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

İçerdiği Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Kullanıcı tarafından sağlanan, tüm Excel çalışma kitabını içeren akış. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenecektir. Veri aralığındaki seri sayısı grafik veri sayısından büyükse, mevcut koleksiyondaki son serinin aynı tipinde ek seriler koleksiyonun sonuna eklenecektir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Hücre veri aralığı formülü. Örnek: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Grafik veri aralığını alır.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Döndürür:**
java.lang.String - Hücre veri aralığı formülü. Örnek: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Grafiğin veri kaynağını temsil eder

**Döndürür:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Veri kaynağı dışsal ise dış çalışma kitabı yolunu temsil eder, aksi takdirde null

**Döndürür:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Gömülü çalışma kitabının tipini alır. DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ise [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) döndürür. Salt okunur [WorkbookType](../../com.aspose.slides/workbooktype).

**Döndürür:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Veriyi eksen üzerinde değiştirir. X ekseninde çizilen veri Y eksenine, Y ekseninde çizilen veri X eksenine taşınır.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenir.

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

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Hedef çalışma kitabının yolu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Dış çalışma kitabını grafik için veri kaynağı olarak ayarlar.

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

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Hedef çalışma kitabının yolu |
| updateChartData | boolean | Değer false ise sadece çalışma kitabı yolu güncellenir. Grafik verileri hedef çalışma kitabından yüklenmez ve güncellenmez. Değer true ise grafik verileri hedef çalışma kitabından güncellenir. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler.

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