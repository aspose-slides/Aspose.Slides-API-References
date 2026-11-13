---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Представляет данные, используемые для построения диаграммы.
type: docs
url: /ru/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Представляет данные, используемые для построения диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Получает фабрику ячеек для создания ячеек, используемых в рядах или категориях диаграммы. |
| [getSeries()](#getSeries--) | Получает ряды. |
| [getSeriesGroups()](#getSeriesGroups--) | Получает группы рядов. |
| [getCategories()](#getCategories--) | Получает основные категории (или как основные, так и вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Получает вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение true. |
| [readWorkbookStream()](#readWorkbookStream--) | Записывает внутреннюю книгу Excel в поток в памяти. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Инициализирует внутреннюю книгу Excel значением, указанным пользователем. |
| [setRange(String formula)](#setRange-java.lang.String-) | Устанавливает диапазон данных диаграммы. |
| [getRange()](#getRange--) | Получает диапазон данных диаграммы. |
| [getDataSourceType()](#getDataSourceType--) | Представляет источник данных диаграммы |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Представляет путь к внешней книге, если источник данных внешней, иначе null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Получает тип встроенной книги. |
| [switchRowColumn()](#switchRowColumn--) | Меняет местами данные по оси. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [refreshData()](#refreshData--) | Обновляет данные диаграммы, перезагружая их из исходной книги. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Получает фабрику ячеек для создания ячеек, используемых в рядах или категориях диаграммы. Только для чтения [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Возвращает:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Получает ряды. Только для чтения [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Возвращает:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Получает группы рядов. Только для чтения [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Каждая группа рядов содержит ряды с совместимыми типами. Группы совместимых типов рядов определены и описаны перечислением CombinableSeriesTypesGroup. Также каждая группа рядов содержит ряды, которые отображаются либо на основной оси, либо на вторичной оси (не обе ситуации в одной группе). Таким образом, принцип группировки рядов — группировка по типовым группам, упомянутым выше, и по типу отображения (основной/вторичный). 2) Группа рядов содержит некоторые свойства рядов, общие для каждого ряда в группе («свойства группы рядов»). «Свойства группы рядов» в классе ChartSeriesGroup доступны для чтения/записи. Каждое из «свойств группы рядов» может иметь только для чтения проекцию в классе ChartSeries.

**Возвращает:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Получает основные категории (или как основные, так и вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение false). Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```


--------------------

Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. Если свойство ... имеет значение true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных рядов, а данные в свойстве (\#getCategories.getCategories) — для основных рядов.

**Возвращает:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. Если true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных рядов, а данные в свойстве (\#getCategories.getCategories) — для основных рядов. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```


**Возвращает:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Если false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. Если true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных рядов, а данные в свойстве (\#getCategories.getCategories) — для основных рядов. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Получает вторичные категории, если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение true. Только для чтения [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // соответствующие категории — series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // соответствующие категории — series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Если свойство (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) имеет значение false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, а данные в свойстве (\#getCategories.getCategories) используются как для основных, так и для вторичных рядов. Если свойство ... имеет значение true, то данные в свойстве (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных рядов, а данные в свойстве (\#getCategories.getCategories) — для основных рядов.

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| ms | byte[] | Поток, предоставленный пользователем, содержащий всю книгу Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Устанавливает диапазон данных диаграммы. Ряды и категории будут обновлены в соответствии с новым диапазоном данных. Если количество рядов в диапазоне данных больше, чем количество рядов в данных диаграммы, то дополнительные ряды того же типа, что и последний ряд в текущей коллекции, будут добавлены в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
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

Представляет путь к внешней книге, если источник данных внешней, иначе null

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

Меняет местами данные по оси. Данные, построенные по оси X, будут перемещены на ось Y и наоборот.

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
| Параметр | Тип | Описание |
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
| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |
| updateChartData | boolean | Если значение false, только путь к книге будет обновлен. Данные диаграммы не будут загружены и обновлены из целевой книги. Может использоваться, когда целевая книга не существует или недоступна. Если значение true, данные диаграммы будут обновлены из целевой книги. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Обновляет данные диаграммы, перезагружая их из исходной книги.

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