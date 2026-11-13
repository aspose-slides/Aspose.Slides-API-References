---
title: ChartData
second_title: Aspose.Slides for Java API Referansı
description: Bir grafik çizimi için kullanılan verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/chartdata/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Bir grafik çizimi için kullanılan verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. |
| [getSeries()](#getSeries--) | Serileri alır. |
| [getSeriesGroups()](#getSeriesGroups--) | Seri gruplarını alır. |
| [getCategories()](#getCategories--) | Birincil kategorileri alır (veya #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte alır). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Eğer false ise #getSecondaryCategories.getSecondaryCategories özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Eğer false ise #getSecondaryCategories.getSecondaryCategories özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [getSecondaryCategories()](#getSecondaryCategories--) | İkincil kategorileri alır, eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise. |
| [readWorkbookStream()](#readWorkbookStream--) | Dahili bulunan Excel çalışma kitabını bellek içi akışa yazar. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Dahili bulunan Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır. |
| [getDataSourceType()](#getDataSourceType--) | Harici veri kaynağı ise harici çalışma kitabı yolunu temsil eder, aksi takdirde null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Grafiğin veri kaynağını temsil eder. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Yerleşik çalışma kitabının türünü alır. |
| [getRange()](#getRange--) | Grafik veri aralığını alır. |
| [setRange(String formula)](#setRange-java.lang.String-) | Grafik veri aralığını ayarlar. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [refreshData()](#refreshData--) | Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler. |
| [switchRowColumn()](#switchRowColumn--) | Verileri eksen üzerinde değiştirir. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. Yalnızca okunabilir [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Döndürür:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Serileri alır. Yalnızca okunabilir [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Döndürür:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Seri gruplarını alır. Yalnızca okunabilir [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Her seri grubu, birleşebilir tipte serileri içerir. Birleşebilir seri tipleri grupları CombinableSeriesTypesGroup enum'ı ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksende ya da ikincil eksende çizilen serileri içerir (her iki durum aynı grup içinde bulunmaz). Bu nedenle seri gruplama ilkesi, yukarıda belirtilen tip gruplarına ve birincil/ikincil çizim tipine göre gruplanmasıdır. 2) Seri grubu, grup içindeki tüm seriler için ortak olan bazı seri özelliklerini içerir ("seri grup özellikleri"). ChartSeriesGroup sınıfındaki "seri grup özellikleri" okunabilir/yazılabilir. "Seri grup özellikleri"nin her biri ChartSeries sınıfında yalnızca okunabilir bir yansıma sahip olabilir.

**Döndürür:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Birincil kategorileri alır (veya #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte alır). Yalnızca okunabilir [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise (#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise #getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, #getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Eğer false ise #getSecondaryCategories.getSecondaryCategories özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer true ise #getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, #getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır. Okunabilir/Yazılabilir boolean.

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
public final void setUseSecondaryCategories(boolean value)
```

Eğer false ise #getSecondaryCategories.getSecondaryCategories özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer true ise #getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, #getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır. Okunabilir/Yazılabilir boolean.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

İkincil kategorileri alır, eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise. Yalnızca okunabilir [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise bu (#getSecondaryCategories.getSecondaryCategories) özelliği null döndürür ve #getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise bu #getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, #getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Dahili bulunan Excel çalışma kitabını bellek içi akışa yazar.

**Döndürür:**
byte[] - İçsel bulunan Excel çalışma kitabının bir kopyasını içeren byte dizisi örneğini döndürür.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Dahili bulunan Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ms | byte[] | Kullanıcı tarafından sağlanan, tüm Excel çalışma kitabını içeren akış. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Harici veri kaynağı ise harici çalışma kitabı yolunu temsil eder, aksi takdirde null.

**Döndürür:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Grafiğin veri kaynağını temsil eder.

**Döndürür:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Yerleşik çalışma kitabının türünü alır. DataSourceType (#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ise [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) döndürür. Yalnızca okunabilir [WorkbookType](../../com.aspose.slides/workbooktype).

**Döndürür:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Grafik veri aralığını alır.

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

**Döndürür:**
java.lang.String - Hücre veri aralığı formülü. Örn: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenir. Veri aralığındaki seri sayısı grafik verisindeki seri sayısından büyükse, mevcut koleksiyonun son serisiyle aynı tipte ek seriler koleksiyonun sonuna eklenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | Hücre veri aralığı formülü. Örn: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verisi hedef çalışma kitabından güncellenecektir.

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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| workbookPath | java.lang.String | Hedef çalışma kitabının yolu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| workbookPath | java.lang.String | Hedef çalışma kitabının yolu |
| updateChartData | boolean | Değer false ise yalnızca çalışma kitabı yolu güncellenir. Grafik verisi hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut değilse ya da erişilemezse kullanılabilir. Değer true ise grafik verisi hedef çalışma kitabından güncellenir. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Kaynak çalışma kitabından yeniden yükleyerek grafik verilerini yeniler.

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

Verileri eksen üzerinde değiştirir. X ekseninde çizilen veri Y eksenine, Y ekseninde çizilen veri X eksenine taşınır.