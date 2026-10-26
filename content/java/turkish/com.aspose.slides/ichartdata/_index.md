---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Bir grafik çizimi için kullanılan verileri temsil eder.
type: docs
url: /tr/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Bir grafik çizimi için kullanılan verileri temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. |
| [getSeries()](#getSeries--) | Serileri alır. |
| [getSeriesGroups()](#getSeriesGroups--) | Seri gruplarını alır. |
| [getCategories()](#getCategories--) | Birincil kategorileri (veya \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte) alır. |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. |
| [getSecondaryCategories()](#getSecondaryCategories--) | (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) ) özelliği true ise ikincil kategorileri alır. |
| [readWorkbookStream()](#readWorkbookStream--) | Dahili tutulan Excel çalışma kitabını bellek içi bir akışa yazar. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Dahili tutulan Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır. |
| [setRange(String formula)](#setRange-java.lang.String-) | Grafik veri aralığını ayarlar. |
| [getRange()](#getRange--) | Grafik veri aralığını alır. |
| [getDataSourceType()](#getDataSourceType--) | Grafiğin veri kaynağını temsil eder |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Veri kaynağı harici ise harici çalışma kitabı yolunu temsil eder, aksi takdirde null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gömülü çalışma kitabının türünü alır. |
| [switchRowColumn()](#switchRowColumn--) | Verileri eksen boyunca değiştirir. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Grafik serileri veya kategorileri için kullanılan hücreleri oluşturmak üzere hücre fabrikasını alır. Yalnızca okunur [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Döndürür:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Serileri alır. Yalnızca okunur [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Döndürür:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Seri gruplarını alır. Yalnızca okunur [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Her seri grubu, birleştirilebilir türlere sahip serileri içerir. Birleştirilebilir seri türleri grupları, CombinableSeriesTypesGroup enum'ı ile tanımlanır ve açıklanır. Ayrıca her seri grubu, birincil eksenlerde ya da ikincil eksenlerde (aynı grup içinde her iki durumda da değil) çizilen serileri içerir. Dolayısıyla seri gruplandırma ilkesi, yukarıda belirtilen tür gruplarına ve birincil/ikincil çizim tipine göre gruplamadır. 2) Seri grubu, gruptaki her seri için ortak olan bazı seri özelliklerini ("seri grup özellikleri") içerir. ChartSeriesGroup sınıfındaki "Series group properties" okuma/yazma özelliktedir. Her "seri grup özelliği" ChartSeries sınıfında yalnızca okunur bir yansıtma içerebilir.

**Döndürür:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Birincil kategorileri (veya \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) özelliği false ise birincil ve ikincil kategorileri birlikte) alır. Yalnızca okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. True ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, bu (\#getCategories.getCategories) özelliğindeki veri ise birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. True ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri ise birincil seriler için kullanılır. Okunur/yazılabilir boolean.

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

False ise (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. True ise (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri ise birincil seriler için kullanılır. Okunur/yazılabilir boolean.

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

(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) ) özelliği true ise ikincil kategorileri alır. Yalnızca okunur [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

False ise bu (\#getSecondaryCategories.getSecondaryCategories) özelliği null döner ve (\#getCategories.getCategories) özelliğindeki veri birincil ve ikincil seriler için birlikte kullanılır. True ise bu (\#getSecondaryCategories.getSecondaryCategories) özelliğindeki veri ikincil seriler için, (\#getCategories.getCategories) özelliğindeki veri ise birincil seriler için kullanılır.

**Döndürür:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Dahili tutulan Excel çalışma kitabını bellek içi bir akışa yazar.

**Döndürür:**
byte[] - Dahili tutulan Excel çalışma kitabının bir kopyasını içeren bir bayt dizisi döndürür.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Dahili tutulan Excel çalışma kitabını kullanıcı tarafından belirtilen değerle başlatır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Kullanıcının sağladığı, tüm Excel çalışma kitabını içeren akış. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Grafik veri aralığını ayarlar. Seriler ve kategoriler yeni veri aralığına göre güncellenir. Veri aralığındaki seri sayısı grafik verisindeki seri sayısından büyükse, mevcut koleksiyondaki son serinin aynı türünde ek seriler koleksiyonun sonuna eklenir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Hücre veri aralığı formülü. Örneğin: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
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
java.lang.String - Hücre veri aralığı formülü. Örneğin: "Sheet1!$A$1:$C$4"
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

Veri kaynağı harici ise harici çalışma kitabı yolunu temsil eder, aksi takdirde null.

**Döndürür:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Gömülü çalışma kitabının türünü alır. DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ise [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) döndürür. Yalnızca okunur [WorkbookType](../../com.aspose.slides/workbooktype).

**Döndürür:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Verileri eksen boyunca değiştirir. X ekseninde çizilen veriler Y eksenine taşınır ve tersine.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar. Grafik verileri hedef çalışma kitabından güncellenir.

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

Harici çalışma kitabını grafik için veri kaynağı olarak ayarlar.

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
| updateChartData | boolean | Değer false ise yalnızca çalışma kitabı yolu güncellenir. Grafik verileri hedef çalışma kitabından yüklenmez ve güncellenmez. Hedef çalışma kitabı mevcut değilse ya da erişilemezse kullanılabilir. Değer true ise grafik verileri hedef çalışma kitabından güncellenir. |