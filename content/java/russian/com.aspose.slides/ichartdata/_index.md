---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /ru/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Представляет данные, используемые для построения диаграммы.
## Methods

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Получает фабрику ячеек для создания ячеек, используемых в серии диаграммы или категориях. |
| [getSeries()](#getSeries--) | Получает серии. |
| [getSeriesGroups()](#getSeriesGroups--) | Получает группы серий. |
| [getCategories()](#getCategories--) | Получает основные категории (или и основные, и вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Получает вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно true. |
| [readWorkbookStream()](#readWorkbookStream--) | Записывает внутреннюю книгу Excel в поток в памяти. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Инициализирует внутреннюю книгу Excel значением, указанным пользователем. |
| [setRange(String formula)](#setRange-java.lang.String-) | Устанавливает диапазон данных диаграммы. |
| [getRange()](#getRange--) | Получает диапазон данных диаграммы. |
| [getDataSourceType()](#getDataSourceType--) | Представляет источник данных диаграммы |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Представляет путь к внешней книге, если источник данных внешний, иначе null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Получает тип встроенной книги. |
| [switchRowColumn()](#switchRowColumn--) | Меняет местами данные по оси. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Получает фабрику ячеек для создания ячеек, используемых в серии диаграммы или категориях. Только для чтения [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Возвращает:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Получает серии. Только для чтения [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Возвращает:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Получает группы серий. Только для чтения [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Каждая группа серий содержит серии совместимых типов. Группы совместимых типов серий определяются и описываются перечислением CombinableSeriesTypesGroup. Также каждая группа содержит серии, которые отображаются либо на основных осях, либо на вторичных осях (не одновременно в одной группе). Таким образом, принцип группировки серий — группировка по типам групп, упомянутым выше, и по типу построения на основных/вторичных осях. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup являются чтением/записью. Каждое из «свойств группы серий» может иметь проекцию только для чтения в классе ChartSeries.

**Возвращает:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Получает основные категории (или и основные, и вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно false). Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные в этом свойстве (\#getCategories.getCategories) — для основных серий.

**Возвращает:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. Если true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные в свойстве (\#getCategories.getCategories) — для основных серий. Чтение/запись булевый тип.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории series.getChart().getChartData().getCategories()
>  }
> ```


**Возвращает:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. Если true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные в свойстве (\#getCategories.getCategories) — для основных серий. Чтение/запись булевый тип.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории series.getChart().getChartData().getCategories()
>  }
> ```

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


Получает вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно true. Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно false, то это свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных серий. Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) равно true, то данные в этом свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные в свойстве (\#getCategories.getCategories) — для основных серий.

**Возвращает:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Записывает внутреннюю книгу Excel в поток в памяти.

**Возвращает:**
byte[] - Возвращает массив байтов, содержащий копию внутренней книги Excel.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Инициализирует внутреннюю книгу Excel значением, указанным пользователем.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Поток, предоставленный пользователем, содержащий всю книгу Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Устанавливает диапазон данных диаграммы. Серии и категории будут обновлены на основе нового диапазона данных. Если количество серий в диапазоне данных превышает количество серий в данных диаграммы, то в конец коллекции будут добавлены дополнительные серии того же типа, что и последняя серия в текущей коллекции.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


Получает диапазон данных диаграммы.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Возвращает:**
java.lang.String - Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Представляет источник данных диаграммы

**Возвращает:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Представляет путь к внешней книге, если источник данных внешний, иначе null

**Возвращает:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


Получает тип встроенной книги. Возвращает [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined), если DataSourceType (\#getDataSourceType.getDataSourceType) равен [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Только для чтения [WorkbookType](../../com.aspose.slides/workbooktype).

**Возвращает:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Меняет местами данные по оси. Данные, построенные по оси X, будут перенесены на ось Y и наоборот.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Устанавливает внешнюю книгу как источник данных для диаграммы. Данные диаграммы будут обновлены из целевой книги.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Устанавливает внешнюю книгу как источник данных для диаграммы.

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

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |
| updateChartData | boolean | Если значение false, будет обновлен только путь к книге. Данные диаграммы не будут загружены и обновлены из целевой книги. Может использоваться, когда целевая книга не существует или недоступна. Если значение true, данные диаграммы будут обновлены из целевой книги. |