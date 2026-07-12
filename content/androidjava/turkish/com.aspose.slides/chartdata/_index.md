---
title: ChartData
second_title: Aspose.Slides Android için, Java API Referansı aracılığıyla
description: Grafik çizimi için kullanılan verileri temsil eder.
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

Grafik çizimi için kullanılan verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak amacıyla hücre fabrikasını alır. |
| [getSeries()](#getSeries--) | Serileri alır. |
| [getSeriesGroups()](#getSeriesGroups--) | Seri gruplarını alır. |
| [getCategories()](#getCategories--) | Birincil kategorileri alır (veya \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte alır). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | False ise \#getSecondaryCategories.getSecondaryCategories özelliği null döner ve \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | False ise \#getSecondaryCategories.getSecondaryCategories özelliği null döner ve \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [getSecondaryCategories()](#getSecondaryCategories--) | İkincil kategorileri alır, eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise. |
| [readWorkbookStream()](#readWorkbookStream--) | İçerdiği Excel çalışma kitabını bellek içi akışa yazar. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | İçerdiği Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır. |
| [getDataSourceType()](#getDataSourceType--) | Harici veri kaynağı ise harici çalışma kitabı yolunu temsil eder, aksi halde null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Grafiğin veri kaynağını temsil eder. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gömülü çalışma kitabının türünü alır. |
| [getRange()](#getRange--) | Grafik veri aralığını alır. |
| [setRange(String formula)](#setRange-java.lang.String-) | Grafik veri aralığını ayarlar. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [switchRowColumn()](#switchRowColumn--) | Verileri eksen üzerinde değiştirir. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak amacıyla hücre fabrikasını alır. Salt okunur [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Döndürür:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Serileri alır. Salt okunur [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Döndürür:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Seri gruplarını alır. Salt okunur [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Her seri grubu, birlikte kullanılabilir türlerdeki serileri içerir. Birlikte kullanılabilir seri türleri grupları, CombinableSeriesTypesGroup enumu ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksende veya ikincil eksende çizilen serileri içerir (aynı grup içinde her iki durumda da olmaz). Bu nedenle seri gruplandırma prensibi, yukarıda belirtilen tür gruplarına ve birincil/ikincil çizim tipine göre yapılır. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini ("series group properties") barındırır. ChartSeriesGroup sınıfındaki "Series group properties" okunur/yazılır. "Series group properties" öğelerinin her biri ChartSeries sınıfında salt okunur bir yansımaya sahip olabilir.

**Döndürür:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Birincil kategorileri alır (veya \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte alır). Salt okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve bu \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, bu \#getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Eğer false ise \#getSecondaryCategories.getSecondaryCategories özelliği null döner ve \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer true ise \#getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, \#getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır. Okunur/yazılabilir boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

**Döndürür:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Eğer false ise \#getSecondaryCategories.getSecondaryCategories özelliği null döner ve \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer true ise \#getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, \#getCategories.getCategories özelliğindeki veri ise birincil seriler için kullanılır. Okunur/yazılabilir boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getCategories()
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

İkincil kategorileri alır, eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise. Salt okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // ilişkili kategoriler series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise bu (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve \#getCategories.getCategories özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. Eğer \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği true ise bu \#getSecondaryCategories.getSecondaryCategories özelliğindeki veri ikincil seriler için, \#getCategories.getCategories özelliğindeki veri birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

İçerdiği Excel çalışma kitabını bellek içi akışa yazar.

**Döndürür:**
byte[] - İçerdiği Excel çalışma kitabının bir kopyasını içeren bayt dizisi örneğini döndürür.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

İçerdiği Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ms | byte[] | Tam Excel çalışma kitabını içeren kullanıcı tarafından sağlanan akış. |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Harici veri kaynağı ise harici çalışma kitabı yolunu temsil eder, aksi halde null.

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

Gömülü çalışma kitabının türünü alır. DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ise [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) döndürür. Salt okunur [WorkbookType](../../com.aspose.slides/workbooktype).

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
java.lang.String - Hücre veri aralığı formülü. Örnek: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenecek. Eğer veri aralığındaki seri sayısı grafik verisindeki seri sayısından fazlaysa, mevcut koleksiyondaki son seriye aynı türde ek seriler koleksiyonun sonuna eklenecek.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| formula | java.lang.String | Hücre veri aralığı formülü. Örnek: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenecek.

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
| updateChartData | boolean | Değer false ise yalnızca çalışma kitabı yolu güncellenir. Grafik verileri hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut değilse veya erişilemezse kullanılabilir. Değer true ise grafik verileri hedef çalışma kitabından güncellenecektir. |
### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Verileri eksen üzerinde değiştirir. X ekseninde çizilen veriler Y eksenine taşınır ve tersine.