---
title: ChartData
second_title: Aspose.Slides для Android через Java API справочник
description: Представляет данные, используемые для построения диаграммы.
type: docs
url: /ru/com.aspose.slides/chartdata/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Представляет данные, используемые для построения диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Получает фабрику ячеек для создания ячеек, используемых для рядов диаграммы или категорий. |
| [getSeries()](#getSeries--) | Получает серии. |
| [getSeriesGroups()](#getSeriesGroups--) | Получает группы серий. |
| [getCategories()](#getCategories--) | Получает основные категории (или и основные, и вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null, и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Получает вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true. |
| [readWorkbookStream()](#readWorkbookStream--) | Записывает содержащуюся внутри Excel-книгу в поток в памяти. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Инициализирует содержащуюся внутри Excel-книгу пользовательским значением. |
| [getDataSourceType()](#getDataSourceType--) | Представляет путь внешней книги Excel, если используется внешний источник данных, иначе null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Представляет источник данных диаграммы. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Получает тип встроенной книги. |
| [getRange()](#getRange--) | Получает диапазон данных диаграммы. |
| [setRange(String formula)](#setRange-java.lang.String-) | Устанавливает диапазон данных диаграммы. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Устанавливает внешнюю книгу как источник данных для диаграммы. |
| [switchRowColumn()](#switchRowColumn--) | Меняет данные местами по осям. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Получает фабрику ячеек для создания ячеек, используемых для рядов диаграммы или категорий. Только чтение [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Возвращает:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Получает серии. Только чтение [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Возвращает:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Получает группы серий. Только чтение [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Каждая группа серий содержит серии с совместимыми типами. Группы совместимых типов серий определены и описаны с помощью перечисления CombinableSeriesTypesGroup. Также каждая группа серий содержит серии, отображаемые либо на первичной оси, либо на вторичной оси (не оба случая в одной группе). Таким образом, принцип группировки серий — это группировка по типам, упомянутым выше, и по типу отображения на первичной/вторичной оси. 2) Группа серий содержит некоторые свойства серий, общие для каждой серии в группе («свойства группы серий»). «Свойства группы серий» в классе ChartSeriesGroup доступны для чтения и записи. Каждое из «свойств группы серий» может иметь только для чтения проекцию в классе ChartSeries.

**Возвращает:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Получает основные категории (или одновременно основные и вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false). Только чтение [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // связанные категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // связанные категории series.getChart().getChartData().getCategories()
>  }
> ```

Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null, и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true, то данные свойства (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные свойства \#getCategories.getCategories — для основных серий.

**Возвращает:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. Если true, то данные свойства \#getSecondaryCategories.getSecondaryCategories используются для вторичных серий, а данные свойства \#getCategories.getCategories — для основных серий. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // связанные категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // связанные категории series.getChart().getChartData().getCategories()
>  }
> ```

**Возвращает:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Если false, то свойство \#getSecondaryCategories.getSecondaryCategories возвращает null и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. Если true, то данные свойства \#getSecondaryCategories.getSecondaryCategories используются для вторичных серий, а данные свойства \#getCategories.getCategories — для основных серий. Чтение/запись boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // связанные категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // связанные категории series.getChart().getChartData().getCategories()
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Получает вторичные категории, если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true. Только чтение [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // связанные категории series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // связанные категории series.getChart().getChartData().getCategories()
>  }
> ```

Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно false, то свойство (\#getSecondaryCategories.getSecondaryCategories) возвращает null и данные свойства \#getCategories.getCategories используются как для основных, так и для вторичных серий. Если свойство \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) равно true, то данные свойства (\#getSecondaryCategories.getSecondaryCategories) используются для вторичных серий, а данные свойства \#getCategories.getCategories — для основных серий.

**Возвращает:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Записывает содержащуюся внутри Excel-книгу в поток в памяти.

**Возвращает:**
byte[] - Возвращает экземпляр массива байтов, содержащий копию содержащейся внутри Excel-книги.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Инициализирует содержащуюся внутри Excel-книгу пользовательским значением.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ms | byte[] | Пользовательский поток, содержащий всю книгу Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Представляет путь внешней книги, если используется внешний источник данных, иначе null.

**Возвращает:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Представляет источник данных диаграммы.

**Возвращает:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Получает тип встроенной книги. Возвращает [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined), если DataSourceType (\#getDataSourceType.getDataSourceType) равен [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Только чтение [WorkbookType](../../com.aspose.slides/workbooktype).

**Возвращает:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Получает диапазон данных диаграммы.

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

**Возвращает:**
java.lang.String - Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Устанавливает диапазон данных диаграммы. Серии и категории будут обновлены в соответствии с новым диапазоном данных. Если количество серий в диапазоне данных превышает количество серий в данных диаграммы, то к концу коллекции будут добавлены дополнительные серии того же типа, что и последняя серия в текущей коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | java.lang.String | Формула диапазона данных ячеек. Например: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Устанавливает внешнюю книгу как источник данных для диаграммы.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| workbookPath | java.lang.String | Путь к целевой книге |
| updateChartData | boolean | Если значение false, будет обновлен только путь к книге. Данные диаграммы не будут загружены и обновлены из целевой книги. Может использоваться, когда целевая книга не существует или недоступна. Если значение true, данные диаграммы будут обновлены из целевой книги. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Меняет данные местами по осям. Данные, построенные по оси X, будут перемещены на ось Y и наоборот.